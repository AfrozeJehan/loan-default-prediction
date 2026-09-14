# Data dictionary

The notebook documents the following HMEQ columns. The source dataset is not
included in this repository.

| Column | Meaning | Role / notes |
| --- | --- | --- |
| `BAD` | Whether the client defaulted (`1`) or repaid (`0`) | Binary target |
| `LOAN` | Amount of loan approved | Numeric predictor |
| `MORTDUE` | Amount due on the existing mortgage | Numeric predictor |
| `VALUE` | Current property value | Numeric predictor |
| `REASON` | Reason for the loan request, including `HomeImp` and `DebtCon` | Categorical predictor |
| `JOB` | Applicant job category | Categorical predictor |
| `YOJ` | Years at the present job | Numeric predictor |
| `DEROG` | Number of major derogatory reports | Numeric predictor |
| `DELINQ` | Number of delinquent credit lines | Numeric predictor |
| `CLAGE` | Age of the oldest credit line, in months | Numeric predictor |
| `NINQ` | Number of recent credit inquiries | Numeric predictor |
| `CLNO` | Number of existing credit lines | Numeric predictor |
| `DEBTINC` | Debt-to-income ratio | Numeric predictor |

The notebook describes 5,960 records, with `BAD = 1` in 1,189 cases
(approximately 20%). Missing values are present in several predictors and are
handled in the analysis.
