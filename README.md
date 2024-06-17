# OpenMod4Africa Workshop Madrid 2024: the pyam package

[![License:
MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![python](https://img.shields.io/badge/python-≥3.10,<3.13-blue?logo=python&logoColor=white)](https://github.com/IAMconsortium/pyam)
[![Code style:
black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

Copyright 2022 (c) Daniel Huppmann; this repository is released under the [MIT
License](LICENSE).

This repository is based on the work done by Daniel Huppmann for *ENGAGE Capacity
Building Workshop: the pyam package*
<https://github.com/danielhuppmann/ENGAGE-pyam-tutorial/>.

## Overview

This repository holds a [Jupyter notebook](tutorial-notebook.ipynb) for a live-demo of
the **pyam** package given as part of the OpenMod4Africa workshop on June 18, 2024.

The Jupyter notebook is based on the *ENGAGE Capacity Building Workshop: the pyam
package* (<https://github.com/danielhuppmann/ENGAGE-pyam-tutorial/>) which itself is
based on the advanced assignment of the [Modelling
Lab](https://github.com/danielhuppmann/climate-risks-academy-2021), which was part of
the *Climate Risks Academy 2021* organized by the European University Institute (EUI)
Florence School of Banking and Finance in cooperation with Oliver Wyman.

The scenario data used in this tutorial notebook is taken from the [OpenMod4Africa
Internal Scenario Explorer](https://data.ece.iiasa.ac.at/openmod4africa-internal).

## The pyam package

<img src="./_static/pyam-logo.png" width="133" height="100" align="right" alt="pyam logo" />

This exercise uses the Python package **pyam**, an open-source community toolbox for
analysis & visualization of scenario data. The package was developed to facilitate
working with timeseries scenario data conforming to the format developed by the
[Integrated Assessment Modeling Consortium (IAMC)](https://www.iamconsortium.org). The
package is used in ongoing assessments by the IPCC and in many model comparison projects
at the global and national level, including several Horizon 2020 projects.

[Read the docs](https://pyam-iamc.readthedocs.io) for more information!

## Getting started

To run the notebooks on your machine, please install Python version 3.10 or higher. To
install the required packages and dependencies, download or git-clone this repository
and run the following command in the root folder:

```console
pip install -r requirements.txt
```

Then, you can start a Jupyter notebook using

```console
jupyter notebook
```
