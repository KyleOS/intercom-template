## This is a template within Kyso's template library 😉

This is an invidual template for retrieving and plotting Intercom data, forked from the [baseline project](https://github.com/kyso-io/template) that you can use to get started writing a Kyso template.


### Installation

Git clone this repository:

```
https://github.com/KyleOS/intercom-template
```

If you haven't done so already, download and install the [Anaconda Python distribution](https://www.anaconda.com/distribution/).
Then active a conda virtual environment with

```
conda env create -f environment.yml
conda activate dev
```


### Installing libraries

Install any additional libraries you need with:

```
conda install <library>
```

Make sure to run the following command to save the installed libraries into the environment.yml file,
this allows others to run the report easily. Note that all libraries required to run this project are already installed, inlcuding plotly and pandas.

```
conda env export --no-builds > environment.yml
```


### Usage

Start programming! Open jupyter with

```
jupyter lab
```

And start working - **take a look at the data preparation report first.** In this notebook you will learn how to create an app on Intercom and fetch your data from the notebook. Once you've successfully run that notebook, open up the actual report.


### Sharing

Once you've made your changes (i.e you've run the project using your own company's data) push your new commits to Github and [import everything into Kyso](https://docs.kyso.io/posting-to-kyso/connect-a-github-repo-to-kyso).
