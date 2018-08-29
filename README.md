# SensorSample

The Android platform provides several sensors that enable your app to monitor the motion or position of a device, in addition to other sensors such as the light sensor.
Motion sensors such as the accelerometer or gyroscope are useful for monitoring device movement such as tilt, shake, rotation, or swing. Position sensors are useful for determining a device's physical position in relation to the Earth. For example, you can use a device's geomagnetic field sensor to determine its position relative to the magnetic north pole.
A common use of motion and position sensors, especially for games, is to determine the orientation of the device, that is, the device's bearing (north/south/east/west) and tilt. For example, a driving game could allow the user to control acceleration with a forward tilt or backward tilt, and control steering with a left tilt or right tilt.

The SensorSample app displays the device orientation angles as numbers and as colored spots along the four edges of the device screen. There are three components to device orientation
1. Azimuth : The direction (north/south/east/west) the device is pointing. 0 is magnetic north.
2. Pitch : The top-to-bottom tilt of the device. 0 is flat.
3. Roll : The left-to-right tilt of the device. 0 is flat.
When you tilt the device, the spots along the edges that are tilted up become darker.


# What you should already KNOW

You should be familiar with:
Creating, building, and running apps in Android Studio.
Using the Android sensor framework to gain access to available sensors on the device, and to register and unregister listeners for those sensors.
Using the onSensorChanged() method from the SensorEventListener interface to handle changes to sensor data.

# What you will LEARN

What the accelerometer and magnetometer sensors do.
The differences between the device-coordinate system and the Earth coordinate system, and which sensors use which systems.
Orientation angles (azimuth, pitch, roll), and how they relate to other coordinate systems.
How to use methods from the sensor manager to get the device orientation angles.
How activity rotation (portrait or landscape) affects sensor input.

