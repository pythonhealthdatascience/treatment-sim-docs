[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pythonhealthdatascience/stars-ciw-examplar/HEAD)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10051495.svg)](https://doi.org/10.5281/zenodo.10051495)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-360+/)
[![Read the Docs](https://readthedocs.org/projects/pip/badge/?version=latest)](https://pythonhealthdatascience.github.io/stars-simpy-examplar-docs)
[![License: MIT](https://img.shields.io/badge/ORCID-0000--0001--5274--5037-brightgreen)](https://orcid.org/0000-0001-5274-5037)
[![License: MIT](https://img.shields.io/badge/ORCID-0000--0003--2631--4481-brightgreen)](https://orcid.org/0000-0003-2631-4481)
[<img src="https://img.shields.io/static/v1?label=dockerhub&message=images&color=important?style=for-the-badge&logo=docker">](https://hub.docker.com/r/tommonks01/treat_sim)

#   Towards Sharing Tools and Artifacts for Reuable Simulation: example enhanced documentation for a `simpy` model. 

## Overview

The materials and methods in this repository support work towards developing the S.T.A.R.S healthcare framework (**S**haring **T**ools and **A**rtifacts for **R**eusable **S**imulations in healthcare).  The code and written materials here demonstrate the application of S.T.A.R.S' version 1 to sharing a `simpy` discrete-event simuilation model and associated research artifacts.  

* All artifacts in this repository are linked to study researchers via ORCIDs;
* Model code is made available under a MIT license;
* Python dependencies are managed through `conda`;`
* The python code itself can be viewed and executed in Jupyter notebooks via [Binder](https://mybinder.org); 
* The model is documented and explained in a [Jupyter book website](https://pythonhealthdatascience.github.io/stars-simpy-examplar-docs) served up by GitHub pages;
* The materials are deposited and made citatable using Zenodo;
* The models are sharable with other researchers and the NHS without the need to install software.

## Author ORCIDs

[![ORCID: Harper](https://img.shields.io/badge/ORCID-0000--0001--5274--5037-brightgreen)](https://orcid.org/0000-0001-5274-5037)
[![ORCID: Monks](https://img.shields.io/badge/ORCID-0000--0003--2631--4481-brightgreen)](https://orcid.org/0000-0003-2631-4481)

## Citation

> 

```bibtex

```

## Funding

This code is part of independent research supported by the National Institute for Health Research Applied Research Collaboration South West Peninsula. The views expressed in this publication are those of the author(s) and not necessarily those of the National Institute for Health Research or the Department of Health and Social Care.

## Case study model

To Add.

## Online Notebooks via Binder

The python code for the model has been setup to run online in Jupyter notebooks via binder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pythonhealthdatascience/stars-ciw-examplar/HEAD)

> Binder is a free service.  If it has not been used in a while Binder will need to re-containerise the code repository, and push to binderhub. This will take several minutes. After that the online environment will be quick to load.

## Online documentation produced by Jupyter-book

[![Read the Docs](https://readthedocs.org/projects/pip/badge/?version=latest)](https://pythonhealthdatascience.github.io/stars-simpy-examplar-docs)

* The documentation can be access at [https://pythonhealthdatascience.github.io/stars-simpy-examplar-docs](https://pythonhealthdatascience.github.io/stars-simpy-examplar-docs)

## How to create the website locally

Alternatively you may wish to create the website on your local machine.  

### Downloading the code

Either clone the repository using git or click on the green "code" button and select "Download Zip".

```bash
git clone https://github.com/pythonhealthdatascience/stars-simpy-examplar-docs
```

### Installing dependencies

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-360+/)

All dependencies can be found in [`binder/environment.yml`]() and are pulled from conda-forge.  To run the code locally, we recommend install [mini-conda](https://docs.conda.io/en/latest/miniconda.html); navigating your terminal (or cmd prompt) to the directory containing the repo and issuing the following command:

```bash
conda env create -f binder/environment.yml
```

To activate the environment issue the following command:

```bash
conda activate stars_docs`
```

### Building the book

In the directory (folder) containing the code issue the following command via the terminal (or cmd prompt/powershell on windows)

```bash
jb build .
```

> The configutation of the book has been setup to re-run all of the notebooks.  It may take a few minutes to execute on your local machine.

When the build is complete Jupyter book will display a hyper-link to the book that has been built on your machine.  Click on the link (or copy paste into a browser) to run it.