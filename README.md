# Hi, I'm Saleh 👋

I'm a **mechanical engineer and CFD researcher** working on multiphase flow, porous-media transport, numerical methods, and scientific software.

My work sits at the intersection of **physics, numerical modelling, validation, and software**: building models, testing whether they behave correctly, and turning them into workflows that are useful beyond a single simulation.

I work mainly with **C++, Python, OpenFOAM, lattice-Boltzmann methods, HPC, and GPU-enabled computing**, with experience spanning multiphase flow, heat and mass transfer, phase change, turbulence, and image-based porous-media modelling.

## Selected projects

### [PoreWise](https://github.com/SalehMohammadrezaei/PoreWise)
**Image-based permeability modelling on CPU and GPU**

An open-source lattice-Boltzmann workflow that converts segmented 2D and 3D pore geometries into quantitative permeability predictions.

- CPU and GPU execution
- 3D micro-CT rocks, foams, and micromodel geometries
- automated numerical tests and validation
- permeability-tensor workflow
- designed to store pore voxels only, allowing 1024³ sandstone volumes to run on a single workstation GPU
- validated against analytical solutions and published benchmarks


### [Funoos](https://github.com/SalehMohammadrezaei/Funoos)
**An interactive environment for exploring CFD and numerical simulation**

Funoos brings together **28 experiments and 51 presets** across six numerical-method families:

`LBM` · `Navier-Stokes` · `Euler` · `SPH` · `Spectral` · `Reaction-Diffusion`

It covers problems including aerodynamics, wakes, convection, free surfaces, shocks, porous flow, vortices, mixing, and pattern formation.

The application includes configurable inputs, quantitative diagnostics, parameter sweeps, run comparison, reproducible presets, automated checks, and documented model limitations.

I defined the physics, numerical-method direction, validation approach, and project structure. Later implementation stages were developed with AI coding agents under my technical direction, with generated changes reviewed, tested, and numerically verified.

### [totem](https://github.com/SalehMohammadrezaei/totem)
**Does the totem fall? Physics says yes.**

A physics side project inspired by *Inception*, combining **heavy-top rigid-body dynamics**, **MuJoCo contact physics**, and GPU-accelerated rendering to explore what the famous spinning top would actually do under physical dynamics.

I defined the physics and project direction; implementation was predominantly AI-assisted.

## What I care about

- simulations that are **physically credible**, not just numerically converged
- verification, validation, and solver correctness
- scientific software that makes numerical methods easier to explore and use
- HPC and GPU-enabled simulation workflows
- using AI agents to accelerate engineering work while keeping **physics and validation in the loop**

## Reach me

✉️ **salehmrezaee@gmail.com**  
💼 [LinkedIn](https://www.linkedin.com/in/saleh-mohammadrezaei)
