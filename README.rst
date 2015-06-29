pandas_tutorial
===============

This repository contains all the material needed by students registered to the
Numpy tutorial of `SciPy 2015<http://scipy2015.scipy.org/ehome/115969/289057/?&>`_
on July Mon July 6th 2015.


Packages needed
---------------

If you don't already have a working distribution, by far the easiest way to get
everything you need for this turtorial is to download
`Enthought Canopy<https://store.enthought.com/>`_ (the free version is enough),
or `Anaconda<http://continuum.io/downloads>`_.

To be able to run the examples, demoes and exercises, you must have the
following packages installed:
- numpy 1.8+
- matplotlib 1.4+
- ipython 2.0+ (for running, experimenting and doing exercises)
- nose (only to test your distribution, see below)

To test your installation, please execute the :py:`test_python_install.py`
script using the `nosetests` executable:

    $ nosetests test_python_install.py
    ....
    ----------------------------------------------------------------------
    Ran ** tests in ** s

    OK
