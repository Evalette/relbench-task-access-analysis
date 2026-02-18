# RelBench dataset and task access notes

This repository collects a small research notebook with experiments on accessing RelBench datasets and tasks for my master's thesis.

## Context

I am using RelBench as a benchmark for a master's thesis project on graph neural networks over relational databases.  
The notebook in this repository was created with:

- `relbench==2.0.2`
- Python 3 (local environment)
- Datasets and tasks listed on https://relbench.stanford.edu

## What is in this repository?

- `task_accessibility_and_format_test.ipynb`  
  A Jupyter notebook that:
  - lists datasets and tasks available through the `relbench` Python API,
  - compares their names to those documented on the RelBench website,
  - tests which datasets and tasks can be downloaded and accessed,
  - records error messages (e.g., hash mismatches, 404 errors, missing dependencies).

## How this repository is used

The results in this notebook are meant to support clear GitHub issues for the `snap-stanford/relbench` repository,  
by providing minimal code examples and full error messages in one place.
