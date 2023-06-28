## Smart Car - Automation in Conventional Cars

https://user-images.githubusercontent.com/17024368/221351044-22c8ebd1-1e3c-4490-9d72-5d20201e6e96.mp4


https://user-images.githubusercontent.com/17024368/221350997-c66f5fb0-8862-4e18-8efa-a08b9cba6346.mp4


Tesla's autopilot has been word of mouth to everyone these days. It's amazing how the car has brought self driving capabilities to mainstream usage. A lot of work is being done in adding automation to electric cars around the world, but Zero work to bring it to mainstream in conventional Petrol/Diesel cars that makes the bulk of the vehicle market today and will continue to remain dominant for a long time.
There are approximately 9-10 Crore registered motor vehicles in India today and about 50 lakh passenger cars added to the India market every year.
This project aims to develop systems to add 'Limited' self driving capabilities and basic automation to these non-electric conventional cars and create 'Conversion Kits' that would include things like electronically controllable Steering Wheel, accelerator, brakes, sensors, control module etc which can be installed in any car and it would become 'Smart' Car.
Thus self driving capabilities won't be limited to modern electric cars only but also for conventional Petrol/Diesel cars be it Maruti 800 or Wagon R or any other car present on Indian Roads today.

Currently the job is to collect Human-Vehicle Interaction data, specifically on Indian road conditions with the help of sensors like Lidar, GPS, Accelerator/Brake/Clutch position data corresponding to speed. In the current setup, a Hyundai Eon car has been modified such that it can be turned on as well as steering can be controlled via a Smartphone. Positional sensors are to be placed at steering wheel and Accelerator/Brake/Clutch that would collect the data of how car drives when a human is driving it, eg. The position of the steering wheel while the car turns, position of Accelerator/Clutch while speeding or gear changing, and later on use this data to train an autonomous system using Machine Learning that would drive the car.

The project is running in a phase by phase system and once one part is developed and tested rigorously, only then it moves over to the next phase.
Similar to steering wheel in current setup, next is to place motors and linear actuators on Accelerator/Brake/Clutch so that they can be precisely controlled via electronic signals and after collecting enough driving data, build a Machine Learning Algorithm around the collected data that would run on a single board computer like Raspberry Pi and test it on real world conditions of Indian roads. 
