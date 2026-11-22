# waveshare-test
This repository will house a node network for the purposes of testing on Waveshare's Wave Rover, which is a test robot that will be used to help us test and develop the software stack for Bender 2027. The repository will have a ROS2 Jazzy workspace with the goal of publishing map data from sensor and pose data, and output motor commands to the Wave Rover.

The initial plan is to run this code on an 8GB Raspberry Pi 5 that is running Ubuntu 24.04 with a headless SSH setup. The raspberry pi will be able to be SSH'ed into from a laptop without the need for wiring up peripherals such as a keyboard or monitor. This RPi will then be hooked up to the GPIO bus on the Wave Rover.
