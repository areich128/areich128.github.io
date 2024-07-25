# General Projects

<!
## Altamira Rocket
Over the 2024 summer, I took on this project as a way to prepare for my role as the CU SRL Avionics Lead.

### Altamira Requirements
I will be using the BeagleBone Black microcontroller and NASA's FPrime embedded systems framework. The rocket should be able therefore to house these components, as well as return them to the ground safely.

### Altamira Design
To fulfill these requirements, I designed a 3" diameter low-powered rocket. The fins, nosecone, and AV bay are custom designed to be 3D printed. Design was informed by calculations done in OpenRocket

![AltamiraOpenRocketDesign](https://areich128.github.io/AltamiraORK.png)
*Altamira OpenRocket Design*

![AltamiraFlightSim](https://areich128.github.io/AltamiraFlightSim.png)
*Altamira Flight Simulation*

![AltamiraOnShape](https://areich128.github.io/AltamiraOnShape.png)
*Altamira OnShape Assembly*

Estes rockets only have a delay of either 4 or 6 seconds. Due to the weight of the necessary components, a 6 second delay from burnout to apogee is not possible with the motor I have chosen (F15). As such, weight will be added to the nosecone in order to decrease apogee to as close to 4 seconds after burnout as possible.
- Delay needs to be timed correctly to avoid extreme load on the parachute/recovery system

### Avionics

Originally, the plan was to use two sensors: the BMP388 (for temperature, pressure, and altitude) and the BNO085 sensor (for accelerometer, gyroscope, magnetometer, and orientation). However, the BNO uses Sensor Hub Transport Protocol (SHTP) on top of the basic I2C communication. Since I am writing custom drivers, this posed a large challenge for me and I decided to focus on the BMP.

The BMP driver is relatively simple. All it does is initialize the sensor, write the desired settings, calibrate, then continually poll for telemetry. The altitude reading is inferred from the pressure and temperature sensors.

The FPrime Ground Data System will then run locally on the BeagleBone in lieu of a downlink system. This will stream telemetry over port 50000, which will be picked up by a bash script and saved to an onboard SD card.

**Launch Date: July 27** at Fiesta Island
>

## Window Shutter

## Hydrogen generator

Back to [home](https://areich128.github.io)