# Smart-Move

Controlling a 2D automobile with just 4 arrow keys.

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
