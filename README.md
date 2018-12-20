# Developing hypotheses based on public databases
---

*Shaimar González Morales*

*BIOF309*

# Purpose

This project is intended to help undergraduate and early graduate students to develop research projects.

To design a research project you first have to be familiar with the field you want to study. For that you need to read primary literature from the field. One place where you can find primary literature in biomedical sciences is PubMed (https://www.ncbi.nlm.nih.gov/pubmed/). 

Questions to ask yourself while you are reading a scientific article:

1. What is the big question being addressed in this paper?

2. What are the major weaknesses of the paper?

3. Are the data convincing (if not, say why)?

4. Considering the findings outlined in this paper, what new question arises that
interests you?

5. How can the methods/concept of the paper be applied to your field?

Once you are familiar with the field, ask yourself what questions still are not answered. The following steps are designed for you to test your questions and give you a little bit of insight (remember that these will be correlations and correlations doesn't imply causality). If you read articles and still can't develop a hypothesis, you can go to databases and follow some of the steps below and then go back to the literature to see if there are articles that support your idea.

# Overview

-Using datasets to support your hypothesis
-Using web-based software to interpret data
-Assessing possible implications of your hypothesis


# Using datasets to support your hypothesis

Analyzing data from NCBI GEO database

-Cleaning data

-Building graphs

-Statistical analysis

# Using web-based software to interpret data

Looking at correlations in Ingenuity Pathway Analysis

-Building Venn/Euler diagrams 

# Assessing possible implications of your hypothesis

Looking at correlations with disease dataset

-Cleaning data

-Building graphs

-Statistical analysis

# Summary 

Hopefully this project helped you have a better idea of how to design a research question and how to look for evidence that could support your hypothesis.

# Resources: Developing a research question

Writing a Good Research Question 

(https://cirt.gcu.edu/research/developmentresources/tutorials/question

Planning Your Scientific Journey 

(https://courses.ibiology.org/courses/course-v1:iBiology+iBio1+2017_2/about) 

Developing a Research Question

(https://www.esc.edu/online-writing-center/resources/research/research-paper-steps/developing-questions/)

How to Write a Research Question

(https://writingcenter.gmu.edu/guides/how-to-write-a-research-question)



Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as PPTx.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

