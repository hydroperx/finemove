# Smart-Move

Controlling a car with just 4 arrow keys, whether in 2D or 3D spaces,
points to a new manner of driving
without a steer and real life mechanisms.

![](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/7c3b69bc-4b20-47af-b3c2-3defa3e34060/dhs4fha-043d0bf7-6b1f-4bca-a6bc-bfe3dd628ac2.png/v1/fit/w_512,h_512,q_70,strp/the_car__the_shark__drift_by_hydroper_dhs4fha-375w-2x.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NTEyIiwicGF0aCI6IlwvZlwvN2MzYjY5YmMtNGIyMC00N2FmLWIzYzItM2RlZmEzZTM0MDYwXC9kaHM0ZmhhLTA0M2QwYmY3LTZiMWYtNGJjYS1hNmJjLWJmZTNkZDYyOGFjMi5wbmciLCJ3aWR0aCI6Ijw9NTEyIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmltYWdlLm9wZXJhdGlvbnMiXX0.l8g9xUkyMeixj1iCFLQ5tLiL6VNZkvx_uugt_x21vFA)

Click the following picture to watch the Smart Move:

<p align="center">

[![image](https://github.com/user-attachments/assets/1c946ffa-03e6-4559-9e9e-db0fbfe9737f)](https://m.youtube.com/watch?v=e1iCEF_LlP8)

</p>

## 2D coordinates

* $x = \text{horizontal position from -Infinity to zero to +Infinity}$
* $y = \text{vertical position from -Infinity to zero to +Infinity}$
* $w = \text{rotation ratio (percentage, radians, or degrees) from -Infinity to zero to +Infinity}$

The rotation ($w$) is often expressed as degrees (0, 45, 90, 180, 360, ...).

* 90° degrees means *lie to the next side*.
* 180° degrees means *lie to the bottom*.
* 360° degrees is the identity rotation, viewed the same way as 0° degrees.

A rotation changes either in the clockwise direction, or in the counter clockwise direction, or is in inertia.

## Keyboard Layout

For the Smart Move, just 4 arrows are enough, positioned as in the following picture.

![image](https://github.com/user-attachments/assets/68e2c81e-960f-4eb8-8946-4894aacdbb5c)

The automobile may perform one of the following combinations:

* UP (NORTH)
* UP-LEFT (NORTHWEST)
* UP-RIGHT (NORTHEAST)
* DOWN (SOUTH)
* DOWN-LEFT (SOUTHWEST)
* DOWN-RIGHT (SOUTHEAST)

The automobile moves smoothly or abruptly to that combination's direction according to key pressure.

## Performing a Drift

The automobile is a box into a larger circunference which is partitioned into 4 parts, forming 4 triangles each with a uniform curved hypotenuse side.

![image](https://github.com/user-attachments/assets/72b02679-dc2f-40b2-aa48-d3f208c213c6)

How the automobile moves depends in its box rotation (commonly in degrees); the pressed combination causes:

* the automobile's box to rotate (either clockwise, counter clockwise, or inertia);
* the $x, y$ coordinates each change according to simple trigonometric functions.
