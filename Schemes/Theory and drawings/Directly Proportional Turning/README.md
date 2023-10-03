The maximum left turn on the servo is 0, and the maximum right turn is 180, while 90 is the center.
The variable "diff" is defined as the distance to the left minus the distance to the right. 
A positive diff value is the distance means it's closer to the right, and vice versa. The minimum and maximum diff values are -300 and 300 respectively.
Our equation takes all the into account and makes the servo turn depending on the diff, it is directly proportional. 

Our equation is angle = -0.3(diff) + 90
