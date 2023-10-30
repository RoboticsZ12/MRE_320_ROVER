# MRE_320_ROVER
For the final project, we are tasked with creating a mars rover with the aid from @Brandon_Hickey. The project is split into four seperate components. 
1) Hardware design
   ->Basic configuration for the body of the rover.
   
      a. Electrical setup
         ->Setting up motors, radio, and telemetry devices.
3) Avionics
   ->Configuring key software to communicate with the rasberry pi microcontroller, the brain of the rover.
4) External sensor
   ->We must attach an external sensor, most likely the DHT-11 temperature sensor, to compare with the data from the rasberry pi. Comparing both sets of data will ensure the precision/accuracy of each sensor. 

Once again, our steps for the configuration was guided by @Brandon_Hickey. However, to ensure the rover operated as intended, we needed to fine tune our own PID controller and set our own waypoints. The main objective of the project was simple. We needed to not only create a rover that would operate efficiently and transmit data, but we also needed to configure the rover to operate on a certain path in a timely manner. 

This path is described and shown in file "Rover_Project" then "Avionics". The goal is to run this path as accurate as possible and be able to run the path in a timely manner. Through PID tuning and ensuring there are no interferences, such as friction, with the rovers hardware, we should be able to configure a rover that is accurate, agile, and data transmitting. 
