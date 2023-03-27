{{ cookiecutter.project_name.replace(' ', '_').replace('-', '_') }}
==========================

### Description



### Our Solution



### Technologies


------------

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

{{ cookiecutter.version }}

### Contributors

{{ cookiecutter.author }}

### Links



