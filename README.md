# Segmenting the Market:
A Two-Stage Random Forest Approach for Predicting Prices in Skewed and Heterogeneous Secondhand Car Data

---

This thesis is submitted in partial fulfillment of the requirements for the degree of master of science in data science & society at the school of humanities and digital sciences of tilburg university

## 📁 Repository Structure:

| File / Folder                     | Description                                                               |
|-----------------------------------|---------------------------------------------------------------------------|
| `01_*.ipynb`                      | Data cleaning, model feature standardization, and feature creation        |
| `02_encoding.ipynb`              | Categorical and ordinal encoding, including log and ratio transformations  |
| `03_EDA_visuals.ipynb`           | Exploratory Data Analysis (EDA) and variable inspection                    |
| `05_1_two-stage_Classification`  | Random Forest classifier for price segmentation                            |
| `05_2-4_two-stage_[High/Mid/Low]`| Segment-specific Random Forest regressors for each price class             |
| `06_single-stage_Regression`     | Baseline Random Forest model trained on the full dataset                   |
| `07_dummy_Regression`            | DummyRegressor using the global median price                               |
| `08_combine_results.ipynb`       | Aggregates results from all models (05_1-4, 06, 07) into one DataFrame     |
| `09_visualize_results.ipynb`     | Generates final plots and tables used in the thesis                        |
| `requirements.txt`               | List of required Python libraries                                          |


## 📁 Dataset used:
The dataset used in this project is:
https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data

## Citation
Verhaar, Q(2025), Segmenting the Market: A Two-Stage Random Forest Approach for Predicting Prices in Skewed and Heterogeneous Secondhand Car Data. Master's Thesis, Tilburg University
