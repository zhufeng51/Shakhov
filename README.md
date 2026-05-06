# cdugksFoam
An OpenFOAM solver for the Shakhov model using simplified conservation flux scheme for gas kinetics

# Overview
This repository provides an OpenFOAM-based solver implementing the simplified conservation flux scheme for gas kinetic equations, specifically designed for the Shakhov model. It offers a robust, modular, and extensible framework for simulating rarefied gas flows within the OpenFOAM environment.

# Supported OpenFOAM Versions
This solver has been tested and verified on:
* OpenFOAM 2.4.0 (GCC / Intel compilers)
* OpenFOAM 6.0 (GCC compiler)
  
# Compilation & Installation
of240
Enter source directory and compile
cd cdugksFoam/src
./Allwmake
Citation
If you use this solver in your research or projects, please cite the corresponding paper:
```bash
@article{zhu2025simplified,
    title     = {{A simplified conservation flux scheme for gas kinetics based on {OpenFOAM} framework I: Shakhov model}},
    author    = {Zhu, Mengbo and Chen, Jianfeng and Li, Xiaoqiang and Zhuo, Congshan and Liu, Sha and Zhong, Chengwen},
    journal   = {Computer Physics Communications},
    volume    = {312},
    pages     = {109598},
    year      = {2025},
    publisher = {Elsevier}
}
