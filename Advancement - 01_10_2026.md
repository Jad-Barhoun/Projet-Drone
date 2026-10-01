# Project Advancement — 01/10/2026

## Work completed

Today, we made several important advances on the drone and RC controller.

### Drone

* Changed the drone **microcontroller** to the **STM32F411RET6**.
* Changed the **IMU** to the **LSM6DSO16ISTR**.
* Redrew and updated the **drone electrical schematic** with the new components and their connections.
* Chosen the **LED orientation convention**:

  * **Red:** left side
  * **Green:** right side
  * **White:** back
  * **White:** front

### RC Controller

* Selected the **STM32G031K8** as the microcontroller for the RC controller.
* Designed the **electrical schematic of the RC controller**.
* Selected and connected the main components of the controller.

### Component testing

* Tested both **microcontrollers** with basic programs to get familiar with the development environment and IDE.
* Tested the **radio modules** as a preliminary test.

## TODO

### Drone testing

* Test the **LSM6DSO16ISTR IMU** and verify that the sensor readings are correct.
* Test the **motors**.
* Measure/evaluate the **lift force** produced by the motors.

### PCB design

* Determine the optimal **placement of all components and their footprints** on the PCB, taking into account the drone's weight distribution and balance.
* Complete the **PCB layout and routing**, while considering component placement, connections, and overall PCB constraints.
* Continue developing the PCB layout for both the drone and RC controller.
