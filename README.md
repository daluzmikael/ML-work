# CSE4502 ML Work

Machine learning coursework from CSE4502 — regression, classification, and ensemble methods on real-world datasets.

## Projects

| Project | Description | Data |
|---------|-------------|------|
| [NYC Airbnb 2019](nyc-airbnb-2019/) | Predict nightly listing prices from location, room type, availability, and review features | `AB_NYC_2019_1.csv` |
| [Letter Recognition](letter-recognition/) | Classify 26 capital letters (A–Z) from 16 pixel-statistic features using ensemble methods | `letter-recognition.data.csv` |

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

Open either notebook in Jupyter and run from the top. Each project folder contains its own data file alongside the notebook.
