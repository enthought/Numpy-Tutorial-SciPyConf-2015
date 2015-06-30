==========================================
SciPy2015 tutorial: Introduction to NumPy
==========================================

This repository contains all the material needed by students registered for the
Numpy tutorial of **SciPy 2015** (http://scipy2015.scipy.org/ehome/115969/289057/?&)
on July Mon July 6th 2015.


Content needed
===============
This github repository is all that is needed in terms of tutorial content. To
install it on your machine, you will need a git client.

Step1: Install a git client
---------------------------
* Windows
---------
A good git client for Windows can be downloaded at
http://www.git-scm.com/downloads.
When you install git, you will be asked where to make git available from and
what kind of line ending policy you prefer. If you are not sure, we recommend
that you allow to run git from the command prompt if possible, as it is more
flexible than only running git from the git bash tool that comes with it. Also,
for line ending, the option commonly chosen is
**Checkout Windows-Style, commit unix-style line endings**.


* Mac OSX
---------
If you don't already have git available, a good git client for Windows can be
downloaded at http://www.git-scm.com/downloads.
It installs git in /usr/local/git/bin/, so to have it available from any
terminal, you will want to make sure that location is on your PATH environment
variable.


Linux
-----
The easiest on Linux is to install git from your distro's package manager (yum
for redhat based distros, apt-get for Ubuntu, ...). For example on Ubuntu, it
should be enough to type::

    $ sudo apt-get install git


Step2: Download the material (all platforms)
--------------------------------------------

Once git is available, you will need to clone this repository to get all the
content needed during the tutorial. Its SSH URL is
git@github.com:enthought/Numpy-Tutorial-SciPyConf-2015.git. To do that, you
should be able to start a command prompt/terminal (or the git bash prompt if
you chose to only make git accessible from there) and type::

    $ git clone git@github.com:enthought/Numpy-Tutorial-SciPyConf-2015.git

That will create a new folder named SciPy2015_numpy_tutorial/ with all the
content you will need: a slides I will go through (slides.pdf), and a folder of
exercises.

As you get closer to the day of the tutorial, it is highly recommended to
update this repository, as I will be improving it this week. To update it, open
a command prompt, move **into** the SciPy2015_numpy_tutorial/ folder and run::

    $ git pull


Packages needed
---------------

If you don't already have a working distribution, by far the easiest way to get
everything you need for this tutorial is to download
Enthought Canopy (https://store.enthought.com/, the free version is enough),
or Continuum's Anaconda (http://continuum.io/downloads).

If you do, you will need to make sure that you install or update all needed
packages. To be able to run the examples, demoes and exercises, you must have
the following packages installed:
- numpy 1.8+
- matplotlib 1.4+
- ipython 2.0+ (for running, experimenting and doing exercises)
- nose (only to test your distribution, see below)

To test your installation, please execute the :py:`check_env.py`
script:

    $ python check_env.py
    ....
    ----------------------------------------------------------------------
    Ran 4 tests in 0.162 s

    OK


Questions? Problems?
====================
Questions? Problems? Don't wait, shoot me and the rest of the group an email on
the tutorial mailing list: https://groups.google.com/forum/#!forum/scipy2015-numpy-tutorial
