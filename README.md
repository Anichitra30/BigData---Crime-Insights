# Crime Insights

Project description

With different areas experiencing diverse amounts of criminal activity, the city of Chicago continues to struggle with controlling and reducing crime. There is an urgent need for an improved crime prediction system designed specifically for Chicago in order to handle this issue and allocate resources effectively. To predict where and when crimes are likely to occur, this system should make use of socioeconomic indicators, past crime data, and other pertinent aspects. The main objective of this project is to create a reliable crime prediction model for Chicago that will help law enforcement organizations and local government representatives allocate resources proactively and carry out targeted interventions to lower crime rates and improve public safety. 

The problem of crime prediction in Chicago is critically important due to its potential to enhance public safety and resource allocation. High crime rates can lead to physical harm, property damage, and reduced quality of life for residents.

The project utilizes a diverse dataset that includes historical crime data for Chicago. This dataset contains information such as crime types, locations, timestamps and demographic data. 
[Data Link](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data)

Started on 2023-09-15.

## Project Organization

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── datasets
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── final          <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── docs               <- Code documentation and generated analysis as HTML, PDF, LaTeX, etc.
│   └── images         <- Generated graphics and figures to be used in reporting
|   └── reports        <- Generated analysis as HTML, PDF, LaTeX, etc.
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── src                <- Source code for use in this project.
|__ output             <- Temporary Output files
```
## Features
- Commit Message checking via commitlint
- [Linter support for R lang](https://github.com/r-lib/lintr)
- [R Lang Code formatter using Styler](https://github.com/r-lib/styler)
- [R lang general checks using pre-commit hooks](https://lorenzwalthert.github.io/precommit/articles/available-hooks.html)
- [Local Testing via pre-commit](https://pre-commit.com/)
- Github Integration 
- CI testing via Github actions and pre-commit.ci
- Github CODEOWNERS to automatically add owners to Github PR
- Github pull request remplates for standardizing description
- Multiple programming language support in the directory structure
- R Lang test cases support using Makefile and Github actions

## Requirements:
- [pre-commit](https://pre-commit.com/)
    ```
        pip install pre-commit
    ```
- [commitlint](https://github.com/conventional-changelog/commitlint)
    ```
        npm install -g @commitlint/cli @commitlint/config-conventional
    ```
    for this Nodejs is required. Download and install from here [Nodejs](https://nodejs.org/en/download/)

## Note:
This template is tested with Mac OS. So, all the commands and programs should work smoothly on mac and linux. Windows user might face some issues in the installation. Our future goal is to make this template platform independent.

## Acknowledgments
- [drivendata/cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science)
- [pal0064/Sonic](https://github.com/pal0064/Sonic)
