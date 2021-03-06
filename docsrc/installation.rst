.. Installation

As of version 1.3, spaghetti supports Python `3.6`_ and `3.7`_ only. Please make sure that you are operating in a Python 3 environment.

Installation
============

Installing with ``conda`` via `spaghetti-feedstock`_ (highly recommended)
-------------------------------------------------------------------------

To install ``spaghetti`` and all its dependencies, we recommend using the `conda`_ manager, specifically with the `conda-forge`_ channel. This can be obtained by installing the `Anaconda Distribution`_ (a free Python distribution for data science), or through `miniconda`_ (minimal distribution only containing Python and the ``conda`` package manager). 

Using `conda`, `spaghetti` can be installed as follows::

  $ conda config --set channel_priority strict
  $ conda install --channel conda-forge spaghetti


Installing with `Python Package Index`_
---------------------------------------
::

  $ pip install spaghetti


*or* download the source distribution (``.tar.gz``) and decompress it to your selected destination. Open a command shell and navigate to the decompressed folder. ::

  $ pip install .

.. role:: rubric

**Warning**

When installing via `pip`, you have to ensure that the required dependencies for `spaghetti` are installed on your operating system. Details on how to install these packages are linked `here`_. Using `conda` (above) avoids having to install the dependencies separately.

Install the most current development version of `spaghetti` by running: ::

  $ pip install git+https://github.com/pysal/spaghetti

Development Version
-------------------

Install the most current development version of spaghetti by running::

  $ pip install git+https://github.com/pysal/spaghetti

You can  also `fork`_ the `pysal/spaghetti`_ repo and create a local clone of your fork. By making changes to your local clone and submitting a pull request to `pysal/spaghetti`_, you can contribute to the spaghetti development.

|

.. _3.6: https://docs.python.org/3.6/
.. _3.7: https://docs.python.org/3.7/
.. _spaghetti-feedstock: https://github.com/conda-forge/spaghetti-feedstock
.. _conda: https://docs.conda.io/en/latest/
.. _conda-forge: https://conda-forge.org
.. _Anaconda Distribution: https://docs.continuum.io/anaconda/
.. _miniconda: https://docs.conda.io/en/latest/miniconda.html
.. _Python Package Index: https://pypi.org/project/spaghetti/
.. _pysal/spaghetti: https://github.com/pysal/spaghetti
.. _fork: https://help.github.com/articles/fork-a-repo/
.. _here: https://github.com/pysal/spaghetti#requirements