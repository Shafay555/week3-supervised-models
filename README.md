Week 3: Supervised Models on the Diabetes Prediction Dataset

Dataset:Diabetes Prediction Dataset (Kaggle), 100,000 rows (96,146 after removing duplicates), 9 columns, target = diabetes.

Summary
- Trained KNN, Decision Tree and Logistic Regression to predict diabetes.
- Compared them using accuracy, confusion matrix, precision, recall and F1-score.
- The data is imbalanced (about 91% No, 9% Yes), so accuracy alone is misleading and recall is the key metric.

Best model:Decision Tree (max_depth = 2) with accuracy 97.2% (F1 = 0.808).

How to run
1. Install the libraries: pip install -r requirements.txt
2. Start Jupyter: jupyter notebook
3. Open Assignment3.ipynb and click Kernel > Restart and Run All.
