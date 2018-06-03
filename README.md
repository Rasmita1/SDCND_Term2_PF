# SDCND_Term2_PF

Here I implemented a 2 dimensional particle filter in C++ to localize an autonomous driving car.

## Introduction
A robot has been kidnapped and transported to a new location! Luckily it has a map of this location, a (noisy) GPS estimate of its initial location, and lots of (noisy) sensor and control data.
The particle filter will be given a map and some initial localization information (analogous to what a GPS would provide). At each time step the filter will get observation and control data.

## Run the code
This project involves the Term 2 Simulator which can be downloaded ([here](https://github.com/udacity/self-driving-car-sim/releases)). Follow the instructions preesent in the classroom section 'uWebSocketIO Starter Guide' for the environment setup.
Once the install for uWebSocketIO is complete, the main program can be built and run by doing the following from the project top directory.
1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./particle_filter
I have used the codes present in the the sdcnd and referred the open forum portals.

Alternatively some scripts have been included to streamline this process, these can be leveraged by executing the following in the top directory of the project:

1. ./clean.sh
2. ./build.sh
3, ./run.sh

Job is to build out the methods in particle_filter.cpp until the simulator output says:

Success! Your particle filter passed!

[![Watch the video](https://github.com/Rasmita1/SDCND_Term2_PF/blob/master/data/Output_Simulator.avi)]
