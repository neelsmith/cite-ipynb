# cite-ipynb

The Jupyter notebook `almond-CITE>ipynb` was originally created using Jupyter notebook server with an almond kernel, then from the File menu, using `Download as...Notebook`, to save  an `.ipynb` file.  You can run the same notebook server locally with

    docker run -it --rm -p 8888:8888 almondsh/almond:0.8.2

and upload the `.ipynb` file.

## Options for viewing or running the notebook remotely


### Static renderings

-  This notebook rendered as HTML directly on github: <https://github.com/neelsmith/cite-ipynb/blob/master/almond-CITE-edited.ipynb>
-  From <https://nbviewer.jupyter.org/>, enter the github usename/repo pair `neelsmith/cite-ipynb`


### Ineractive

Can also go to https://mybinder.org/ and enter github repo URL:  scala kernel available after commit of configuration files in `binder` directory.

([binder link](https://mybinder.org/v2/gh/neelsmith/cite-ipynb/7d2013916a2ef200557129af3b6c7e665440af50))


All the CITE goodies via almond work on github.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/neelsmith/cite-ipynb/master)
