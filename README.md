# Getting started with this tutorial

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

## Exercises

If you are like me you will also find using some of these techniques in exercises to be quite useful as well. And fortunately pandas has some great [exercises listed on their site](https://pandas.pydata.org/pandas-docs/stable/tutorials.html#exercises-for-new-users). If y'all would like and these tutorials/videos get enough support, I'd be happy to video the solutions to those exercises as well. 

## TODO

For me:

Pandas nans 
Pandas essential functions
	https://pandas.pydata.org/pandas-docs/stable/computation.html
Pandas and strings 
Indexing and selecting 
Multi/heirarchical index (how you get there and how you get out)
	https://pandas.pydata.org/pandas-docs/stable/reshaping.html
groupby stuff 
Merging and joining 
Performance and categories 
	https://pandas.pydata.org/pandas-docs/stable/categorical.html
	https://pandas.pydata.org/pandas-docs/stable/enhancingperf.html


Future 
Styles - https://pandas.pydata.org/pandas-docs/stable/style.html
IO - read_csv and sql 

Then add to these tutorials with these guys
https://pandas.pydata.org/pandas-docs/stable/10min.html
https://pandas.pydata.org/pandas-docs/stable/cookbook.html
http://tomaugspurger.github.io/modern-4-performance.html
https://pandas.pydata.org/pandas-docs/stable/gotchas.html deep mem usage 

