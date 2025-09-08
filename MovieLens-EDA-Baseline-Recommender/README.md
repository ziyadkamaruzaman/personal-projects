
# MovieLens EDA & Baseline Recommender

This project provides a hands-on introduction to recommender systems using the MovieLens dataset. It includes:
- Exploratory Data Analysis (EDA) to understand user and movie behavior
- Visualizations of rating distributions and activity
- A baseline recommender that predicts ratings using the mean rating for each movie
- Evaluation of the baseline recommender's performance

The code is organized in a Jupyter notebook, making it easy to follow and adapt for your own experiments.


## Project Structure
- `notebooks/` — Jupyter notebooks for EDA and modeling
- `data/` — Place MovieLens dataset files here
- `src/` — (Optional) Source code for data processing and recommender logic


## Getting Started
1. Download the MovieLens dataset from [GroupLens](https://grouplens.org/datasets/movielens/).
2. Place the dataset files (e.g., `ratings.csv`, `movies.csv`) in the `data/` directory.
3. Install requirements:
	```bash
	pip install -r requirements.txt
	```
4. Open `notebooks/01_movielens_eda_baseline.ipynb` in Jupyter or VS Code and run the cells.

## Requirements
- Python 3.8 or newer
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn

## Features
- Data loading and inspection
- User and movie statistics
- Ratings distribution visualizations
- Baseline recommender (mean rating)
- Evaluation with RMSE and MAE

---
This project is ideal for learning the basics of recommender systems and EDA with real-world data. Feel free to fork and extend!
