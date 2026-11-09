# Fair and Calibrated Credit Decisions Under Limited Human Review Capacity

Team Oversight · Project 5 · Course submission v05

This study compares credit default models, evaluates calibration and group disparities, and simulates how limited human-review capacity is allocated. Review outcomes and decision costs are scenario assumptions. The Statlog German Credit analysis is an exploratory secondary benchmark.

## Files

| File | Contents |
| --- | --- |
| `team-oversight-fair-calibrated-credit-v05(4).ipynb` | Executed notebook with the analysis and displayed outputs for RQ1–RQ5. |
| `fairness_review_capacity_results(5).zip` | Exported PDF figures and CSV tables, including run settings and the export manifest. |

## Data and execution

Download the original archives from the [UCI Default of Credit Card Clients](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients) and [UCI Statlog German Credit](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data) pages.

1. Import the notebook into Kaggle and attach both archives as inputs. Select CPU and run all cells from a fresh session.
2. Download `fairness_review_capacity_results.zip` from the notebook output. The notebook writes it to `/kaggle/working/fairness_review_capacity_results.zip`.

For local Jupyter execution, place both original archives in the working folder. Use a Python 3 kernel with NumPy, pandas, SciPy, scikit-learn, Matplotlib, IPython, and `xlrd` for the original `.xls` file. Restart the kernel and run all cells. If discovery finds multiple inputs, use the two explicit data path settings described in the notebook.

## Target journal

*Decision Support Systems* (Elsevier). This repository contains the course submission. The audit identified revisions before journal submission.
