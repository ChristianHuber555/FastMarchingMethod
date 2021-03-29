# Fast Marching Method Order 1,2,3 with RayTracing for 2D and 3D

The Fast Marching Method (FMM) is a grid-based numerical solver for the so-called Eikonal equation, a high-frequency approximation of the wave equation building the basis of geometrical optics. The FMM tracks the evolution of a monotonically advancing wavefront utilizing finite differences to compute the travel time for every grid point. Compared to other grid-based travel time  calculations, the FMM has advantages in terms of stability, computational efficiency, and algorithmic simplicity. The FMM Sources are [1, 2, 3, 4]

The underlying FMM is implemented in C++ and used in Python! How to use the C++ code in Python will be shown in Section "Installation" and the usage in Python will be shown in Section "Usage".

I'm still in the learning process how to code efficiently, so I would welcome any improvement suggestion. 

## Installation

The Installation of the package is straigthforward, only the following has to be typed into "Anaconda Prompt":

```
cd -directory to FMM_Setup.py-
python FMM_Setup.py
```

The installation was only tested and used on python.

## Usage

This Subsection describes the different methods to use, and how to use them. 

