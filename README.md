# 🏥 Medical Cost Personal Datasets

A machine learning project for predicting individual medical insurance costs based on personal attributes. This project utilizes regression models to estimate charges from the "Medical Cost Personal Datasets" dataset.

## 📂 Project Structure
- `data/` — raw and cleaned datasets
- `notebooks/` — Jupyter notebooks with EDA and model training
- `models/` — saved models and pipelines
- `main.py` — main script for running the pipeline
- `README.md` — project documentation

## 🔧 Technologies
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- Jupyter Notebook

## 📊 Dataset Description
The dataset includes demographic and health information used to predict insurance charges:
- `age` — age of the individual
- `sex` — gender (`male`, `female`)
- `bmi` — body mass index
- `children` — number of children covered by insurance
- `smoker` — smoking status (`yes` or `no`)
- `region` — residential region in the US (`northeast`, `northwest`, `southeast`, `southwest`)
- `charges` — individual medical costs billed by health insurance (target variable)

![bjishk](https://github.com/user-attachments/assets/f4a30308-4aa6-4d43-82b9-cfc12310526a)


## 📈 Project Workflow
1. 📥 Load and explore the dataset
2. 🧼 Clean and preprocess data (encoding, scaling)
3. 📊 Perform exploratory data analysis (EDA)
4. 🤖 Train regression models (Linear, Ridge, Lasso)
5. 🧪 Evaluate performance (MAE, RMSE, R²)
6. 💾 Save and serialize the model for future use

## 🚀 How to Run
Install dependencies:
```bash
pip install -r requirements.txt
```
## Run the main pipeline:
```
Untitled.ipynb
