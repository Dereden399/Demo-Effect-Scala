# Demo Effects written on scala
I made these 2 demo effects on scala for "Programming studio 1" course in Aalto university, but decided, that it would be great to post it here too.
## Effects I made:
- src/main/scala/s1/demo/effects/ParasDemo.scala - waves
- src/main/scala/s1/demo/effects/ParasDemo2.scala - ball
### I did not write other files, they were all made by course's teacher and assistants

## Waves
In this effect I made simple waves, those center is moving across the screen and color parts are spinning. The color of the pixel is decided by the sum of distance from the center and time. Color parts are just a Cartesian coordinate system, that is spinning using the matrice every frame

## Ball
This effect is much harder, because I tried to simulate 3d ball in 2d space. The position of ball, position of light, color and rotation are calculated using (x, y) coordinates of the pixel. Rotation of the ball's axis is made using quaternions
