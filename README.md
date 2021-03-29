# Fast Marching Method

The Fast Marching Method (FMM) is a grid-based numerical solver for the so-called Eikonal equation, a high-frequency approximation of the wave equation building the basis of geometrical optics. The FMM tracks the evolution of a monotonically advancing wavefront utilizing finite differences to compute the travel time for every grid point. Compared to other grid-based travel time  calculations, the FMM has advantages in terms of stability, computational efficiency, and algorithmic simplicity. 

Finite differences try to approximate derivatives (here in terms of the function f(x)

<img src="https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title=" x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />
