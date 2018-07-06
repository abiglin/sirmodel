SIR Model
======

Installation:

* Please use Python 2 not Python 3 
* Recommend using Anaconda distribution of python to install (https://www.anaconda.com/download/#macos)
* To avoid version conflicts, please use conda virtual environment and install sirmodel in it: 

$ conda list
  (Look for python in the list outputed. If not 2.7.n, please run: 
   conda install python=2.7)

$ git clone https://github.com/maggiecdagger/sirmodel.git

$ cd sirmodel

$ conda install scipy numpy sympy Click Pillow matplotlib=2.1.0


To open the interface:

$ python SIR/sir.py


