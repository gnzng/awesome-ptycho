# Awesome Ptychography 🔬✨

A curated list of ptychography reconstruction software from around the world. 

🚧 Under construction: Please feel free to contribute. 

## 📊 Software Comparison
The list includes only relatively recently updated open-source modules and packages. 

| Name | Author/Organization | Language | GPU Support | Algorithms | GUI |
|------|-------------------|----------|-------------|-----------|-----|
| [4D-STEM](https://github.com/py4dstem/py4DSTEM) | NCEM/LBNL | Python | ✅ CUDA | mPIE |  ✅ |
| [cdtools](https://github.com/cdtools-developers/cdtools) | MIT | Python | ✅ CUDA through torch | ADAM, SGD, LBFGS | ❌ |
| [PtychoShelves](https://www.psi.ch/en/sls/csaxs/software) | PSI | MATLAB | ✅  | PIE, DM, ML |  ❌ |
| [PtyLab](https://github.com/PtyLab) | - | Python, Julia, MATLAB | ✅ | ePIE, mPIE, pcPIE, e3PIE, lsqPIE, aPIE, sPIE, zPIE, pSD, mqNewton | ❌ |
| [PtyPy](https://github.com/ptycho/ptypy) | Diamond Light Source | Python |  ✅ CUDA | PIE, DM, RAAR, SDR |  ❌ |
| [Pty-chi](https://github.com/AdvancedPhotonSource/pty-chi) | UChicago Argonne | Python | ✅ CUDA through torch | ADADELTA, ADAGRAD, ADAM, ADAMAX, ADAMW, ASGD, LBFGS, RADAM, RMSPROP, SGD, SPARSE_ADAM, BH, DM, ePIE, LSQML, PIE, rPIE | ❌ |
| [PyNX](https://pynx.esrf.fr/en/latest/) | ESRF | Python/OpenCL |  ✅ CUDA & OpenCL | PIE, DM, AP | ❌ |
| [ssc-cdi](https://zenodo.org/records/15427455) | Sirius | C++, Python | ✅ CUDA | rPIE, mPIE, AP, RAAR, ML | ❌ |

## 🔤 Column Descriptions

- **Name**: Software package name
- **Author/Organization**: Primary developing organization or author
- **Language**: Main programming language(s)
- **GPU Support**: GPU acceleration framework (CUDA, OpenCL, etc.)
- **Algorithms**: Supported reconstruction algorithms
- **GUI**: Has graphical user interface
- **Repository**: Link to source code repository

## 🧮 Algorithm Abbreviations

### Classical Ptychography Algorithms
- **AP**: Alternating Projections [link](https://www.sciencedirect.com/science/article/pii/S1063520315000913)
- **DM**: Difference Map [link](https://www.science.org/doi/10.1126/science.1158573)
- **ML**: Maximum Likelihood [link](https://iopscience.iop.org/article/10.1088/1367-2630/14/6/063004)
- **LSQML**: Least-squares Maximum Likelihood [link](https://opg.optica.org/oe/fulltext.cfm?uri=oe-26-3-3108&id=381198)
- **RAAR**: Relaxed Averaged Alternating Reflections [link](https://arxiv.org/abs/math/0405208)
- **SDR**: Semi-implicit relaxed Douglas-Rachford algorithm [link](https://opg.optica.org/oe/fulltext.cfm?uri=oe-27-22-31246&id=422295)

### PIE (Ptychographic Iterative Engine) Variants
- **PIE**: Ptychographic Iterative Engine [link](https://www.sciencedirect.com/science/article/pii/S0304399109001284)
- **aPIE**: angle calibration PIE [link](https://opg.optica.org/ol/fulltext.cfm?uri=ol-47-8-1949&id=471191)
- **e3PIE**: Extended PIE with 3 (probe) modes
- **ePIE**: Extended PIE [link](https://www.sciencedirect.com/science/article/pii/S0304399109001284)
- **lsqPIE**: Least-squares PIE
- **mPIE**: Mixed PIE [link](https://opg.optica.org/oe/fulltext.cfm?uri=oe-25-25-30851&id=377327)
- **pcPIE**: Position-corrected PIE [link](https://www.sciencedirect.com/science/article/abs/pii/S0304399112001222)
- **rPIE**: Regularized PIE [link](https://opg.optica.org/optica/fulltext.cfm?uri=optica-4-7-736)
- **sPIE**: Smoothed PIE 
- **zPIE**: autofocusing PIE [link](https://opg.optica.org/ol/fulltext.cfm?uri=ol-45-7-2030&id=429515)

### Specialized Ptychography Optimizers
- **BH**: Bilinear Hessian [link](https://arxiv.org/abs/2502.10755)
- **mqNewton**: Modified quasi-Newton
- **pSD**: projected Steepest Descent

### General Optimization Algorithms
- **ADADELTA**: Adaptive Delta optimizer
- **ADAGRAD**: Adaptive Gradient optimizer
- **ADAM**: Adaptive Moment Estimation optimizer
- **ADAMAX**: ADAM with infinity norm
- **ADAMW**: ADAM with Weight decay
- **ASGD**: Averaged Stochastic Gradient Descent
- **LBFGS**: Limited-memory Broyden-Fletcher-Goldfarb-Shanno optimizer
- **RADAM**: Rectified ADAM
- **RMSPROP**: Root Mean Square Propagation
- **SGD**: Stochastic Gradient Descent
- **SPARSE_ADAM**: Sparse ADAM optimizer

## 📚 Datasets and Resources

### 🗃️ Public Datasets
- [CXIDB](http://cxidb.org/) - Coherent X-ray Imaging Data Bank

### 📖 Learning Resources
- Rodenburg, J.M. orcid.org/0000-0002-1059-8179 and Maiden, A.M. (2019) Ptychography. In: Hawkes, P.W. and Spence, J.C.H., (eds.) Springer Handbook of Microscopy. Springer Handbooks . Springer . ISBN 9783030000684 [link to online version](https://eprints.whiterose.ac.uk/id/eprint/127795/1/Ptychography_Chapter-Rodenburg%2BMaiden_final.pdf)
- Guoan Zheng, A MATLAB tutorial, Fourier Ptychographic Imaging [link to online version](https://iopscience.iop.org/book/mono/978-1-6817-4273-1.pdf)

## 🤝 Contributing

To add or update software information please submit a PR.

## 🏷️ Tags

`ptychography` `coherent-diffraction-imaging` `computational-imaging` `x-ray-imaging` `electron-microscopy` `phase-retrieval` `scientific-computing`

