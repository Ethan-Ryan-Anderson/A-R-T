# Explanations on how I plan to implement each feature

### Planned Features
A List of planned features

* Lap Counter / Timer
* Lap timer
* Measure acceleration, deceleration, and tilt for better analysis of riding dynamics.
* Lap time comparisons, to compare inside-outside lines or diffrent rythms
* Built in gate-drop training
* Jump Distance Measurer (This one isnt really practical it would just be cool to know exactly how far Im jumping)

# Lap Counter/Timer
For prototyping and proof of concept, This will be implemented with a handle bar button.

# Lap Timer
Planning to use GPS waypoints and system time to mark the completed laps and then do the math to calculate time.
This waypoint based approach should allow for splits on diffrent parts of the track

# Measure acceleration, deceleration, and tilt for better analysis of riding dynamics.
This can just be done with a simple gyroscope and accelerometer.

# Lap time comparisons, to compare inside-outside lines or diffrent rythms
Will take the gps, data and parse on track positions to see which lines are faster

#Built in gate-drop training
Give rider 30 second, 15 second warnings and then a final alert, then see detect the diffrence from the time of the final alert and the time the accelerometer detects a set amount of forward momentum.

# Jump Distance Measurer
Not really sure, but this isnt a make or brake feature, but im looking at trying to parse G-Force Data
