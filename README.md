# CME538 Assignments

My work for the assignments in CME538 (Introduction to Data Science for Civil & Mineral Engineers), Fall 2026.

## Repository Contents

| Path | Contents |
|---|---|
| [`assignments/`](./assignments/) | Assignment notebooks (`assignment1`–`assignment9`), their datasets, and supporting files. |
| [`requirements.txt`](./requirements.txt) | Python dependencies used by the notebooks. |

Each `assignments/assignmentN/` folder holds the notebook(s) and data for that assignment.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

Then open the notebook for the assignment you want to run.

## Notes

- Lecture and tutorial materials are not included in this repository.
- The zipped copy of assignment 4 (`assignment4.zip`) is not tracked; use the `assignments/assignment4/` folder instead.
- A few datasets are large (e.g. the 2019 bike share CSVs and `winemag_data.csv`, 50 MB+).
