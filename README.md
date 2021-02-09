# Installing geopandas on MacOS
1. Create a new conda environment `conda create -n <env_name> python=3.8`
2. Install base python packages `conda install pandas numpy matplotlib seaborn scipy`
3. Install `geopandas` dependencies `pip install fiona shapely pyproj rtree`
4. `pip install geopandas`
5. Run python and test `import geopandas as gp`
