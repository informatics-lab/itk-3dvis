# itk-3dvis
Example of how to use itk-jupyter-widgets to render Met Office data in 3D using Jupyter

## Setup
First, clone this repository:

```
git clone https://github.com/informatics-lab/itk-3dvis.git
cd itk-3dvis
```

Create a conda environment with the accompanied `requirements.txt`:

```conda create --name itk-3dvis --file requirements.txt --yes```

If you are using Jupyter Lab then you also need to install the an extension:

```jupyter labextension install @jupyter-widgets/jupyterlab-manager itk-jupyter-widgets```

## Launch notebook
From the cloned git repository:

```jupyter notebook itk-3dvis.ipynb```

Or if you are using Jupyter Lab:

```jupyter lab```
