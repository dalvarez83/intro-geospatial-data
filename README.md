## **Intro to Geospatial Raster and Vector Data with Python**
This tutorial covers core ideas and skills working with geospatial data. 

The data used in this lesson includes optical satellite images from the Copernicus Sentinel-2 mission and public geographical datasets from the dedicated distribution platform of the Dutch government. These are real-world data sets that entail sufficient complexity to teach many aspects of data analysis and management. 

This follows the open source instructions through the [Carpentries Geospatial course](https://carpentries-incubator.github.io/geospatial-python/index.html)

## Setup local directory
First, `cd` into your working directory.

Create a new directory called `geospatial-python`.
`mkdir geospatial-python`

Within `geospatial-python`, create a directory called data
`mkdir data`

Download the files in the `data` folder. 

Alternatively, `git clone` or `fork` this repository to get the files.

## Setup enviroment

Set up conda mamba environment. 

Run the following commands in Bash or Terminal.

Check which version of conda is installed.
``conda --version``

Then install `mamba`.
``conda install -c conda-forge mamba``

Create Python environment

`mamba env create -n geospatial -f https://raw.githubusercontent.com/carpentries-incubator/geospatial-python/main/files/environment.yaml`

Activate `geospatial` environment.

``conda activate geospatial``

If successful, the text (`base`) in your terminal prompt will now read (`geospatial`) indicating that you are now in the Anaconda virtual environment named geospatial. The command `which python` should confirm that we’re using the Python installation in the geospatial virtual environment. For example:
`which python`

IMPORTANT: If you close the terminal, you will need to reactivate this environment with `conda activate geospatial` to use the Python libraries required.

## Alternative environment setup method

**Environment Install using `environment.yaml`***
Run the following commands in Bash or Terminal.

Change directory into your appropriate level directory.
`cd ../geospatial-python`

`conda env create -f environment.yaml`

Then, activate the `geospatial` virtual environment.
`conda activate geospatial`

## Start Jupyter-Lab
After activating the geospatial conda environment, launch Jupyter-Lab by entering the following command in your terminal.
`jupyter lab`


