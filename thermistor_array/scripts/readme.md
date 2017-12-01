### Setup Instructions

Using Anaconda

```
$ conda create -n tmpsf ipykernel requests thredds_crawler xz xarray netcdf4 matplotlib
```

To add the `tmpsf` environment to jupyter as a selectable kernel

```
$ python -m ipykernel install --user --name tmpsf

```