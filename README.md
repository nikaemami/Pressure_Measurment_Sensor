# Pressure_Sensor
Printing the pressure measured by connecting a MPX4115 sensor to a power supply, on an lcd connected to a micro-controller.

First, I connected the sensor to a power supply, and measured the output of the sensor in enough points in the range of its possible input values. The results are shown in the table below:

Then, by using the cftool in MATLAB, I fit the best curve possible to the data. The equation of the curve is as follows:

By using the equation above, and using a STM32 micro-controller, I wrote a program to measure the pressure with the sensor, and print the result on an lcd connected to the micro-controller.

The final result:
