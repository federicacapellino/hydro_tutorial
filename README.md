# Hydrodynamics for heavy-ion collisions with FluiduM

## Instructions for anaconda navigator
Install anaconda navigator: https://www.anaconda.com/docs/tools/anaconda-navigator/install

## Instructions for Julia
Install julia: Download from: https://julialang.org/downloads

After the installation, open the Julia REPL.

In the Julia REPL, download the backend for Jupyter:

```using Pkg
Pkg.add("IJulia")```

And then register Julia as kernel in Jupyter notebook. 

```using IJulia
notebook()```

This will automatically open Jupyter on the browser. Close the tab after the process is done.

Now add the Fluidum repository and the MonteCarloGlauber repository on the Julia REPL

```import Pkg
Pkg.add(url = "https://github.com/fafafrens/Fluidum.jl")
Pkg.add(url = "https://github.com/AndreasKirchner/MonteCarloGlauber.jl")```

Open Anaconda Navigator, and launch the Jupyter notebook. Click into new on the left, and select Julia as kernel.

Try to use Fluidum and MCGlauber, typing

```using Fluidum
using MonteCarloGlauber```
