# Finger-Pulse-Sensor-Module
The finger-pulse sensor module uses a photoelectric plethysmograph, which is a device that uses light to measure blood volume changes in the finger. The module typically connects to an Arduino board via three pins: power, ground, and a digital output pin. The output pin will output a pulse signal that can be used to measure the heart rate.

In this code, the finger-pulse sensor is connected to digital pin 2, and the heart rate is calculated by multiplying the pulse count by 6 (since the pulse signal is typically generated at a rate of one pulse per second). The heart rate is then printed to the serial port, so you can view it using the Arduino serial monitor.
