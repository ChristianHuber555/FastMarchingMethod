# Fast Marching Method

The Fast Marching Method (FMM) is a grid-based numerical solver for the so-called Eikonal equation, a high-frequency approximation of the wave equation building the basis of geometrical optics. The FMM tracks the evolution of a monotonically advancing wavefront utilizing finite differences to compute the travel time for every grid point. Compared to other grid-based travel time  calculations, the FMM has advantages in terms of stability, computational efficiency, and algorithmic simplicity. 

Finite differences try to approximate derivatives (here in terms of the function ```f(x)```)


 katex.render("c = \\pm\\sqrt{a^2 + b^2}", element, {
    throwOnError: false
});

