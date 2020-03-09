# Getting Started

This project utilizes poetry for dependency management. To quickly and reliably get started working on these notebooks, first install poetry using:

```
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python

poetry config virtualenvs.in-project true
```

Clone this repo and navigate to the root directory and then install the dependencies into your jupyter notebook using:

```
poetry install

poetry run ipython kernel install --user --name=open_covid19
```

If the above worked without issue, you should be able to spin up your jupyter notebook using

```
poetry run jupyter notebook
```



