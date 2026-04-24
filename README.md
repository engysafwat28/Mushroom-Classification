# Mushroom-Classification
Machine learning project developed as part of a Kaggle competition to classify mushrooms as edible or poisonous based on their features. Includes data preprocessing, feature engineering, and model optimization.
# Mushroom Classification - Kaggle Competition

# 🚀 Project Overview
This project was developed as part of a Kaggle competition to classify mushrooms as:

# ✅ Edible (e)
# ☠️ Poisonous (p)
based on their physical and biological characteristics.

The objective is to build a high-performance machine learning model that generalizes well on unseen data.

# 🏆 Results
# 🎯 Kaggle Public Score: 0.97404
📈 Excellent predictive performance
🔥 Strong generalization on test data
# 📊 Dataset Description
The dataset contains multiple features describing mushrooms, including:

Cap shape, color, diameter
Stem height and width
Ring type
Surface characteristics
📌 Source: Kaggle Playground Series - Season 4 Episode 8

# 🔍 Exploratory Data Analysis (EDA)
✔ Checked missing values and handled them effectively
✔ Removed duplicate records
✔ Dropped irrelevant or low-impact features
✔ Visualized key patterns using:

📊 Pie chart → Class distribution
📉 Histograms → Numerical features distribution
🔥 Heatmap → Feature correlation
📊 Count plots → Categorical relationships
# 💡 Key Insight:

Numerical features such as stem-height and stem-width are right-skewed, meaning most mushrooms have smaller values with few large outliers.
# ⚙️ Data Preprocessing
# 🧹 Data Cleaning
Removed unnecessary columns: id, veil-type, stem-root, stem-surface, veil-color, spore-print-color
Removed duplicates
# 🔄 Handling Missing Values
Categorical → Filled with mode
Numerical → Dropped in train data and Filled with median in test data
# 🧠 Feature Engineering
Reduced noise by removing rare categories
Extracted categorical patterns using regex
# 🔧 Transformations
 StandardScaler → Numerical features
 OneHotEncoder → Categorical features
# 🤖 Model Building
A complete machine learning pipeline was built using:

🔗 ColumnTransformer (for preprocessing)
⚡ XGBoost Classifier
🎯 GridSearchCV (5-fold cross-validation)
🔍 Hyperparameter Tuning
param_grid = {
  'model__n_estimators': [100, 200],
  'model__max_depth': [4, 6, 8],
  'model__learning_rate': [0.01, 0.1, 0.2]
}
# 📈 Model Evaluation
✅ Accuracy Score
📊 Confusion Matrix
✔ High training accuracy
✔ Strong test performance
✔ No significant overfitting observed

# 🧠 Skills Demonstrated
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Machine Learning Pipelines
Hyperparameter Tuning
Model Evaluation
XGBoost Implementation
# 🛠️ Technologies Used
Python 🐍
Pandas & NumPy
Scikit-learn
XGBoost
Matplotlib & Seaborn
Plotly
# 💡 Future Improvements
🚀 Try advanced models (LightGBM, CatBoost)
📊 Perform feature importance analysis
🌐 Deploy model using Streamlit or Flask
⚡ Optimize inference speed
# 🙌 Acknowledgment
Thanks to Kaggle for providing this dataset and competition environment.

# ⭐ Support
If you found this project useful:

⭐ Give it a star on GitHub
💬 Share your feedback
# 👩‍💻 Author
Engy Safwat  
Machine Learning Developer
