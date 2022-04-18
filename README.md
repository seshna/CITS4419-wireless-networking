# CITS4419-wireless-networking

## Install packages using YML file

The accompanying YML file will install a significant list of packages useful to Jupyter Notebook and SCI-KIT learn. Below is the list of dependencies installed.

```yml
name: jupyter-env
channels:
  - conda-forge
  - defaults
dependencies:
  - python=3.8.5
  - tensorflow=2.4.1
  - tensorflow-datasets
  - scikit-learn
  - scikit-learn-intelex
  - notebook
  - jupyterlab
  - ipywidgets
  - seaborn
  - python-graphviz
  - graphviz
  - openpyxl
```

Run the following command to install the packages
```bash
# could take around 20 to 30 mins
conda env create --file jupyter-env.yml

# clean up the unwanted compressed files
conda clean --all
```

## Activate session

```bash
conda activate jupyter-env
```

## Deactivate session

```bash
conda deactivate
```
