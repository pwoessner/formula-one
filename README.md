# formula-one
Formula 1 Jupyter notebook to make some data analysis.

# Local Setup

- Create the `f1-cache` folder in the root of the repository

## Main Dependencies

- [Jupyter Notebook](https://jupyter.org)
- [FastF1](https://github.com/theOehrly/Fast-F1)

## Conda Environment

[Sharing an environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#sharing-an-environment)

**Udpate the Config**
```sh
conda env export > environment.yml
```

**Create the Conda Environment**
```sh
conda env create -f environment.yml
```

**Update Environment**
```sh
conda env update --prefix ./env --file environment.yml  --prune
```