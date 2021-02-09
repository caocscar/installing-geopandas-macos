# Installing geopandas on MacOS
1. Create a new conda environment `conda create -n <env_name> python=3.8`
2. Activate new environment `conda activate <env_name>`
3. Install base python packages `conda install pandas numpy matplotlib seaborn scipy`
4. Install `geopandas` dependencies `pip install fiona shapely pyproj rtree`
5. `pip install geopandas`
6. Run python and test `import geopandas as gp`

**Note**: You can also just try the last three steps with your existing python installation. You might want to uninstall the packages in step 4 first if they are already installed.
