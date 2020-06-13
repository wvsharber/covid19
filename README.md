# COVID-19 DNA Sequence Exploration

This repo explores using DNA sequence data from SARS-CoV-2. 


## Setting up the src code and conda environment

 Use the following steps to complete the installation of the conda environment in `environment.yml` and make code stored in src available as a package.

After cloning the repo, navigate into the repo and run:

```
# create the conda environment
conda env create -f environment.yml

# activate the conda environment
conda activate covid19-env

# make this conda environment available as a kernel in jupyter
python -m ipykernel install --user --name covid19-env --display-name "covid19-env"
```