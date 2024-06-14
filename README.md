[![Documentation Status](https://readthedocs.org/projects/adopt-net0/badge/?version=latest)](https://adopt-net0.readthedocs.io/en/latest/?badge=latest)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
![Testing](https://github.com/UU-ER/AdOpT-NET0/actions/workflows/00publish.yml/badge.svg?branch=main)

# AdOpT-NET0 - Advanced Optimization Tool for Networks and Energy

This is a python package to simulate and optimize multi energy systems. It can 
model conversion technologies and networks for any carrier and optimize the 
design and operation of a multi energy system.

## Installation
The package can be installed with pip:

```pip install pypsa```

## Usage and documentation
The documentation and minimal examples of how to use the package can be found 
[here](https://adopt-net0.readthedocs.io/en/latest/index.html). We also provide a 
[visualization tool](https://resultvisualization.streamlit.app/) that is compatible 
with AdOpT-NET0.

## Dependencies
The package relies heavily on other python packages. Among others this package uses:

- [pyomo](https://github.com/Pyomo/pyomo) for compiling and constructing the model
- [pvlib](https://github.com/pvlib/pvlib-python) for converting climate data into 
  electricity output
- [tsam](https://github.com/FZJ-IEK3-VSA/tsam) for the aggregation of time series

## Credits
This tool was developed at Utrecht University.
