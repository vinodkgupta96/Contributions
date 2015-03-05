#Comment from Mark A. Yoder

# Demo       5
# ReadMe.txt 5
# Fritzing   0
# Code       10


Grade:  20/25

================================================


To: Mark A Yoder
From: Vinod Kumar
Subject: Lab 07 Submission
Partner's Name : Shiva Verma Soni
Name: Vinod Kumar
Roll No.: B13141

	



In This Lab we find the acceleration of an object , the temperature around surroundings.
	
In this lab the Gyroscope is connected to Beaglebone given in lab digram. We  connected the 4 pins (vdd, GND ,XCL, XDA ) tobone. We used the analog input pins to read the data from the gyroscope. In the code "gyro_b13141.js" and "gyro2_b13141.js" data is sent in array with each element of data 8 bits each. 0 to 5  for accelorometer, (6 ,7) for  temperature sensor and (8 to 13) correspond to gyroscope readings. The gyroscope sends data in 8 bits each. we Sheifted bits  by eight unit and adding the corresponding elements together, we got the respective values of acceleration, temperature and gyroscope. 
Conclusions:

This lab gave some basic undestandings of the gyroscopic sensor, which is widely used in solving real world problem.This is will also increase the knowledge while doing peooject based on sensors.