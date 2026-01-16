# Delft-Dryad
Making an agile drone that hopefully one day will be able to take videos of people in complex enviroments .</br>
This is an TU Delft [RSA](https://rsadelft.nl/) project that was unveiled on Q3 project meeting.
## Objectives
1. Make a drone that uses custom AI model for person tracking
2. Able to show agility with dodging obstacles while not losing track of the person
3. Keep the drone as small as possible for increased agility


## Timeline
### Prototype(done by 2026 Q4)
- Hardware:
  - Drone - BetaFPV Pavo Pico that can take off from the ground and spin in place
  - Microcontroller - stm32n6 with a (custom) Ai model for people detection
  - Stm32 controlls the included flight controller by giving directions
- Software:
  - Drone can keep the person moving around it in the centre of the camera image by rotating on its z axis
### Dryad v1(done by 2027 Q2) 
- Hardware:
  - Drone - BetaFPV Pavo Pico/ custom built
  - Microcontroller - stm32n6 with a custom Ai model for people detection
  - custom pcb for stm32 and related electronics
- Software:
  - Drone can follow a person in an open plain keep a constant distance
### Dryad v2
- Fully controlled by stm32n6 only as the singular controller
- Able to keep up with a running person through a forest without losing sight of him

  
### Future features:
- custom drone build
- stm32n6 being used also as the primary flight computer
- lidar for obstacle detection
- path planning to avoid obstacles
- following a person
- custom ai model used also for obstacle detection and filtering other people
- SD card for recording the footage
- baby mode -> doesnt let user crash the drone
- broadcasting the image to a computer with a nice vizualizator
- usb c battery charging
- gps for drone tracking
