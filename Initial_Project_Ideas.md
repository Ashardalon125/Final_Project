## Initial Project Ideas
-Fine nuclear model
-Stochastic examination of nuclear models
-Classical collision

## Seven Steps to Writing Good Code
Cited from http://www.davidketcheson.info/2015/05/10/rock_solid_code.html for personal reference

1) Use version control
2) Put your code in the cloud, in the open
3) Add a README and a license
4) Write docstrings
5) Write tests
6) Keep track of issues
7) Automate the tests

## Thoughts
Potential wells are often used to define the behaviour of particles on the quantum level. At the quantum level, the potential well yields information about the probabilities of finding a particle in a given region. Describing the behaviour of a particle in a well defined potential well can show behaviour of several tied physics concepts.

## General Outline
### 1) General Area
This project will deal with a quantum potential well and a point particle moving through it. This will show several key behaviours according when it comes to the boundary conditions and assumptions.

### 2) Controlling Equations
The spherical potential well has a set radius and two constant potential values, one for within the radius and one for outside the radius. This contributes to the motion in space by imparting impulse into the point particle.

### 3) Specific Scenario
A point particle is introduced into the potential well with some initial energy and allowed to move about. It will also be specified which direction it acts in in order to take into account non-radial movement.

### 4) Numerical Method

### 5) Boundary Conditions
It will be assumed that some of the standard laws of physics apply, such as a maximum speed and mass density. Further, it's assumed that the edge of the potential well is a perfect, instantaneous transition.

### 6) Desired Results
An algorithm for modelling the motion of the particle is the primary objective. Model detailing the ratios of select energies, and a way of predicting collision parameters are both objectives as well.

### 7) Rough Outline
First, work on modelling the potential well must be done. A basic calculation involving the energy level and the constant force will be performed first, allowing for the framework of the rest of the algorithm. Once the basics have been handled, generalizing it for more scenarios, such as circular movement and true 3D motion will be next.

After the basic has been done, an algorithm capable of comparing momenta will be created. It will be able to produce information about the momenta at different times and locations. Building off this will also be an impact parameter calculator.