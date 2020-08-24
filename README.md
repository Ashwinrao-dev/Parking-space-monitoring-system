# Parking space monitoring system

Automated system built to display the number of vehicles inside the parking lot. 
It will display 'FULL' if there is no space for anymore vehicles.


Working:
The system works on the principle of counter.
With the help of installed IR sensors at the gates the arriving and departing cars can be monitored. 
The data from the sensors is perceived by the FPGA in which the code is already loaded. 
This FPGA kit is connected to GPIO card in which seven segment display will display the count.
