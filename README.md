# Getting started with this tutorial

## Installing with Miniconda

The first step to get running with these tutorials is to install conda.

Conda is the package manager that the Anaconda distribution is built upon. It is a package manager that is both cross-platform and language agnostic (it can play a similar role to a pip and virtualenv combination).

Miniconda allows you to create a minimal self contained Python installation, and then use the Conda command to install additional packages.

First you will need Conda to be installed and downloading and running the Miniconda will do this for you. The installer can be found [here](http://conda.pydata.org/miniconda.html).

The next step is to create a new conda environment. A conda environment is like a virtualenv that allows you to specify a specific version of Python and set of libraries. I've already saved all of the dependencies that you will need to run the tutorial. All you need to do is run the following commands from a terminal window:

`conda create -n pandas-env --file requirements.txt python=3.6`

This will create a minimal environment with everything installed in it. To put your self inside this environment run:

`source activate pandas-env`

On Windows the command is:

`activate pandas-env` 

Finally the last step is to run an ipython notebook from within the env and then we are ready to go:

`ipython notebook` 

Pandas itself has some good resources on installation that you can find [here](https://pandas.pydata.org/pandas-docs/stable/install.html)

## Exercises

If you are like me you will also find using some of these techniques in exercises to be quite useful as well. And fortunately pandas has some great [exercises listed on their site](https://pandas.pydata.org/pandas-docs/stable/tutorials.html#exercises-for-new-users). If y'all would like and these tutorials/videos get enough support, I'd be happy to video the solutions to those exercises as well. 

## TODO

For me:

Start with https://pandas.pydata.org/pandas-docs/stable/dsintro.html
Pull out the parts you use and the parts you like

continue down the list on the left hand side building tutorials
https://pandas.pydata.org/pandas-docs/stable/index.html

Then add to these tutorials with these guys
https://pandas.pydata.org/pandas-docs/stable/10min.html
https://pandas.pydata.org/pandas-docs/stable/cookbook.html
http://tomaugspurger.github.io/modern-4-performance.html


