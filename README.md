# Computational Intro to Robotics: Robot Localization
Authors: [Mo Ampane](https://github.com/Moampane) & Dokyun Kim

## Project Description
The goal of this project was to implement a particle filter for robot localization using ROS2 in Python.

## Methodology
This project can be separated into 5 main steps  
1. Initializing the particle cloud
2. Updating the particle's location using the robot's odometry
3. Updating the particle's weight using the robot's laser scan data
4. Updating the robot's position based on the particle's weights
5. Resampling the particles

#### Initializing the particle cloud (`initialize_particle_cloud()`)
Before running the particle filter, an initial set of particles must be created. In this project, a 2D gaussian distrubution with $\mu = (0,0)$ and $\sigma = (0.05, 0.05)$. A plot of the distribution is shown below.  

![Particle cloud plot](img/particle_cloud.png)  
Fig 1. Visualization of the probability distribution used for initializing the particle cloud

#### Update particles with robot's odomoetry (`update_particles_with_odom()`)
LOREM IPSUM

#### Update particles with robot's laser scan (`update_particles_with_laser()`)
LOREM IPSUM

#### Update robot position with particles' weights (`update_robot_pose()`)
LOREM IPSUM


#### Resample particles (`resample_particles()`)
LOREM IPSUM


## Challenges we faced
LOREM IPSUM


## Project Reflection
LOREM IPSUM


