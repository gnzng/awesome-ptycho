# Awesome Ptychography 🔬✨

A curated list of ptychography reconstruction software from around the world. 

🚧 Under construction: Please feel free to contribute. 

## 📊 Software Comparison

| Name | Author/Organization | Language | GPU Support | Algorithms | GUI | Repository |
|------|-------------------|----------|-------------|-----------|-----|--------------|
| 4D-STEM | NCEM/LBNL | Python | ✅ CUDA | mPIE |  ✅ | [GitHub](https://github.com/py4dstem/py4DSTEM) |
| cdtools | MIT | Python | ✅ CUDA through torch | ADAM, SGD, LBFGS | ❌ | [GitHub](https://github.com/cdtools-developers/cdtools) |
| PtychoShelves | PSI | Matlab | ✅  | PIE, DM, ML |  ❌ | [PSI website](https://www.psi.ch/en/sls/csaxs/software) | 
| PtyLab | - | Python, Julia, Matlab | ✅ | ePIE, mPIE, pcPIE, e3PIE, lsqPIE, aPIE, sPIE, zPIE, pSD, mqNewton | ❌ | [GitHub](https://github.com/PtyLab) | 
| PtyPy | Diamond Light Source | Python |  ✅ CUDA | PIE, DM, RAAR, SDR |  ❌ | [GitHub](https://github.com/ptycho/ptypy) | 
| Pty-chi | UChicago Argonne | Python | ✅ CUDA through torch | ADADELTA, ADAGRAD, ADAM, ADAMAX, ADAMW, ASGD, LBFGS, RADAM, RMSPROP, SGD, SPARSE_ADAM, BH, DM, ePIE, LSQML, PIE, rPIE | ❌ | [GitHub](https://github.com/AdvancedPhotonSource/pty-chi) | 
| PyNX | ESRF | Python/OpenCL |  ✅ CUDA&OpenCL | PIE, DM, AP | ❌ | [ESRF](https://pynx.esrf.fr/en/latest/) | 
| ssc-cdi | Sirius | C++, Python | ✅ CUDA | rPIE, mPIE, AP, RAAR, ML | ❌ | [zenodo](https://zenodo.org/records/15427455) | 

## 🔤 Column Descriptions

- **Name**: Software package name
- **Author/Organization**: Primary developing organization or author
- **Language**: Main programming language(s)
- **GPU Support**: GPU acceleration framework (CUDA, OpenCL, etc.)
- **Algorithms**: Supported reconstruction algorithms
- **GUI**: Has graphical user interface
- **Repository**: Link to source code repository

## 🧮 Algorithm Abbreviations

- **ADADELTA**: Adaptive Delta optimizer
- **ADAGRAD**: Adaptive Gradient optimizer
- **ADAM**: Adaptive Moment Estimation optimizer
- **ADAMAX**: ADAM with infinity norm
- **ADAMW**: ADAM with Weight decay
- **AP**: Alternating Projections
- **aPIE**: Annealed PIE
- **ASGD**: Averaged Stochastic Gradient Descent
- **BH**: Bilinear Hessian
- **DM**: Difference Map [link](https://www.science.org/doi/10.1126/science.1158573)
- **e3PIE**: Extended PIE with 3 modes
- **ePIE**: Extended PIE [link](https://www.sciencedirect.com/science/article/pii/S0304399109001284)
- **LBFGS**: Limited-memory Broyden-Fletcher-Goldfarb-Shanno optimizer
- **lsqPIE**: Least-squares PIE
- **LSQML**: Least-squares Maximum Likelihood
- **ML**: Maximum Likelihood
- **mPIE**: Mixed PIE
- **mqNewton**: Modified quasi-Newton
- **pcPIE**: Position-corrected PIE
- **PIE**: Ptychographic Iterative Engine [link](https://www.sciencedirect.com/science/article/pii/S0304399109001284)
- **pSD**: projected Steepest Descent
- **RAAR**: Relaxed Averaged Alternating Reflections
- **RADAM**: Rectified ADAM
- **RMSPROP**: Root Mean Square Propagation
- **rPIE**: Regularized PIE
- **SDR**: Semi-implicit relaxed Douglas-Rachford algorithm [link](https://opg.optica.org/oe/fulltext.cfm?uri=oe-27-22-31246&id=422295)
- **SGD**: Stochastic Gradient Descent
- **SPARSE_ADAM**: Sparse ADAM optimizer
- **sPIE**: Smoothed PIE 
- **zPIE**: autofocusing PIE [link](https://opg.optica.org/ol/fulltext.cfm?uri=ol-45-7-2030&id=429515)


## 📚 Datasets and Resources

### 🗃️ Public Datasets
- [CXIDB](http://cxidb.org/) - Coherent X-ray Imaging Data Bank

### 📖 Learning Resources


## 🤝 Contributing

To add or update software information 📤 Submit a pull request

## 🏷️ Tags

`ptychography` `coherent-diffraction-imaging` `computational-imaging` `x-ray-imaging` `electron-microscopy` `phase-retrieval` `scientific-computing`



*⭐ Star this repository to keep track of updates!*
