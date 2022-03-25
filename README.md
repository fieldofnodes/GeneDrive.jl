# GeneDrive.jl

## Overview 

`GeneDrive.jl` is a Julia package designed for simulating biological dynamics and control. The objectives of the package include: 
* Provide data models that structure inputs to experimental setups and exploit the power of Julia's type system for [multiple dispatch](https://docs.julialang.org/en/v1/manual/methods/). 
* Enable the creation of dynamic models that build on the [`DifferentialEquations.jl`](https://diffeq.sciml.ai/stable/) platform.
* Enable the creation of decision models that employ [`JuMP.jl`](https://jump.dev/JuMP.jl/stable/), the domain-specifc modeling language for mathematical optimization.

## Highlights 
* 
* 
* 

## Installation and usage 

Add the package with:

```julia
julia> ]
(v1.7) pkg> add GeneDrive.jl
```

Begin using the package with: 
```julia
julia> using GeneDrive.jl
```

Version advisory: `GeneDrive.jl` will work with Julia v1.7+.

## Getting started

The [documentation]() features examples as well as more detailed descriptions of package functionalities and applications.  

## License

`GeneDrive.jl` is released under an MIT [License](https://opensource.org/licenses/MIT). This package has been developed in partial fufillment of the requirements for a Master of Science in Electrical Engineering and Computer Science ([EECS](https://eecs.berkeley.edu/research)) at the University of California, Berkeley. 
