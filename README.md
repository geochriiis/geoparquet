# Geoparquet

Geoprocessing with `.parquet` files ([documentation and how to install](https://pypi.org/project/geoparquet/)). Timing comparisons when reading/writing `.parquet` against `.shp` and `GPKG` can been seen at [jorisvandenbossche/geopandas-parquet-timings.ipynb](https://gist.github.com/jorisvandenbossche/ccd34426d7fe182c929089b6cd4557ac#file-geopandas-parquet-timings-ipynb)

Files<br>|<br>| _ testing.ipynb (tests a simple import of a shapefile and export in `.parquet`) -- useful link

Currently known libraries that can read and write GeoParquet files:

* [GeoPandas](https://geopandas.org/en/stable/docs/user_guide/io.html#apache-parquet-and-feather-file-formats) (Python)
* [sfarrow](https://wcjochem.github.io/sfarrow/index.html) (R)