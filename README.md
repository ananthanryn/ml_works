# Few Basic Machine Learning Projects
I recommend to install Miniconda and work on a seperate isolated environment
- Download and install Miniconda from [here](https://docs.conda.io/en/latest/miniconda.html).
- Then create a seperate virtual environment for full Anaconda installation
```bash
conda create -n environmentName anaconda 
```
- Activate the environment
```bash
conda activate environmentName
```
- It is required to install Tensorflow GPU and XGBoost as it is not packaged with the full Anaconda installation
```bash
conda install -c conda-forge tensorflow
conda install -c conda-forge xgboost
conda install -c conda-forge tensorflow-gpu
```
