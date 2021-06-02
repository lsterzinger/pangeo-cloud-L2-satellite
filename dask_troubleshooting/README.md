# Troubleshooting Dask Issues w/ GOES S3 Data

These notebooks highlight a problem I've run into when trying to open GOES-16 netCDF files over S3 with `xr.open_mfdataset()`.

If no dask client is created, the files can be opened with xarray in a matter of minutes.
    * [Notebook without dask](./goes-16-no-dask.ipynb)
    
However, all else being equal, if a dask distributed client is created before opening the files, the `open_mfdataset()` call hangs, seemingly forever.
    * [Notebook with dask](./goes-16-with-dask.ipynb)