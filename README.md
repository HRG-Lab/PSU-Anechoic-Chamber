# PSU-Anechoic-Chamber

This repo contains information regarding the capabilities, available equipment, and operation of the anechoic chamber. This page contains an overview of each of the pages of documentation and tools located in the respective folders as well as links to those documents.

## Chamber Overview

The Penn State EE East 329 Anechoic Chamber has two main rooms: the actual chamber, and the control room. The control room is only accesible via Penn State ID card, and the chamber is padlocked unless it is currently in use. To request access, email Dr. Huff at ghuff@psu.edu.

TODO: Frequency range of the Chamber

A full list of horns available for measurement as well as a system block diagram (including a list of components) can be found [here](documentation/README.md)

To simplify measurements, both the control PC and PNA can be accessed via remote desktop and there is a camera in the chamber that can be used to monitor. 

### Remote Chamber Access

To do remote measurements, you need to do the following:

* Connect to the Penn State College of Engineering VPN ([more info here](https://www.ncts.psu.edu/vpn/))
* Remote in to the PNA and Control Room PC:
    * Open Remote Desktop (on Windows / OSX) or Remmina (Linux)
    * For Server Address, use the following IP addresses:
        * 130.203.194.233 (Control Room PC)
        * 130.203.194.234 (PNA)
    * Log in to the Chamber camera by navigating to the following IP in a browser either on your PC or in your remote desktop window for the Control Room PC and logging in using provided credentials
        * 172.28.184.23



## [DAMS System Overview](documentation/dams/)

The Penn State anechoic chamber uses a Diamond Engineering positioner and its associated software to take measurements. This software is called "Desktop Antenna Measurement System", or DAMS. Antenna measurement with this software basically comes down to the following steps, all of which are explained in more detail in the [DAMS documentation](documentation/dams/):

1. Open DAMS
2. Maneuver the positioner to the "zero position" and set it as "zero"
3. Define the details of the measurement, e.g. over what angles the measurement will be taken, and at what intervals. Things like the frequency sweep, number of points, etc. are set on the network analyzer and read by DAMS when the measurement starts.
4. Set whether the measurement is a one or two plane measurement
5. Choose what frequency to monitor in the live plot
6. Run whichever sweep is appropriate for your measurement (AzEl, Elevation,
   Azimuth)

## [Measurement](documentation/measurement/)

TODO: Give brief overview of calibration, what is needed to take a good
measurement, etc.

## Misc. Tools

* [SciKit-RF](http://scikit-rf.org/)
