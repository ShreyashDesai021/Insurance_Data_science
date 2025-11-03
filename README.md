# Insurance Data Science

This repository contains a small data science project exploring insurance data. It includes CSV datasets and a Jupyter notebook with analysis and visualizations.

Contents
- `insurance.csv` — original dataset (insurance charges vs features)
- `insurance_outliers.csv` — derived/cleaned dataset with outliers removed
- `vsec-final.ipynb` — Jupyter notebook with analysis and plots
- `TableauView_ofVSEC.twb` — Tableau workbook (view)

Getting started
1. Clone the repo:

```powershell
cd /d D:\
git clone https://github.com/ShreyashDesai021/Insurance_Data_science.git
cd Insurance_Data_science
```

2. Create a virtual environment and install the basics:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Open the notebook:

```powershell
jupyter notebook vsec-final.ipynb
```

Data & license
- The CSV files are included in this repository. If you'd prefer to remove large data files from git, consider moving them to a `data/` folder and adding it to `.gitignore`, or using Git LFS.

This project is released under the MIT License (see `LICENSE`).

Contributing
- Feel free to open issues or PRs. If you add large binary artifacts (models, datasets), prefer Git LFS or a cloud storage link.

Contact
- Repo: https://github.com/ShreyashDesai021/Insurance_Data_science
