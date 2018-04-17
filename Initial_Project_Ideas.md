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