# Maniatis_et_al_2020_in_review
In this repository you can find the rawd data used for the publication: 
by Maniatis et al., 2020: "Inertial drag and lift forces for coarse grains on rough alluvial beds",Earth Surface Dynamic, currently in review

There are two data sets:

- The first is for the laboratory experiments performed in the flume facilities of the University of Glasgow (2013-2014) for both the spherical and the ellipsoid of the sensors.

- The second corresponds to the field experiments pefromed in River Erlenbach (May 2018) and correspond to the ellipsoid only. 

Notes: 
- A lot of sensors have the facility for "on-board filtering" for deriving body frame linear accelerations. The model described in the paper starts a step before that in order to explain the physics of the accelerometer measurementin relation to sediment transport. Here the raw accelerormeter and gyroscope measurements are provided. For the accelerometer measurements this corresponds to body frame accelerations before gravity compensation (and corresponding callibration, see thesis Maniatis 2016, chapter 6). 

- The initial oriantation of the sensor for each experiment is described in the paper. The corresponding quaternions were measured using the Yei sensor which provides that facility (and includes a correction from the magnetometer deployed in the sensor, see sensor datasheet).

Specifically for the field experiments:
These are the time series as they occured 1 second after the release of the sensor up to the begining of the 10 second cesation as described in the paper. If the field timeseries are rotated correclty and combined to a single dataset, they recreate the histograms of Figure C1 in the paper. 


Thesis:
Maniatis, G.: Eulerian-Lagrangian definition of coarse bed-load transport: theory and verification with low-cost inertial measurement units,
Ph.D. thesis, University of Glasgow, 2016.
