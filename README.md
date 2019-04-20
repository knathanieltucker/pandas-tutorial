# Getting started with this tutorial

I made this after quite a lot of thought. There are a ton of pandas tutorials out there and the maintainers of pandas themselves have tutorials. But I think these tutorials have one of two flavors:

1. Intro: you barely get into details. 
2. Reference: just the details

I wanted to let people know what are the important and advanced pandas functions that a data scientist uses on a day to day basis. And I could not find it. 

Thus this. 

This tutorial is an opinionated guide to pandas. I'll let you know which functions I think are not worth learning and which are. This is not an intro to pandas. This is pandas for data scientists, and I hope you enjoy.

## Installing Virtualenv

The first step to get running with these tutorials is to install virtualenv. Fortunately there is a [great tutorial](https://docs.python-guide.org/dev/virtualenvs/#lower-level-virtualenv) on hitchhiker's guide to python. Please follow the steps  in the guide.

Once you have installed virtualenv let's make an enviornment with the following command:

`virtualenv -p python3 env`

Notice that we are using python 3. Pandas has announced that they will stop supporting python 2 after 2019. You will then need to activate your env. Again the tutorial is a great resource on showing you how to do this on both windows and mac: 

[Activate your env](https://docs.python-guide.org/dev/virtualenvs/#lower-level-virtualenv)

The next step is that we will need to install all the requirements:

`pip install -r requirements.txt`

Finally the last step is to run an ipython notebook from within the env and then we are ready to go:

`ipython notebook` 

Pandas itself has some good resources on installation that you can find [here](https://pandas.pydata.org/pandas-docs/stable/install.html)


## Order of the Notebooks

The recommended order is:

1. Pandas Intro to Data Structures
2. Indexing and Selecting
3. Group Operations
4. Row-Column Transformations
5. Combining DataFrames
6. Misc Functions


## Exercises

If you are like me you will also find using some of these techniques in exercises to be quite useful as well. And fortunately pandas has some great [exercises listed on their site](https://pandas.pydata.org/pandas-docs/stable/tutorials.html#exercises-for-new-users). If y'all would like and these tutorials/videos get enough support, I'd be happy to video the solutions to those exercises as well. 
