# Notebooks

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/LibCrowds/notebooks/master)

The [Jupyter notebooks](http://jupyter.org/) contained in this repository
explore the data created via the LibCrowds platform.

## Build setup

``` bash
# install core dependencies
pip install -r requirements.txt

# install Jupyter extensions
jupyter labextension install @jupyterlab/plotly-extension

# run
jupyter lab
```