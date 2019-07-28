Jupyter Lab Setup
=================

Install nodejs to have access to jupyter lab extensions configuration : https://nodejs.org/en/download/package-manager/

Matplotlib widget:

```
pip install ipympl
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install jupyter-matplotlib
```

Git plugin:
```
jupyter labextension install @jupyterlab/git
pip install --upgrade jupyterlab-git
jupyter serverextension enable --py jupyterlab_git<Paste>
```

Diagrams:
```
jupyter labextension install jupyterlab-drawio
```

Diagrams from markdown in Jupyter notebook: https://github.com/jupyter/notebook/issues/2300


