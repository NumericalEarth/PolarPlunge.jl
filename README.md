# PolarPlunge.jl 🧊🌊🏊

> Swim lessons in Scottish waters.

A workshop held 18-19th February 2026 for Edinburgh's [Mac-Migs PhD programme](https://www.mac-migs.ac.uk/) around Julia, GPUs and Earth-System modelling.

Speakers:

- [Simone Silvestri](https://github.com/simone-silvestri) (U Torino / MIT)
- [Milan Klöwer](https://milankl.github.io/) (Oxford)

## Workshop structure

- **[Session 1](https://github.com/NumericalEarth/PolarPlunge.jl/tree/main/01_Intro), Wednesday (18/2) morning:** Introduction to the Julia programming language
- **[Session 2](https://github.com/NumericalEarth/PolarPlunge.jl/tree/main/02_GPU), Wednesday (18/2) afternoon:** Introduction to GPU computing
- **[Session 3](https://github.com/NumericalEarth/PolarPlunge.jl/tree/main/03_NumericalEarth), Thursday (19/2) morning:** Oceananigans and SpeedyWeather showcases
- **Session 4, Thursday (19/2) afternoon:** Open questions plus overflow

You find the materials for each session in the respective folders.

## Jupyter notebooks

How to run the notebooks here locally

1. [Install Julia](https://julialang.org/downloads/), run with `julia` in your terminal
2. [Install IJulia](https://github.com/JuliaLang/IJulia.jl) via `using Pkg; Pkg.add("IJulia")` inside the [Julia REPL](https://docs.julialang.org/en/v1/stdlib/REPL/)
3. Add a Jupyter kernel via `using IJulia; installkernel("Julia")`
4. Launch `jupyter notebook`, choose notebook and pick the "Julia" kernel

## Google Colab

The notebooks here can also be launched without installation on Google Colab. You will need to log in with a Google account.

1. Session: [Google Colab link](https://colab.research.google.com/github/NumericalEarth/PolarPlunge.jl/blob/main/01_Intro/introduction_to_julia.ipynb)
2. Session:
    1. GPU basics: [Google Colab link](https://colab.research.google.com/github/NumericalEarth/PolarPlunge.jl/blob/main/02_GPU/01_gpu_computing.ipynb)
    2. GPU PDEs: [Google Colab link](https://colab.research.google.com/github/NumericalEarth/PolarPlunge.jl/blob/main/02_GPU/02_gpu_navier_stokes.ipynb)
4. Session:
    1. SpeedyWeather: [Google Colab link](https://colab.research.google.com/github/NumericalEarth/PolarPlunge.jl/blob/main/03_NumericalEarth/speedyweather.ipynb)
    2. Oceananigans:

## Acknowledgements

This workshop would not be possible without the tremendous efforts from

- The [Julia language](https://julialang.org/) developers
- The [JuliaGPU](https://juliagpu.org/) community
- The [Oceananigans developers](https://github.com/CliMA/Oceananigans.jl)
- The [SpeedyWeather developers](https://github.com/SpeedyWeather/SpeedyWeather.jl)

## See also

- https://github.com/NumericalEarth/SwimLessons.jl
- https://github.com/SpeedyWeather/NCAS_CMSS_2025
- https://github.com/mauro3/EGU2025-Julia-intro-and-showcase-for-geoscience
