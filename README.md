# vscode-python-template

A Template for Python Programming in VSCode

## Setup

We recommend [miniforge](https://conda-forge.org/download/) to set up your python environment. \
Then [uv](https://docs.astral.sh/uv/) can be used to install the project dependencies:

```bash
conda create -n $YOUR_ENV_NAME python=3.12
conda activate $YOUR_ENV_NAME
uv pip install -r requirements.txt
pre-commit install
```
