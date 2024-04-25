# Date(last updated) : March/2024

# Run CPU/GPU

# SDSC HPC User Training Notebook Catalog: PythonSeries-master

# Notebook Names
Decision trees.ipynb

# Import Module:
  * tree, load_iris, graphviz
  
# Install Package: 
  * sklearn
  
# Launch galyleo 
  1) Expanse CPU
  export PATH="/cm/shared/apps/sdsc/galyleo:${PATH}"
  galyleo launch --account abc123 --partition shared --cpus 2 --memory 4 --time-limit 00:30:00 --env-modules cpu/0.17.3b,anaconda3/2021.05
  
  2) Expanse GPU
  export PATH="/cm/shared/apps/sdsc/galyleo:${PATH}"
  galyleo launch --account sds173 --partition gpu --gpus 2 --memory 16 --time-limit 00:30:00 --env-modules gpu/0.17.3b,anaconda3/2021.05
  
# Location:
- [data_analysis_pandas.ipynb](./data_analysis_pandas.ipynb)


# Short Descriptions:
