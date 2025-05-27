# Churn prediction model of an advertisement portal using anonymized data.

Python version = 3.11.0 
- pyenv to install the python version
- uv to manage virtualenv and dependencies

First steps:
1. Clone the repo
2. `pyenv install 3.11.0` & `pyenv local 3.11.0`. `pyenv versions` output should be 3.11.0 with an asterisk.
3. Start the virtual environment `uv sync` and `source .venv/bin/activate` will create the environment with the dependencies defined at pyproject.toml.
4. We can add new dependencies with `uv add <package>`
5. To use this environment as the kernel in notebooks `python -m ipykernel install --user --name=churn-prediction-zrive`


