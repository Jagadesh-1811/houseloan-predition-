# houseloan-predition-
🏠 Home Loan Prediction - Decision Tree Classifier
📌 Objective
This project predicts whether a loan will be approved or not using a Decision Tree Classifier model. It uses labeled training data to train the model and then predicts outcomes on test data.
📂 Dataset
Two datasets are used:
- Training Set: Contains features and labels (Loan_Status).
- Test Set: Contains only features. The model predicts loan approval status for this set.

Path: E:/datasets/train_hm.csv and E:/datasets/test_hm.csv
🔧 Libraries Used
- pandas: Data manipulation
- numpy: Numerical operations
- seaborn & matplotlib.pyplot: Data visualization
- warnings: Suppressing warnings
- sklearn: Machine learning models & metrics
🧠 Workflow Summary
1. 📥 Data Loading
The dataset is loaded using pandas. Original copies are made to preserve the raw data.
2. 🧹 Data Preprocessing
Missing values are handled, and categorical variables are encoded using LabelEncoder or get_dummies.
3. 📊 Exploratory Data Analysis (EDA)
Visualizations such as histograms, count plots, and boxplots are used to analyze feature distributions and relationships.
4. 🏗️ Feature Engineering
New features like Total_Income, EMI, and Balance_Income are created.
Log transformations are applied to skewed features.
5. 🧪 Model Building
A Decision Tree Classifier is trained using the training dataset. The model is evaluated with accuracy and confusion matrix.
6. 📈 Prediction and Evaluation
Loan status predictions are made on the test dataset, and results are saved as a CSV file.
📁 Output
A CSV file with predicted loan statuses for test data.
🚀 How to Run
1. Install required libraries:
   pip install pandas numpy seaborn matplotlib scikit-learn

2. Make sure the datasets are placed at:
   E:/datasets/train_hm.csv
   E:/datasets/test_hm.csv

3. Run the Jupyter Notebook:
   jupyter notebook "Home loan Prediction - decision Tree Classifier.ipynb"
✅ Results
The Decision Tree model successfully predicts loan approvals. The accuracy may vary based on preprocessing and feature selection.
