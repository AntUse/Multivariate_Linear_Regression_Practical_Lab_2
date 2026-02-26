# Practical Lab 2 — Multivariate Linear Regression

This folder contains the notebook `Multivariate_Linear_Regression.ipynb` used for Practical Lab 2 (Diabetes dataset). The notebook performs EDA, trains univariate and multivariate models, evaluates them with R²/MAE/MAPE, and shows plots.

Prerequisites
- Python 3.8+ (macOS ships with Python; use a recent interpreter)

Quick setup (create and use virtual environment)

1. From the `PracticalLab2` folder, create a virtual environment:

```bash
python3 -m venv venv
```

2. Activate the virtual environment (zsh, macOS):

```bash
source venv/bin/activate
```

You should now see `(venv)` in your shell prompt.

3. Install required packages:

```bash
pip install --upgrade pip
pip install numpy pandas scikit-learn matplotlib seaborn jupyterlab
```

(Optionally create a `requirements.txt` with the above packages: `pip freeze > requirements.txt`)

Running the notebook

1. Activate the venv if not already active:

```bash
source venv/bin/activate
```

2. Start Jupyter Lab (or Notebook):

```bash
jupyter lab
# or
jupyter notebook
```

3. Open `Multivariate_Linear_Regression.ipynb` and run the cells.

Notes
- The notebook uses `scikit-learn`'s toy diabetes dataset (no external data files required).\n- For reproducible results, the notebook sets a random seed.\n- If you need to install additional packages, ensure the venv is active before installing.\n
Deactivate venv

```bash
deactivate
```

If you want, I can add a `requirements.txt` and a one-line runner script next. Would you like that?