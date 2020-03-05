# PSU-Anechoic-Chamber

This repo contains information regarding the capabilities, available equipment,
and operation of the anechoic chamber. This page contains an overview of each 
of the pages of documentation and tools located in the respective folders as
well as links to those documents.

## [DAMS System Overview](documentation/dams/)

The Penn State anechoic chamber uses a Diamond Engineering positioner and it's
associated software to take measurements. This software is called "Desktop
Antenna Measurement System", or DAMS. Antenna measurement with this software
basically comes down to the following steps, all of which are explained in more
detail in the [DAMS documentation](documentation/dams/):

1. Open DAMS
2. Maneuver the positioner to the "zero position" and set it as "zero"
3. Define the details of the measurement, e.g. over what angles the measurement
   will be taken, and at what intervals. Things like the frequency sweep, number
   of points, etc. are set on the network analyzer and read by DAMS when the
   measurement starts.
4. Set whether the measurement is a one or two plane measurement
5. Choose what frequency to monitor in the live plot
6. Run whichever sweep is appropriate for your measurement (AzEl, Elevation,
   Azimuth)

## [Measurement](documentation/measurement/)

TODO: Give brief overview of calibration, what is needed to take a good
measurement, etc. 

## Misc. Tools

* [ChamberPlot](https://github.com/HRG-Lab/ChamberPlot)
* [SciKit-RF](http://scikit-rf.org/)
* Calibration

Spreadsheet of components is at [PSU EE Anechoic Chamber Components](https://docs.google.com/spreadsheets/d/1eteUvV0Tn92JbzLjsZK2wsClNtTWEccetH6lqHVsjVo/edit?usp=sharing)
