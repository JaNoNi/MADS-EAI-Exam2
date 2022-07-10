# Ethical Artificial Intelligence

## Portfolio examination Part 2 (Due date 07.07.2022)

## Environment Setup

### Shapash

Some interactive visualizations require a specific Jupyter Lab configuration. For details consult this
[link](https://shapash.readthedocs.io/en/latest/installation-instructions/index.html#compatibility-issues).
My steps were:

- Intall Jupyter Lab in the global env (Can also be install in the venv, but my installation is located inside the global environment to reduce number of Jupyter Lab installations)
- Install `widgetsnbextension` in the global env
- Run `jupyter nbextension enable --py widgetsnbextension` in the global env
- Install Nodejs
- Run `jupyter labextension install @jupyter-widgets/jupyterlab-manager` in the global env
- Install `plotly` in the global env
- Run `jupyter labextension install jupyterlab-plotly` in the global env
