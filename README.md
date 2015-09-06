# Map basics
Maps tutorial for pyunconf 2015, Hamburg.


How to install requirements
===========================================

The fastest way is to install [Miniconda](http://conda.pydata.org/miniconda.html), that contains [`conda`](http://conda.pydata.org/docs/intro.html) package manager and `Python`.

Then open the comand prompt (will work also in Windows) and put:

```
conda install ipython-notebook pandas matplotlib basemap pip
```
This will set you up for the Basemap part.

Cartopy installation
====================
Cartopy does not play very well with Basemap, so the easiest way to make it work is to create separate `conda` environment:

```
conda create --name cartopy ipython-notebook
```
acrivate it:
```
source activate cartopy
```

Install cartopy from anaconda.org (IOOS channel):
```
conda install -c https://conda.anaconda.org/ioos cartopy
```
