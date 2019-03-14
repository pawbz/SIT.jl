# Julia Modeling and Inversion Toolbox

## Installation
Install these packages in the given order via Julia's package manager (i.e., after pressing `]` in the REPL):
```julia
add https://github.com/pawbz/Misfits.jl.git
add https://github.com/pawbz/Inversion.jl.git
add https://github.com/pawbz/Interpolation.jl.git
add https://github.com/pawbz/Conv.jl.git
add https://github.com/pawbz/JuMIT.jl.git
```
## Overview
### Seismic

### Poisson
applies to electrical, gravity and magnetic fields

## Tutorial Notebooks

[![](https://img.shields.io/badge/docs-stable-blue.svg)](https://pawbz.github.io/JuMIT.jl/stable)
[![](https://img.shields.io/badge/docs-dev-blue.svg)](https://pawbz.github.io/JuMIT.jl/dev)

### Forward Modeling
* generate seismic data using a 2D finite-difference solver
  * [notebook] (https://github.com/pawbz/JuMIT.jl/tree/master/notebooks/modeling/page1.ipynb)


* saving time snapshots during modelling
  * [notebook] (https://github.com/pawbz/JuMIT.jl/tree/master/notebooks/modeling/page2.ipynb)

## Credits
* Charles Clerget [@chclerget](https://github.com/chclerget) tested most of the methods of this package.
* The Poisson solver (`JuMIT.Poisson`) was developed by Niels Grobbe, after adapting scripts from [Aime Fournier](https://erlweb.mit.edu/users/aimemitedu).
* Finally, thanks of [Earth Resources Laboratory](https://erlweb.mit.edu), MIT. The project was supported by Aime Fournier via research funds from Equinor.


[![Build Status](https://travis-ci.org/pawbz/JuMIT.jl.svg?branch=master)](https://travis-ci.org/pawbz/JuMIT.jl)
[![codecov](https://codecov.io/gh/pawbz/JuMIT.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/pawbz/JuMIT.jl)
