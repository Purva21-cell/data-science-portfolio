# Data Science Portfolio

A curated collection of reproducible data-science projects, notebooks, and Python utilities.

## About
This repository demonstrates an end-to-end, beginner-friendly machine-learning workflow:
- loading and understanding a dataset
- exploratory data analysis (EDA)
- building a preprocessing and classification pipeline
- evaluating a held-out test set
- writing reusable, testable Python code

## Repository structure
```text
data-science-portfolio/
├── notebooks/
│   └── 01_iris_classification.ipynb
├── src/
│   └── portfolio_analysis.py
├── tests/
│   └── test_portfolio_analysis.py
├── .github/workflows/tests.yml
├── .gitignore
├── LICENSE
├── pyproject.toml
└── README.md
```

## Quick start

Python 3.10 or newer is recommended.

```bash
python -m venv .venv
```

Activate the environment:

**Windows PowerShell**
```powershell
.\.venv\Scripts\Activate.ps1
```

**Windows Command Prompt**
```bat
.venv\Scripts\activate.bat
```

**macOS / Linux**
```bash
source .venv/bin/activate
```

Install dependencies:

```bash
python -m pip install --upgrade pip
pip install -e ".[dev]"
```

Run the analysis:

```bash
python -m src.portfolio_analysis
```

Run tests:

```bash
pytest
```

Launch the notebook:

```bash
jupyter notebook
```

Open `notebooks/01_iris_classification.ipynb`.

## Example project: Iris classification

The example uses the Iris dataset bundled with scikit-learn, so no manual dataset download is needed. It creates a stratified train/test split, fits preprocessing only on the training data through a scikit-learn pipeline, and reports accuracy and a classification report.

The dataset is used for demonstration and is not a substitute for a domain-specific project.

## Add your own projects

For each new project, create a separate folder or notebook and include:
1. a clear problem statement and objective
2. the source and license of the dataset
3. data-cleaning and EDA steps
4. a reproducible methodology and evaluation
5. conclusions, limitations, and next steps

Do not commit passwords, API keys, private datasets, or personal information.

## Author

**Your Name**  
Add your GitHub profile, LinkedIn, and contact details here.
