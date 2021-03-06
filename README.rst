
############
Introduction
############

The latest Documentation was generated on: |today|

.. image:: https://travis-ci.org/pymzml/pymzML.svg?branch=master
    :target: https://travis-ci.org/pymzml/pymzML

.. image:: https://readthedocs.org/projects/pymzml/badge/?version=latest
    :target: http://pymzml.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status


*******************
General information
*******************

Module to parse mzML data in Python based on cElementTree

Copyright 2010-2018 by:

    | M. Kösters,
    | J. Leufken,
    | T. Bald,
    | A. Niehues,
    | S. Schulze,
    | K. Sugimoto,
    | R.P. Zahedi,
    | M. Hippler,
    | S.A. Leidel,
    | C. Fufezan,



===================
Contact information
===================

Please refer to:

    | Dr. Christian Fufezan
    | Group Leader Experimental Bioinformatics
    | Cellzome GmbH
    | R&D Platform Technology & Science
    | GSK
    | Germany 
    | eMail: christian@fufezan.net
    | 
    | http:// <in transition >


*******
Summary
*******

pymzML is an extension to Python that offers
    * a) easy access to mass spectrometry (MS) data that allows the rapid development of tools
    * b) a very fast parser for mzML data, the standard mass spectrometry data format
    * c) a set of functions to compare and/or handle spectra
    * d) random access in compressed files
    * e) interactive data visualization

**************
Implementation
**************

pymzML requires Python3.4+.
The module is freely available on pymzml.github.com or pypi,
published under GPL and requires no additional modules to be installed, but can 
optionally use numpy.


********
Download
********

Get the latest version via github
    | https://github.com/pymzml/pymzML

The complete Documentation can be found as pdf
    | http://pymzml.github.com/dist/pymzml.pdf


********
Citation
********

M Kösters, J Leufken, S Schulze, K Sugimoto, J Klein, R P Zahedi, M Hippler, S A Leidel, C Fufezan; pymzML v2.0: introducing a highly compressed and seekable gzip format, Bioinformatics,
doi: https://doi.org/10.1093/bioinformatics/bty046


************
Installation
************

pymzML requires `Python`_ 3.4 or higher.

.. note::

    Consider to use a Python virtual environment for easy installation and use. 
    Further, usage of python3.4+ is recommended.


Download pymzML using `GitHub`_ **or** the zip file:

* GitHub version: Start by cloning the GitHub repository::

   user@localhost:~$ git clone https://github.com/pymzML/pymzml.git
   user@localhost:~$ cd pymzml
   user@localhost:~$ pip install -r requirements.txt
   user@localhost:~$ python setup.py install

.. _Python:
   https://www.python.org/downloads/

.. _GitHub:
   https://github.com/pymzML/pymzml

If you have troubles installing the dependencies, install numpy first separately,
since pynumpress requires numpy to be installed.

If you use Windows 7 please use the 'SDK7.1 command prompt' for installation
of pymzML to assure correct compiling of the C extensions.



