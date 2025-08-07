# Dataiku Interview: U.S. Census Data Income Level Classification

Project for assessing important characteristics associated with people making more or less $50K per year.

The slide deck can be found in this repository as `YangC_Dataiku_Interview_2.pdf`.

# Setup

Install dependencies using `uv`:

```
# Automatically handles creating virtual env.
uv sync
```

Or through `pip`:

```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

# Structure

Full work including exploratory data analysis, model training, tuning, and feature importance are all contained in `notebooks/main.ipynb`.

Train and test data splits are saved at `data/`.

Presentation slides are located in this repository as `YangC_Dataiku_Interview_2.pdf`.
