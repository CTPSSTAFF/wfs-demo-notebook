# wfs-demo-notebook

This repository contains a Jupyter notebook demonstrating the use of WFS in two ways:
1. via a 'raw' HTTP request/response pair, using the urllib3 library
2. via a request/response pair, handled by the geopandas package - which greatly simplifies things

The notebook should be run under the Anaconda environment specified in the geopandas_0_9_env.yml file.  
To create this environment in an Anaconda shell:
```
conda env create -f geopandas_0_9_env.yml
```

Aubhor: Ben Krepp
Date: 29 December 2022
