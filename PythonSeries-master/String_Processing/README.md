# Date(last updated) : March/2024

# Run CPU/GPU

# SDSC HPC User Training Notebook Catalog: PythonSeries-master

# Notebook Names
  Regression.ipynb

# Import Module:
  * linear_model, mean_squared_error, r2_score, numpy, matplotlib, pandas
  
# Install Package: 
  * sklearn
  * scipy
  
# Launch galyleo 
  1) Expanse CPU
  export PATH="/cm/shared/apps/sdsc/galyleo:${PATH}"
  galyleo launch --account abc123 --partition shared --cpus 2 --memory 4 --time-limit 00:30:00 --env-modules cpu/0.17.3b,anaconda3/2021.05
  
  2) Expanse GPU
  export PATH="/cm/shared/apps/sdsc/galyleo:${PATH}"
  galyleo launch --account sds173 --partition gpu --gpus 2 --memory 16 --time-limit 00:30:00 --env-modules gpu/0.17.3b,anaconda3/2021.05
 
# Location:
- [Regression.ipynb](./Regression.ipynb)

# Short Descriptions:
  Explore regression models using Python's scikit learn (sklearn) package and the built data set.