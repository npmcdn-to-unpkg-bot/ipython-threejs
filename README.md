# ipython-threejs
IPython/Jupyter widget wrapper for three.js
=======
ipython-threejs
===============================

IPython/Jupyter widget wrapper for three.js

Installation
------------

To install use pip:

    $ pip install ipythreejs
    $ jupyter nbextension enable --py --sys-prefix ipythreejs


For a development installation (requires npm),

    $ git clone https://github.com/abelnation/ipython-threejs.git
    $ cd ipython-threejs
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --user ipythreejs
    $ jupyter nbextension enable --py --user ipythreejs
