# CarND-Controls-PID
Self-Driving Car Engineer Nanodegree Program

---

### Project description

Write a PID (Proportial, integral, and differential ) controller, to guide the car
through the track. The most important task

To write this project the YouTube Q&A was followed:
https://www.youtube.com/watch?v=YamBuzDjrs8&feature=youtu.be

### Results

The value for the parameters Kx in the PID.cpp file are the following:

`
double init_Kp = -0.06;
double init_Ki = -0.0001;
double init_Kd = -0.92;
`

These values were adjusted manually. For example, the value Kp was set by making
sure that the car did not steer wildly while going on a straight path. The value
for Kd was adjusted by looking at the response of the car when coming to a curve.
The value was increased as I noticed that car needed to steer faster to get back
to the center of the road. The value of Ki was chosen to be very small to have a
smoother comeback to the center of the road as explained in the lectures.

The throttle value was left at 0.3 and the car can run several laps with out leaving
the road.