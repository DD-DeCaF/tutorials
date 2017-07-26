# Introduction to cobrapy

Rough schedule, we will cover as much as we can and leave the rest as homework.

- *15 min* [Getting started](cobrapy-01-getting-started.ipynb)
  - Load a model and do FBA
- *30 min* [Genome scale metabolic models and simulating](cobrapy-02-genome-scale-metabolic-models.ipynb)
  - What's in the model, reactions, metabolites, genes
  - Expressions and objectives
  - Simulating using FBA, changing the objective
- *30 min* [Manipulating the model](cobrapy-03-manipulating-the-model.ipynb)
  - Adding and emoving reactions, metabolites
  - Changing and reverting using the context manager
- *45 min* [Simulating and analyzing models](cobrapy-04-simulating-and-analyzing-metabolic-models.ipynb)
  - pFBA
  - FVA
      - Loopless
      - Additional constraints
  - Production envelope
  - Gene and reaction essentiality
- *15 min* [Constraints and variables](cobrapy-05-advanced-constraints-objectives.ipynb)
  - Defining own variables and constraints
