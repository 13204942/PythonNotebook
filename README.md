# PythonNotebook
Notebook for course Python For Data Science With Real Exercises 

## Install Python 3.3 or greater
First of all check that you don't already have Python installed by entering python in a command line window. If you see a response from a Python interpreter it will include a version number in its initial display. Generally any recent version will do, as Python makes every attempt to maintain backwards compatibility.

If you need to install Python, you may as well download the most recent stable version. This is the one with the highest number that isn't marked as an alpha or beta release. Please see the [Python downloads page](https://www.python.org/downloads/) for the most up to date versions of Python 3. They are available via the yellow download buttons on that page.

## Installing Jupyter using Anaconda and conda
Recommend installing Anaconda. Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.

Use the Anaconda distribution to install Python and Jupyter. 

* Download Anaconda. And download Anaconda’s latest Python 3 version (currently Python 3.5).
* Install the version of Anaconda which you downloaded, following the instructions on the download page.
* To run the notebook:
~~~
jupyter notebook
~~~

## Alternative for experienced Python users: Installing Jupyter with pip
Also, you may wish to install Jupyter using Python’s package manager, pip, instead of Anaconda.
First, ensure that you have the latest pip; older versions may have trouble with some dependencies:
~~~
pip3 install --upgrade pip
~~~
Then install the Jupyter Notebook using:
pip3 install jupyter
(Use pip if using legacy Python 2.)
