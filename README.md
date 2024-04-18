# Geant4.jl-tutorial
Materials for the Geant4.jl Tutorial.

Read the rendered Jupyter book: https://peremato.github.io/Geant4.jl-tutorial/index.html

## Follow the tutorial with Binder:
[![Binder](https://binderhub.ssl-hep.org/badge_logo.svg)](https://binderhub.ssl-hep.org/v2/gh/peremato/Geant4.jl-tutorial/HEAD?labpath=tutorial%2Fdocs%2F01-introduction.ipynb)

## Follow the tutorial on a local computer:
To install all what is needed:
```bash
# install Julia
curl -fsSL https://install.julialang.org | sh

# clone this repository
git clone https://github.com/peremato/Geant4.jl-tutorial.git
cd Geant4.jl-tutorial

# instantiate this project and install jupyter
export JULIA_PROJECT=@.
julia -e 'using Pkg;Pkg.instantiate()'
julia -e 'using IJulia; installkernel("Julia")'
julia -e 'using IJulia; jupyterlab(dir="tutorial/docs")'
``` 

- - -
When not taken from other sources (with its own Copyright and License), this material is:

Copyright © 2023 CERN and the authors / contributors.

Licensed under [CC-BY-4.0](./LICENSE).