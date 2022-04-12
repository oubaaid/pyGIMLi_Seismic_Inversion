# pyGIMLi_Seismic_Inversion

## Description

The goal of this project is to highlight the structure of the subsoil, the nature of the superposition of geological layers, as well as to become familiar with this method for seismic refraction interpretation.
A seismic refraction survey is the measurements of induced vibrations at the surface and
the recording of the trajectory of seismic waves through the sub-surface over time, using geophones (sensors).
These waves are reflected at changes in elasticity and/or density at the boundaries of the geological layers; we call these boundaries “interfaces”.
The seismic refraction method is based on measuring the shortest time for an induced seismic pulse to travel from its source location to a series of receivers. From these travel times, the seismic velocities and depths of the various layers can be calculated.
The measured value of the seismic refraction method are the compressional waves (or
P-waves) being the fastest waves are easily recognisable. Then, the results obtained are in the form of a raw seismogram, a representation of the travel time of the refracted waves as a function of the distance between the source and the geophones. From the travel times of the refracted waves on this seismogram, we establish the dromochronics. The straight lines associated with the points allow to determine the velocities of the seismic waves, as well as the thickness of the terrain crossed.

In order to define the structural characteristics of the geological layers, we have worked with PyGimli, which is a Python library created for modeling and interpreting geophysical data. 

As with all seismic interpretation software, Python also offers an (open-source) library that has several tools. PyGIMLi is an open-source library for geophysical modeling and inversion. This library allows us to complete several essential steps of processing and inversion of geophysical data, more precisely in our case, seismic data.
In this project, we will create a subsurface geometry and explore the meshtools of pyGIMLi. Then we will visualize the dromochrones and the apparent velocities of the layers. Finally, we will invert seismic arrival time data.

This project was done following the steps of the tutorial Field data inversion (“Koenigsee”) which shows how to use the Refraction Manager to invert a seismic refraction dataset. Our project represents a conventional refraction seismic dataset of 11 profiles placed so that it constitutes a single long profile of total coverage equal to 336 m. Our setup is based on a planar topography, and a geology consisting of silts deposited on Jurassic age limestones with an eroded upper-limit.

![image](https://user-images.githubusercontent.com/98980894/163068281-36d3bdc2-4fda-4f18-9d88-25ad6c962b2f.png)

The start of the processing is first done manually using a software like PickWin, with a pointing of the dromochronics and the evaluation of the apparent velocities, and finally the results are obtained using the time-of-arrival inversion method.

![image](https://user-images.githubusercontent.com/98980894/163068600-3a007670-1482-411d-99f2-7b71b5855888.png)


