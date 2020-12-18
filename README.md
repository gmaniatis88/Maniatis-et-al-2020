# Maniatis_et_al_2020
In this repository you can find the data presented in the manuscript: Maniatis et al.,: "Inertial drag and lift forces for coarse grains on rough alluvial beds measured using in-grain accelerometers", Earth Surface Dynamics, accepted in late 2020.

There are two data sets:

- The first is for the laboratory experiments performed in the flume facilities of the University of Glasgow (2013-2014) for both the spherical and the ellipsoid of the sensors.

- The second corresponds to the field experiments pefromed in River Erlenbach (May 2018) and correspond to the ellipsoid only. 

Notes: 
- A lot of sensors have the facility for "on-board filtering" for deriving body frame linear accelerations. The model described in the paper starts a step before that in order to explain the physics of the accelerometer measurementin relation to sediment transport. Here, for the laboratory experiments, raw accelerormeter and gyroscope measurements are provided. For the accelerometer measurements this corresponds to body frame accelerations before gravity compensation (and corresponding callibration, see thesis Maniatis 2016, chapter 6). 

- The initial oriantation of the sensor for each experiment is defined in the paper. The orientation quaternions were measured using the solution of  Valenti et al., 2015 for the b-i quaternion as defined in the paper (Appendix A1). In addition, the Yei sensor which provides that facility and includes a correction from the magnetometer deployed in the sensor. This was used to crosscompare the solution and define the noise threshold for the accelerometer. 

- For the field experiments, we provide the time series of the drag and lift forces as they occured 1 second after the release of the sensor and up to the begining of the 10 second cesation as described in the paper. 


References:

Maniatis, G.: Eulerian-Lagrangian definition of coarse bed-load transport: theory and verification with low-cost inertial measurement units,
Ph.D. thesis, University of Glasgow, 2016.

Valenti, R.G., Dryanovski, I. and Xiao, J., 2015. Keeping a good attitude: A quaternion-based orientation filter for IMUs and MARGs. Sensors, 15(8), pp.19302-19330.
