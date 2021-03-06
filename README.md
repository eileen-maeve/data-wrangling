# Data Wrangling

Presentation for [PyLadies MTL](http://www.meetup.com/pyladiesmtl/).

## Setup

We run [Python 3.5.2](https://www.python.org/downloads/release/python-352/).
We use [virtual environments](https://virtualenv.pypa.io/) as a general good practice.
Let us create a virtual environment (virtualenv) for this project:

    $ mkdir -p ~/.virtualenv
    $ python3 -m venv ~/.virtualenv/data-wrangling

Activate the virtualenv:

    $ source ~/.virtualenv/data-wrangling/bin/activate

When you are done working on this project, you can `$ deactivate`.
You may want to `$ pip install --upgrade pip`.

Install the dependencies:

    $ pip install -r requirements.txt

I cannot wait to give [Pipfile](https://github.com/pypa/pipfile) a try!!

### Jupyter

Launch the Jupyter Notebook:

    $ jupyter notebook
