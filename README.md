# Singular

[![Build Status](https://travis-ci.com/oscar-system/Singular.jl.svg?branch=master)](https://travis-ci.com/oscar-system/Singular.jl)
[![Coverage Status](https://coveralls.io/repos/github/oscar-system/Singular.jl/badge.svg)](https://coveralls.io/github/oscar-system/Singular.jl)
[![codecov.io](https://codecov.io/github/oscar-system/Singular.jl/coverage.svg?branch=master)](https://codecov.io/gh/oscar-system/Singular.jl)

Julia package for using the [Singular](https://www.singular.uni-kl.de/) library for commutative and
non-commutative algebra, algebraic geometry, and singularity theory.

To build Singular.jl, start julia and then type:

```julia
julia> using Pkg
julia> Pkg.clone("https://github.com/oscar-system/Singular.jl")
julia> Pkg.build("Singular")
```
To use Singular.jl, start julia and then type:

```julia
julia> using Singular
```
