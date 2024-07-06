# clawbot-sensors

Bumper sensor:
This detects whether the bumper is being pressed or not (i.e. there is an object touching the robot), and then the robot takes an action based on that. Here, the robot goes straight from its starting position, hits an object, then goes back to the starting point. Next, it makes a 90 degree turn. This happens 3 more times until the robot has gone north, south, east and west.

Ultrasonic distance sensor:
This monitors the distance the robot has traveled in a certain period, and then the robot takes an action based on that. This was demonstrated with the robot moving through a simple "maze" from a start point to an end point.

Gyro sensor:
This enables the robot to make correct turns of certain angles. The robot followed a "track" of tape and made the following turns: 90 degree left, 90 degree left, 135 degree right, 45 degree right.

Color sensor:
This enables the robot to "see" and distinguish between certain colors of objects that are held up to the sensor. Here, the robot detected whether the piece of paper was red, blue or green, and it turned and moved accordingly (different for each of the colors mentioned).

Color sensor - line tracking:
The same sensor was used as above. The robot was supposed to follow a track of red tape that was straight in some spots and curved in others. One important aspect was the fact that the color sensor also had a light on it and its brightness could be changed, and red reflects more light than gray (floor), so that was important to keeping the robot on the track.
