# Quantum Optomechanics Tools

> A list of toolboxes and platforms for simulations and analysis of quantum optomechanical systems

## [QuTiP - Quantum Toolbox in Python](https://qutip.org/)

[![Release](https://img.shields.io/github/v/release/qutip/qutip?logo=python&color=3776AB&style=flat-square)](https://github.com/qutip/qutip)
[![Updated](https://img.shields.io/github/last-commit/qutip/qutip?label=updated&color=lightgrey&style=flat-square)](https://github.com/qutip/qutip)
[![Stars](https://img.shields.io/github/stars/qutip/qutip?color=lightgrey&style=flat-square)](https://github.com/qutip/qutip)

J. R. Johansson, P. D. Nation and F. Nori, *QuTiP 2: A Python Framework for the Dynamics of Open Quantum Systems*, [Comput. Phys. Commun. **184**, 1234](https://www.doi.org/10.1016/j.cpc.2012.11.019) (2013)

* Open-source Python library to simulate dynamics of open quantum systems
* Built on Numpy, Scipy and Cython packages with graphical outputs by Matplotlib
* User-friendly and efficient numerical simulations of a wide variety of Hamiltonians
* Suitable for quantum optics, trapped ions, superconding circuits and quantum nanomechanical resonators
* Used by research universities, government-funded labs and major corporations

## [Strawberry Fields](https://strawberryfields.ai/)

[![Release](https://img.shields.io/github/v/release/XanaduAI/strawberryfields?logo=python&color=3776AB&style=flat-square)](https://github.com/XanaduAI/strawberryfields)
[![Updated](https://img.shields.io/github/last-commit/XanaduAI/strawberryfields?label=updated&color=lightgrey&style=flat-square)](https://github.com/XanaduAI/strawberryfields)
[![Stars](https://img.shields.io/github/stars/XanaduAI/strawberryfields?color=lightgrey&style=flat-square)](https://github.com/XanaduAI/strawberryfields)

N. Killoran, J. Izzac, N. Quesada, V. Bergholm, M. Amy and C. Weedbrook, *Strawberry Fields: A Software Platform for Photonic Quantum Computing*, [Quantum **3**, 129](https://www.doi.org/10.22331/q-2019-03-11-129) (2019)

* Open-source full-stack Python library for designing, simulating and optimizing continuous-variable quantum optical circuits
* High-level functions for solving practical problems including optimization, machine learning and chemistry
* Includes several world-class simulators to compile and simulate photonic algorithms
* TensorFlow backend to train and optimize quantum programs
* Interactive web-application with drag-and-drop interface

## [QuantumOptics.jl](https://qojulia.org/)

[![Release](https://img.shields.io/github/v/release/qojulia/QuantumOptics.jl?logo=julia&color=9558B2&style=flat-square)](https://github.com/qojulia/QuantumOptics.jl)
[![Updated](https://img.shields.io/github/last-commit/qojulia/QuantumOptics.jl?label=updated&color=lightgrey&style=flat-square)](https://github.com/qojulia/QuantumOptics.jl)
[![Stars](https://img.shields.io/github/stars/qojulia/QuantumOptics.jl?color=lightgrey&style=flat-square)](https://github.com/qojulia/QuantumOptics.jl)

* Open-source numerical framework in Julia to simulate open quantum systems
* Optimized processor usage and memory consumption
* Pre-defined systems and interactions for ease in numerics
* Tested and benchmarked against [QuTiP](#qutip---quantum-toolbox-in-python) and [Quantum Optics Toolbox](#quantum-optics-toolbox)
* Supports author-maintained add-ons.

## [HOQST - Hamiltonian Open Quantum Systems Toolkit](https://uscqserver.github.io/OpenQuantumTools.jl/dev/)

[![Release](https://img.shields.io/github/v/release/USCqserver/OpenQuantumTools.jl?logo=julia&color=9558B2&style=flat-square)](https://github.com/USCqserver/OpenQuantumTools.jl)
[![Updated](https://img.shields.io/github/last-commit/USCqserver/OpenQuantumTools.jl?label=updated&color=lightgrey&style=flat-square)](https://github.com/USCqserver/OpenQuantumTools.jl)
[![Stars](https://img.shields.io/github/stars/USCqserver/OpenQuantumTools.jl?color=lightgrey&style=flat-square)](https://github.com/USCqserver/OpenQuantumTools.jl)

* Open-source Julia package for simulating the open quantum system dynamics codenamed `OpenQuantumTools`
* Includes master equation solvers featuring multiple methods
* Supports solvers for various time-depending coupling interactions
* Provides several plotting functionality by recipes
* Under heavy development

## [Quantum Optics Toolbox](https://qo.phy.auckland.ac.nz/toolbox/)

[![GitHub](https://img.shields.io/badge/release-v0.15-red?style=flat-square)](https://github.com/jevonlongdell/qotoolbox)
[![Updated](https://img.shields.io/github/last-commit/jevonlongdell/qotoolbox?label=updated&color=lightgrey&style=flat-square)](https://github.com/jevonlongdell/qotoolbox)
[![Stars](https://img.shields.io/github/stars/jevonlongdell/qotoolbox?color=lightgrey&style=flat-square)](https://github.com/jevonlongdell/qotoolbox)

* Propreity package developed for MATLAB
* Simple way to set up equations of motion using Hamiltonians
* Quantum objects are mapped to class instances
* Includes a variety of solution algorithms
* Discontinued since 2002

## [The Quantum Optomechanics Toolbox](https://github.com/sampreet/qom/)

[![Release](https://img.shields.io/github/v/release/sampreet/qom?logo=python&color=3776AB&style=flat-square)](https://github.com/sampreet/qom/)
[![Updated](https://img.shields.io/github/last-commit/sampreet/qom?label=updated&color=lightgrey&style=flat-square)](https://github.com/sampreet/qom/)
[![Stars](https://img.shields.io/github/stars/sampreet/qom?color=lightgrey&style=flat-square)](https://github.com/sampreet/qom/)

* Open-source package for computational quantum optomechanics codenamed `qom`
* Automatically managed loops and parameter validation modules
* Solver modules to calculate classical and quantum signatures
* Inheritable optomechanical systems supporting callable properties
* Configurable visualizations without the need for explicit plotting