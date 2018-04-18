### Setting up conda, python and jupyter on your local machine.

Download [miniconda](https://conda.io/miniconda.html) and add the conda-forge channel.

```
$ conda config --add channels conda-forge
```

Create an environment, called ooi, for example.

```
$ conda create -n ooi python=3 ipykernel requests xarray netcdf4 pandas numpy matplotlib
```

Activate your new environment and install wget

```
$ source activate ooi
$ pip install wget
```

Add the ooi environment to jupyter as a selectable kernel for your user.

```
$ python -m ipykernel install --user --name ooi

```

Launch the local notebook server

```
$ jupyter notebook
