# Projet final de Visualisation de Données Biologique

Ce projet a pour but la creation d'un poster se basant sur les données de l'artcle "Microbial Biogeography of Public Restroom Surfaces" de Gilberto E. Flores,  Scott T. Bates, Dan Knights, Christian L. Lauber, Jesse Stombaugh, Rob Knight, Noah Fierer. Le but est de constuire des
visualisations simples & interactives. Pour cela nous avons créé un notebook Jupyter (pyhton 3). 

## Données :
Une table de comptage (abondance) de chaque OTU dans chaque échantillon avec son affiliation taxonomique

## Packages :
- pandas
- re
- plotly
- sklearn
- jupyter_dash
- ipywidgets

## Creation d'un environnement virtuel python
```
python3 -m venv env1
source env1/bin/activate
```

## Installation des packages
```
pip install pandas
pip install regex
pip install plotly
pip install sklean
pip install jupyter-dash
pip install ipywidgets
jupyter nbextension enable --py widgetsnbextension
```
## Interactivité
Le package plotly, ipywidget permettent d'obtenir de  l'interactivité dans les figures.
Le package jupyter-dash permet de créer une "pseudo-application" dans le notebook.

## Figures
L'ensemble des figures créées est disponible dans le dossier ```figures/```de ce dépot.
On notera que les figures intéractives disponible dans le notebook ne sont pas dans ce dossier, car sans l'interactivité celles-ci sont moins lisibles.

## Auteurs
Arnaud DUVERMY et Romuald MARIN
