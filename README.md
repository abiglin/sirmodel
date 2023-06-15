SIR Model
======

* This code uses Python 2, not Python 3.
* We recommend using the Anaconda distribution of Python. The Windows, Mac and Linux versions can be accessed at https://www.anaconda.com/download#downloads.
* To avoid version conflicts, use the conda virtual environment and install sirmodel into it. 

INSTRUCTIONS: Copy each line of code into the Anaconda command prompt app one at a time. The text in brackets is explanatory; it is NOT part of the code. Copy only the lines under "Installation" or "Using the applet" that are not enclosed in brackets.

=== Installation (for instructors/administrators) ===

conda install -c anaconda git
[This loads the git package into Anaconda. It may be that git is already installed. In that case, disregard this line of code.]

conda create --name py2 python=2.7
[This ensures that you are using Python 2 instead of Python 3.]

activate py2
[This "turns on" Python 2.]

conda install scipy numpy sympy Click Pillow matplotlib=2.1.0
[This installs the packages and functions that are used in the applet.]

git clone https://github.com/abiglin/sirmodel.git
[This imports the sirmodel folders from GitHub.]


=== Using the applet (for students) ===

activate py2
[Python 2, the version of Python used in this activity, should already be installed on your device. If it is not, ask your team leader for help.]

cd sirmodel
[This code orients your into the sirmodel subfolder of the GitHub respository. The repository should already be "cloned" onto your device. If it is not (i.e., you receive an error message that the directory cannnot be found), ask your team leader for help.]

cd SIR
[This code orients you into the SIR sub-subfolder. This is where the main applet code is located.]

python sir2.py
[This launches the applet.]


