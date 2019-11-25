# `cite-ipynb`


This repository hosts material teaching you:

1. just enough Scala to write scripts using Jupyter notebooks (`.ipynb` notebook files in the `jes` directory)
2. how to use CITE libraries in Jupyter notebooks (`.ipynb` notebook files in the `almond` directory, using the [almond kernel for Scala](https://almond.sh/))


How to use this material:  <https://neelsmith.github.io/cite-ipynb/>



## TL;DR

You can run a notebook server locally with

    docker run -it --rm -p 8888:8888 almondsh/almond:0.8.2

and then upload an existing `.ipynb` file from the `jes` or `almond` directory.

The files in the `binder` directory define a configuration to use thse notebooks notebooks with `nbviewer` and `mybinder`:


-  notebooks rendered as HTML directly on github: <https://github.com/neelsmith/cite-ipynb/blob/master/almond>
-  formatted display of notebooks on nbviewer: <https://nbviewer.jupyter.org/github/neelsmith/cite-ipynb/tree/master/>
-  work with notebooks interactively  on mybinder.org: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/neelsmith/cite-ipynb/master)
