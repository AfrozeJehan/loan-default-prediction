# Loan Default Prediction

[![View live report](https://img.shields.io/badge/Report-View%20live%20report-blue)](https://afrozejehan.github.io/loan-default-prediction/)
[![Notebook](https://img.shields.io/badge/Notebook-View%20analysis-orange)](loan_default_prediction.ipynb)

Classification analysis of the HMEQ home-equity-loan dataset, completed for
the MIT Professional Education Applied Data Science Program.

## Project overview

The notebook predicts whether a borrower is likely to default (`BAD`) using
loan, property, employment, credit-history, and debt-to-income variables. It
covers data-quality checks, missing-value treatment, categorical encoding,
outlier treatment, logistic regression, decision tree, random forest, and
XGBoost comparisons, with grid search and classification metrics.

## Results and reproducibility

- [Project repository](https://github.com/AfrozeJehan/loan-default-prediction)
- [Live report landing page](https://afrozejehan.github.io/loan-default-prediction/)
- [Live HTML report](https://afrozejehan.github.io/loan-default-prediction/loan_default_prediction.html)
- [Executed notebook](loan_default_prediction.ipynb)
- [Rendered HTML report and embedded visuals](loan_default_prediction.html)
- [Results notes](docs/results.md)
- [Data dictionary](docs/data-dictionary.md)

The source HMEQ dataset is intentionally not included. To run the notebook,
create an environment with `pip install -r requirements.txt`, obtain the
dataset, and update the Colab-style path used by the notebook. The HTML report
is the easiest way to review the supplied execution without the dataset.

The report identifies debt-to-income ratio as an important feature. Its
reported metrics are educational outputs and require fresh validation,
threshold analysis, fairness review, and monitoring before any lending use.

## Repository and license

GitHub Actions validates notebook JSON and required documentation links without
attempting to run the notebook or requiring unavailable data. This project is
released under the [MIT License](LICENSE).

## Attribution

Developed for the MIT PE Applied Data Science Program: *Leveraging AI for
Effective Decision-Making*.
