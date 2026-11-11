# Machine Learning: Lab Tasks

Jupyter notebooks for the Machine Learning course, progressing from Python and NumPy basics to classification, clustering and neural networks, ending with an open-ended project on MNIST.

## Labs

| Folder | Topic |
|---|---|
| [`Lab_Task_01`](Lab_Task_01) | Python basics exercises |
| [`Lab_Task_02`](Lab_Task_02) | NumPy exercises |
| [`Lab_Task_03`](Lab_Task_03) | pandas: analysing the SF Salaries dataset |
| [`Lab_Task_04`](Lab_Task_04) | Data exploration and visualization with pandas and seaborn |
| [`Lab_Task_05`](Lab_Task_05) | Linear regression on taxi trip pricing data |
| [`Lab_Task_06`](Lab_Task_06) | Linear regression with missing-value imputation and encoding (taxi trip pricing) |
| [`Lab_Task_07`](Lab_Task_07) | Logistic regression on loan data |
| [`Lab_Task_08`](Lab_Task_08) | Logistic regression with a preprocessing pipeline (`heart.csv`) |
| [`Lab_Task_09`](Lab_Task_09) | Support Vector Machine with a preprocessing pipeline |
| [`Lab_Task_10`](Lab_Task_10) | Naive Bayes (play-tennis dataset) |
| [`Lab_Task_11`](Lab_Task_11) | Clustering with K-Means and DBSCAN (retail data) |
| [`Lab_Task_12`](Lab_Task_12) | K-Means and DBSCAN with silhouette scores (retail data) |
| [`lab_13`](lab_13) | Perceptron |
| [`Lab_14`](Lab_14) | Neural network (MLP) and SVM on the Iris dataset |
| [`ML_Project`](ML_Project) | **Open-ended lab:** MNIST digit classification comparing Logistic Regression, KNN, Naive Bayes and MLP, with GridSearchCV and K-Means |

## Tech stack

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter

## Running the notebooks

```bash
git clone https://github.com/Hammad-Ahmed-hk/Machine_Learning_Lab_Tasks.git
cd Machine_Learning_Lab_Tasks
pip install pandas numpy scikit-learn matplotlib seaborn jupyter openpyxl
jupyter notebook
```

## Data note

Only some datasets are included (`Salaries.csv`, `Dataset .csv` and the MNIST CSVs in `ML_Project`). The other notebooks read files such as `taxi_trip_pricing.csv`, `loan_data.csv`, `heart.csv`, `play_tennis.csv` and `retail_data.xlsx`, which are not in this repository. Download them from their original sources (for example Kaggle) and place them next to the notebook to re-run it.

## Author

Hammad Ahmed, [@Hammad-Ahmed-hk](https://github.com/Hammad-Ahmed-hk)
