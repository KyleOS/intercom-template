# This is a template within Kyso's template library 😉

This is an invidual template for retrieving and plotting Intercom data, forked from the [baseline project](https://github.com/kyso-io/template) that you can use to get started writing a Kyso template.

## Installation

Git clone this repository:

```
https://github.com/kyso-io/kyso-intercom
```

Download and install the [Anaconda Python distribution](https://www.anaconda.com/distribution/).
Then active a conda virtual environment with

```
conda env create -f environment.yml
conda activate dev
```

## Installing libraries

Install any libraries you need with

```
conda install <library>
```

Make sure to run the following command to save the installed libraries into the environment.yml file,
this allows others to run the report easily

```
conda env export --no-builds > environment.yml
```

## Usage

Start programming! Open jupyter with

```
jupyter lab
```

And start working.

## Sharing

Push to Github and import into Kyso.

