# 💻 Laptop Price Prediction

This notebook demonstrates the process of predicting laptop prices using machine learning techniques. We cover essential steps such as data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

### **📋 Project Overview**

In this project, we used a dataset containing information about various laptops, including brand, RAM, CPU, and more, to predict laptop prices. A Random Forest Regressor was utilized to build the prediction model, which we evaluated using test data and visualization techniques.

### **🌟 Key Features:**

* 🗂️ Data Preprocessing: Cleaned and transformed the dataset by handling categorical variables, extracting features, and converting data types for model readiness.
* 📊 Exploratory Data Analysis (EDA): Visualized relationships and correlations between different variables to gain insights.
* 🛠️ Feature Engineering: Engineered key features such as screen resolution, CPU, and memory to improve model performance.
* 🤖 Model Training: Trained a Random Forest Regressor to predict laptop prices.
* 📈 Model Evaluation: Evaluated the model’s performance by calculating accuracy and visualizing predicted vs. actual prices.
  
### **📁 Dataset:**

The dataset used for this project contains various laptop attributes such as:

🔹 Product
🔹 Company
🔹 TypeName
🔹 RAM
🔹 CPU
🔹 GPU
🔹 Memory
🔹 ScreenResolution
🔹 Weight
🔹 Price (target)

### **🛠️ Libraries Used:**

* Pandas: For data manipulation and analysis.
* NumPy: For numerical operations.
* Seaborn & Matplotlib: For data visualization.
* Scikit-learn: For machine learning algorithms and preprocessing.

### **🧩 Model Pipeline**
1. Data Preprocessing:

* Dropped irrelevant columns (e.g., Product).
* One-hot encoded categorical variables (e.g., Company, TypeName).
* Extracted key features from columns like ScreenResolution, Cpu, Memory, and Gpu.
* Scaled the data using StandardScaler.
  
2. Exploratory Data Analysis:

* Visualized the correlation between features using heatmaps.
* Explored the distribution of key variables.
  
3. Model Training:

* Used RandomForestRegressor to train the model on the processed dataset.
* Split data into training and testing sets for evaluation.
  
4. Model Evaluation:

* Calculated the model's accuracy score.
* Visualized predictions using a scatter plot comparing predicted vs. actual prices.
  
Prediction Example:
* Made a sample price prediction for a test laptop and compared it with the actual price.
  
### **📊 Results**

* The Random Forest Regressor achieved a competitive accuracy on test data.
* Key features that significantly influenced the price prediction include:
* RAM 💾
* CPU Frequency 🖥️
* Memory Amount 🗄️
* Weight ⚖️
  
### **🔍 Conclusion:**

This project demonstrates how machine learning models can be used to predict laptop prices based on various specifications. We achieved a decent model score, and future improvements could include experimenting with more advanced models or tuning hyperparameters more extensively.
