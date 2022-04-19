.. _data:

****
Data
****

Overview
========

Data Description
----------------

+---------+-------------------------+-----------------------------------------------------------------------+
| Level   | Product                 | Description                                                           |
+---------+-------------------------+-----------------------------------------------------------------------+
| 1       | Counts                  | Raw time-ordered instrument data for each differential channel (x31)  |
|         |                         | binned data in energy ranges, number of times that detector exceeded  |
|         |                         | a threshold anything that triggers a thresholds singles counts (x16)  |
+---------+-------------------------+-----------------------------------------------------------------------+
| 1       | Pulse Heights           | Pulse Height of triggers above threshold                              |
|         |                         | (particles events raw events pulses)                                  |
|         |                         | checksum validated                                                    |
+---------+-------------------------+-----------------------------------------------------------------------+
| 2       |Electron Energy Spectra  | Electron spectra in physical units                                    |
+---------+-------------------------+-----------------------------------------------------------------------+
| 2       | Proton Energy Spectra   | Proton spectra in physical units                                      |
+---------+-------------------------+-----------------------------------------------------------------------+
| 3       | TBD                     |                                                                       |
+---------+-------------------------+-----------------------------------------------------------------------+
| QL      | Counts                  | Same as Level 1 but deadtime corrected                                |
+---------+-------------------------+-----------------------------------------------------------------------+


Getting Data
============



Reading Data
============



Calibrating Data
================
Data products below level 2 generally require calibration to be transformed into scientificically useable units.
This section describes how to calibrate data files from lower to higher levels.