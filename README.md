# devtalks-romania
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ChakriCherukuri/devtalks-romania/master?urlpath=Index.ipynb)

Notebooks of my talk at [DevTalks Reimagined](https://www.devtalks.ro/).

## Environment Setup (for running the notebooks)
If you have [miniconda](https://docs.conda.io/en/latest/miniconda.html) distribution, then do the following steps to start the jupyter notebook:

* create conda env called `jupyter-widgets` (one time setup)
```console
$ conda env create -f environment.yml
```
* activate jupyter-widgets conda env
```console
$ conda activate jupyter-widgets
```
* start jupyter notebook server
```console
$ jupyter notebook
```
* Access the index notebook using the following link

`http://localhost:8888/notebooks/Index.ipynb`

## Voila dashboards

Any notebook can be rendered as a voila dashboard by clicking the voila menu button in the notebook.

Live voila dashboards (running on mybinder) can be accessed [here](https://mybinder.org/v2/gh/ChakriCherukuri/devtalks-romania/master?urlpath=voila%2Frender%2FIndex.ipynb).
