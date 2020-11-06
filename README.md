## I. Installation

In your directory clone the project.
```
(base) C:/User/Documents/> git clone git@gitlab.com:grasped/tutorials/geopandas.git

(base) C:/User/Documents/> cd geopandas
```
Install a geopandas enviroment along with its packages.
```
(base) C:/User/Documents/geopandas> conda create --name geo_env python=3.7 notebook pandas numpy geopandas matplotlib descartes
```
Activate the environment.
```
(base) C:/User/Documents/geopandas> conda activate geo_env
```
Activate Jupyter Notebook and go to Geopandas Tutorial.ipynb 
```
(geo_env) C:/User/Documents/geopandas> jupyter notebook
```
When you're done with the tutorial. You can go back to the base environment.
```
(geo_env) C:/User/Documents/geopandas> conda deactivate
```
