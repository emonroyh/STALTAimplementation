# STA/LTA algorithm implementation

## The notebook implements the STA/LTA algorithm in seismological data

The *'short-time-average through long-time-average trigger'* (**STA/LTA**) is the most broadly used algorithm in weak-motion seismology. It continuously calculates the average values of the absolute amplitude of a seismic signal in two consecutive moving-time windows.

The AZ.PFO.txt contains reading from a seismological station. They are actual readinigs and contain seismic events captured on 08/09/2017.

The dataset contains 4 components:

- Time 't' in seconds (starting from 2017-09-08T00:00:00)
- East - West, 
- North - South,
- and Up - Down (which can be considered as X axis, Y axis, Z axis).