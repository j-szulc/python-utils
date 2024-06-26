.. These are examples of badges you might want to add to your README:
   please update the URLs accordingly

    .. image:: https://api.cirrus-ci.com/github/<USER>/pyu.svg?branch=main
        :alt: Built Status
        :target: https://cirrus-ci.com/github/<USER>/pyu
    .. image:: https://readthedocs.org/projects/pyu/badge/?version=latest
        :alt: ReadTheDocs
        :target: https://pyu.readthedocs.io/en/stable/
    .. image:: https://img.shields.io/coveralls/github/<USER>/pyu/main.svg
        :alt: Coveralls
        :target: https://coveralls.io/r/<USER>/pyu
    .. image:: https://img.shields.io/pypi/v/pyu.svg
        :alt: PyPI-Server
        :target: https://pypi.org/project/pyu/
    .. image:: https://img.shields.io/conda/vn/conda-forge/pyu.svg
        :alt: Conda-Forge
        :target: https://anaconda.org/conda-forge/pyu
    .. image:: https://pepy.tech/badge/pyu/month
        :alt: Monthly Downloads
        :target: https://pepy.tech/project/pyu
    .. image:: https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter
        :alt: Twitter
        :target: https://twitter.com/pyu

.. image:: https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold
    :alt: Project generated with PyScaffold
    :target: https://pyscaffold.org/

|

===
pyu
===


    Add a short description here!


A longer description of your project goes here...


.. _pyscaffold-notes:

Installation
=============

.. code-block:: bash

    pip install git+https://github.com/j-szulc/pyu.git

Forced installation
===================

If you're fine with forcing the package installation inside your script, you can use the following code:
.. code-block:: python

    try:
        import pyu
    except ModuleNotFoundError:
        import os
        os.system('pip install git+https://github.com/j-szulc/pyu.git')
        import pyu

Note
====

This project has been set up using PyScaffold 4.5. For details and usage
information on PyScaffold see https://pyscaffold.org/.
