Cookiecutter template suggestion
==========================

### Overview

Accoring do recent studies 42% of development time is spent dealing with maintenance of "bad" and unstructured code.

### Solution

Standardization of a code base is not only a path to reduce loss of time and money, but also provide transparency to developers, engineers and stakeholders.

### Technologies

- Black
    - Black is a code formatter, perfect for a task involving code standardization
- Cookiecutter
    - Leveraging cookiecutter features adds to the standardization process
- Sphinx
    - Creating project pages that outlines code documentation, Sphinx brings the much needed transparency into the code review process.

### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/jonathanoakica/project_template.git

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── data
│   ├── external             <- Data from third party sources.
│   ├── processed            <- The final, canonical data sets for modeling.
│   └── raw                  <- The original, immutable data dump.
│
├── docs                     <- A default Sphinx project; see sphinx-doc.org for details
│
├── models                   <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks                <- Jupyter notebooks. Naming convention is a number (for ordering),
│                                the creator's initials, and a short `-` delimited description, e.g.
│                                `1.0-jqp-initial-data-exploration`.
│
├── references               <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports                  
│   └── figures              <- Generated graphics and figures to be used in reporting
│
├── src                      <- Source code for use in this project.
│   ├── __init__.py          <- Makes src a Python module
│   │
│   ├── code_other           <- Other scripts
│   ├── data                 <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features             <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── train                <- Scripts to train, evaluate and predict models
│   │   ├── evaluate.py
│   │   ├── predict.py
│   │   └── train.py
│   │
│   └── visualization        <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
|
├── CHANGELOG.md             <- Track project versions
├── CONDUCT.md               <- Guidelines for interaction between developers
├── CONTRIBUTING.md          <- Guidelines for code contribution
├── Dockerfile               <- Empty Dockerfile as placeholder
├── Makefile                 <- Makefile with commands like `make environemnt` or `make requirements`
├── README.md                <- The top-level README for developers using this project.
├── requirements.txt         <- The requirements file for reproducing the analysis environment, e.g.
└──                             generated with `pip freeze > requirements.txt`
```

### Version

1.0 beta

### Contributors

Jonathan Oaks



