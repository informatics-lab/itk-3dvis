[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/informatics-lab/itk-3dvis/master?filepath=itk-3dvis.ipynb)

# itk-3dvis
Example of how to use [itk-jupyter-widgets](https://github.com/InsightSoftwareConsortium/itk-jupyter-widgets) to render Met Office data in 3D using Jupyter

## Setup
First, clone this repository:

```
git clone https://github.com/informatics-lab/itk-3dvis.git
cd itk-3dvis
```

Create a conda environment with the accompanied `requirements.txt`:

```conda create --name itk-3dvis --file environment.yml --yes```

If you are using Jupyter Lab then you also need to install the an extension:

```jupyter labextension install @jupyter-widgets/jupyterlab-manager itk-jupyter-widgets```

## Launch notebook
This notebook can be run from the [Pangeo Binder](https://binder.pangeo.io/) service at:

https://binder.pangeo.io/v2/gh/informatics-lab/itk-3dvis/nbserverproxy?filepath=itk-3dvis.ipynb

If you wish to run it locally, first clone this git repository (see above) then:

```jupyter notebook itk-3dvis.ipynb```

Or if you are using Jupyter Lab:

```jupyter lab```
