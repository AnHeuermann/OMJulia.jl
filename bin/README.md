# Lexer for OpenModelica outputs

Builds lexer [src/lexer.jl](../src/lexer.jl) using
[Automa.jl](https://github.com/BioJulia/Automa.jl).

## Build

Change into `bin/` directory and run:

```julia
import Pkg;
Pkg.activate(".")
include("generate_lexer.jl")
```

## Additional notes

  - [src/memory.jl](../src/memory.jl) defines Automa.jl types, so Automa.jl
    isn't a dependency for OMJulia.jl.
