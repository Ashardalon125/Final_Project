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
Modelling the classical collision starts by programming the most default case of a small particle moving near a nuclei. Unlike classical collisions, this can have forces based on proximity, not just contact. Calculating this will be the first component. This will involve the charges of both objects.

Nuclei impacts can also have a certain amount of "stickiness" to them, so programming how much of the nuclei is a binding site will be important as well. It can also be ionized. This means that the nuclei itself will have to have some kind of data structure telling the program how much of it acts a certain way.

Extrapolating this out, most calculations use large amounts of nuclei, in a thin formation and a stream of projectiles. Figuring out how to move it over to many bodies would be the next part of the code.

This will mainly use the formulae proposed in Taylor's Classical Mechanics Textbook, along with various bits of information from the Thomson's experiment determining the existence and nature of electrons.

## General Outline
### 1) General Area
This project will deal with classical collisions using the equations defined in Taylor's Classical Mechanics textbook. This will include impacts, capturing, ionization, and potentially, fission. These use the averaged versions of the equations, as it is a matter of streams of particles impacting sheets of materials.

### 2) Relevant Controlling Equations
The first equation that defines the relationship is:
$$N_{Sc} = N_{Inc}*n_{Tar}*\sigma$$
This defines the number of particles scattered in total. However, sigma here is actually the total sigma of the areas, which is used instead of the impact parameter, given the particles are both too small and too numerous to properly measure it directly. It is the sum of all the sigmas, measuring different cross-sectional areas related to certain outcomes of impacts as mentioned in the general outline.
$$\sigma_{tot} = \sigma_{scat} + \sigma_{cap} + \sigma_{ion} + \sigma_{fis}
It is also worth noting that in the case of $\sigma_{ion}$ only applies to particles that are of a high enough frequency to ionize the target atoms; otherwise it is equal to zero, meaning that a check that determines this will help streamline the program.