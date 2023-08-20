# Cookiecutter Analitica Celerix

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._

## Requirements

- [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html)
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html): This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
pip install cookiecutter
```

or

``` bash
conda install -c conda-forge cookiecutter
```

## Create a new project

In a folder where you want your project generated:

```bash
cookiecutter https://bitbucket.org/analiticaauteco/cex_analitica_cookiecutter/src/master/
```

## Resulting directory structure

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is:
    │   |                     the creator's initials, a short `-` delimited description and 
    |   |                     a number (for ordering), e.g. `ACB-Analisis_de series_RUNT-01`.
    |   └── src            <- functions
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting.
    │
    └── environment.yml    <- The requirements file for reproducing the analysis environment.
    

## Contributing guide

All contributions, bug reports, bug fixes, documentation improvements, enhancements and ideas are welcome.

## Credits
☺ Alex Castaño Ballesteros 
This project is heavily influenced by [jvelezmagic's cookiecutter-conda-data-science](https://github.com/jvelezmagic/cookiecutter-conda-data-science), [drivendata's Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science), [andfanilo's Cookiecutter for Kaggle Conda projects](https://github.com/andfanilo/cookiecutter-kaggle), and julia's package [DrWatson](https://juliadynamics.github.io/DrWatson.jl/dev/).

Other links that helped shape this cookiecutter :

- [Write less terrible code with Jupyter Notebook](https://blog.godatadriven.com/write-less-terrible-notebook-code)
- [Cookiecutter DataScience Opinions](http://drivendata.github.io/cookiecutter-data-science/#opinions)
