# Reading GOES NetCDF data on AWS S3 with fsspec-reference-maker

Many thanks to [Rich Signell](mailto:rsignell@usgs.gov) for his help 

__Dependencies:__

Not in pangeo:
* `fsspec-reference-maker`
    * https://github.com/intake/fsspec-reference-maker

Intalled in pangeo
* `fsspec`
    * Dev version needed?
* `xarray`
    * `h5netcdf` engine
* `s3fs`
    * Dev version might also be required
* `json`
* `dask`
* `matplotlib`

__Setup:__
_This will need to be completed_
* Determine best way to get most current versions of `fsspec`, `fsspec-reference-maker`, and `s3fs`. 