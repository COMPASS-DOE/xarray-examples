# xarray-examples

Here is a set of examples for using [xarray](https://xarray.pydata.org/en/stable/) and friends.

To get started download [miniconda](https://docs.conda.io/en/latest/miniconda.html), and then use the `conda` command to create an environment called `compass` based on the `compass.yml` file in the repository:

    conda env create -f compass.yml

Now launch an instance of jupyterlab from the command line:

    jupyter lab

A browser window will start up, and you can navigate to the notebooks you want to work with.

You may want to start up a new dask cluster first, by clicking the dask icon to the left, and selecting `+ new`. You will then need to replace the cell that spawns the client by deleting the appropriate cell (usually the second cell, below the imports), and clicking the `<>` button in the newly spawned cluster.  
