# cite-ipynb

Notebook files (`.ipynb` files) in the `almond` directory are Jupyter notebooks using the [almond kernel for Scala](https://almond.sh/).

They were originally created by running a  notebook server with an almond kernel using a docker image.  You can run the same notebook server locally with

    docker run -it --rm -p 8888:8888 almondsh/almond:0.8.2

You can then upload an existing `.ipynb` file or create a new one.  From the File menu, you can use `Download as...Notebook`, to save  your running notebook as a `.ipynb` file.


## Options for viewing or running the notebook remotely


### Static renderings

-  This notebook rendered as HTML directly on github: <https://github.com/neelsmith/cite-ipynb/blob/master/almond-CITE-edited.ipynb>
-  From <https://nbviewer.jupyter.org/>, enter the github usename/repo pair `neelsmith/cite-ipynb`


### Ineractive

Can also go to https://mybinder.org/ and enter github repo URL:  scala kernel available after commit of configuration files in `binder` directory.

([binder link](https://mybinder.org/v2/gh/neelsmith/cite-ipynb/7d2013916a2ef200557129af3b6c7e665440af50))


All the CITE goodies via almond work on github.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/neelsmith/cite-ipynb/master)
