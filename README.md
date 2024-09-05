# ⛔️ Deprecated ⛔️ Lexic_split_Weka
This repository contains the **deprecated implementation** of the lexicographic split function in Weka source codes for Decision Trees and Random Trees. These implementations were used for [our paper](https://link.springer.com/article/10.1007/s10462-024-10718-1) yet recently they have been extended in Python as follow.

# 🐍 Python Implementation of Lexicographical Tree-Based Machine Learning Algorithms

> **Scikit-longitudinal (Sklong)** is an open-source Python library & _Scikit-Learn API_ compliant, tailored to longitudinal machine learning classification tasks. It is ideal for researchers, data scientists, and analysts, as it provides specialist tools for dealing with repeated-measures data challenges. [Code](https://github.com/simonprovost/scikit-longitudinal) & [Documentation](https://simonprovost.github.io/scikit-longitudinal/)

As a result, they extended our introduced lexicographical optimisation approach to the following:

## Extension of the Lexicographical Optimisation

| Standard Model                                | Longitudinal-Adapted Model                         |
|-----------------------------------------------|----------------------------------------------------|
| **Decision Tree**                  | _Lexicographical_ Decision Tree [(API Ref.)](https://simonprovost.github.io/scikit-longitudinal/API/estimators/trees/lexico_decision_tree_classifier/) |
| **Random Forest**                  | _Lexicographical_ Random Forest [(API Ref.)](https://simonprovost.github.io/scikit-longitudinal/API/estimators/ensemble/lexico_random_forest/) |
| **Decision Tree Regressor**        | _Lexicographical_ Decision Tree Regressor  [(API Ref.)](https://simonprovost.github.io/scikit-longitudinal/API/estimators/trees/lexico_decision_tree_regressor/) |
| **Deep Forest**                    | _Lexicographical_ Deep Forest [(API Ref.)](https://simonprovost.github.io/scikit-longitudinal/API/estimators/ensemble/lexico_deep_forest/) |
| **Gradient Boosting**              | _Lexicographical_ Gradient Boosting  [(API Ref.)](https://simonprovost.github.io/scikit-longitudinal/API/estimators/ensemble/lexico_gradient_boosting/) |

# 🎓 Cite us !

```
@article{Ribeiro2024,
  title = {A lexicographic optimisation approach to promote more recent features on longitudinal decision-tree-based classifiers: applications to the English Longitudinal Study of Ageing},
  volume = {57},
  ISSN = {1573-7462},
  url = {http://dx.doi.org/10.1007/s10462-024-10718-1},
  DOI = {10.1007/s10462-024-10718-1},
  number = {4},
  journal = {Artificial Intelligence Review},
  publisher = {Springer Science and Business Media LLC},
  author = {Ribeiro,  Caio and Freitas,  Alex A.},
  year = {2024},
  month = mar 
}
```
