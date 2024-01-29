**Molecule Simulation**

Dr. M. Hamilton created this repository. The provided script simulates the behavior of molecules across a specified number of frames. Originally designed for simulating Stochastic Optical Reconstruction Microscopy (STORM) imaging data, it can also be applied to other systems such as Live Imaging and single-molecule FRET. The molecules are initially assigned a random state: 0 (off), 1 (on), or -1 (bleached). They exhibit blinking behavior, transitioning between these states based on a calculated transition matrix within a Markov Chain.

The script was created using Python 3.9 and to run it, install the anaconda environment provided here (called menv.yml).
