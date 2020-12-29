
# Maniatis_et_al_2020
In this repository you can find the data presented in the manuscript: Maniatis et al.,: "Inertial drag and lift forces for coarse grains on rough alluvial beds measured using in-grain accelerometers", Earth Surface Dynamics, accepted in late 2020.

There are two datasets:

The first is for the laboratory experiments performed in the flume facilities of the University of Glasgow (2013-2015) for both the spherical and the ellipsoid of the sensors. A whole laboratory run for the sphere and and an example of how the ellispoid behaved close to entrainment is shown here: https://www.youtube.com/playlist?list=PLzxFBJ2sEYx7PaRsbkuxqpw0bXcDPfZe2. In the .zip files, the time-series are included as used in the analysis for the calculation of impulses in the paper. The time series used at this step do not include the 10s cessation period (are cut at the point where the sensor stopped moving). Complete experimental runs for each enclosure (one for the sphere and one for the ellipsoid including the cessation period) are also provided in the Github repository (https://github.com/gmaniatis88/Maniatis-et-al-2020) as separate files, for the better understanding of the laboratory experimental procedure (Sphere_full_run_lab.csv and Ellipsoid_1_full_run_lab.csv). The Sphere_full_run_lab.csv for the sphere was also used in the Figures 3 and B1 of the paper.

The second dataset corresponds to the field experiments performed in River Erlenbach (May 2018) and is for the ellipsoid only. Those runs include the seconds from the cessation period because the transport was very short and it would be very difficult to interpret the motion otherwise. Also, note that for those experiments the final and transformed Drag and Lift inertial forces are provided, as discussed in the paper, and not the raw sensor data.

Notes:

- A lot of sensors have the facility for "on-board filtering" for deriving body frame linear accelerations. The model described in the paper starts a step before that in order to explain the physics of the accelerometer measurement relation to sediment transport. In this context, the raw accelerometer measurements provided for the lab experiments are the body frame accelerations before gravity compensation (for relevant calibration, see thesis Maniatis 2016, chapter 6).

- The initial oriantation of the sensor for each experiment is defined in the paper. The orientation quaternions were approximated using the auxiliary solution of Valenti et al., 2015 for the b-i quaternion as defined in the paper (Appendix A1). In addition, the Yei sensor which provides that facility and includes a correction from the magnetometer deployed in the sensor. This was used to cross-compare the solution and define the noise threshold for the accelerometer.

References:

Maniatis, G.: Eulerian-Lagrangian definition of coarse bed-load transport: theory and verification with low-cost inertial measurement units, Ph.D. thesis, University of Glasgow, 2016.

Valenti, R.G., Dryanovski, I. and Xiao, J., 2015. Keeping a good attitude: A quaternion-based orientation filter for IMUs and MARGs. Sensors, 15(8), pp.19302-19330.

