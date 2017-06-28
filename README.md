# Current Build Status

Linux, OSX: [![Build Status](https://travis-ci.org/csdms-stack/anuga-recipe.svg?branch=master)](https://travis-ci.org/csdms-stack/anuga-recipe)

# About ANUGA

Home: https://anuga.anu.edu.au/

Package license: GPLv2

Summary: ANUGA (pronounced "AHnooGAH") is open-source software for the simulation of the shallow water equation, in particular it can be used to model tsunamis and floods.

# Installing ANUGA

To install ANUGA from the csdms-stack channel with `conda`:

```bash
$ conda config --add channels conda-forge
$ conda config --add channels csdms-stack
```

Once these channels have been activated:

```bash
$ conda install anuga
```

It is possible to list all of the versions of anuga available on your
platform with:

```bash
$ conda search anuga --channel csdms-stack
```

# Current release info

Version: [![Anaconda-Server Badge](https://anaconda.org/csdms-stack/anuga/badges/version.svg)](https://anaconda.org/csdms-stack/anuga)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/csdms-stack/anuga/badges/downloads.svg)](https://anaconda.org/csdms-stack/anuga)
