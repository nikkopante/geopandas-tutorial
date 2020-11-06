## I. Installation

In your directory clone the project.
```console
> git clone git@gitlab.com:grasped/tutorials/geopandas.git
> cd geopandas
```
Install a geopandas enviroment along with its packages.
```console
> conda create --name geo_env python=3.7 notebook pandas numpy geopandas matplotlib descartes
```
Activate the environment.
```console
> conda activate geo_env
```
Activate Jupyter Notebook and go to Geopandas Tutorial.ipynb 
```console
> jupyter notebook
```
When you're done with the tutorial. You can go back to the base environment.
```console
> conda deactivate
```
