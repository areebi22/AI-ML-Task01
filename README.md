
## Task 1 – Exploring and Visualizing the Iris Dataset

### 🔹 Task Objective
To load, inspect, and visualize the Iris dataset to understand feature distributions and relationships between variables.

### 🔹 Dataset Used
- **Name:** Iris Species Dataset  
- **Source:** Kaggle (Iris.csv format)  
- **Rows:** 150  
- **Columns:**  
  - `SepalLengthCm`  
  - `SepalWidthCm`  
  - `PetalLengthCm`  
  - `PetalWidthCm`  
  - `Species`  

### 🔹 Models Applied
- No machine learning model used in this task.  
- This task focuses on **Exploratory Data Analysis (EDA)** and **data visualization** only.

### 🔹 Key Results and Findings
- Visualizations show clear differences between the three Iris species.
- Petal measurements (`PetalLengthCm`, `PetalWidthCm`) separate the species more clearly than sepal measurements.
- Distributions of features are well-behaved with limited outliers, making this dataset suitable for classification tasks.

### Files for Task 1
- `Task1_Iris_Exploration_Visualization.ipynb` – Colab notebook with:
  - Dataset loading using pandas
  - Shape, column names, `.head()`, `.info()`, `.describe()`
  - Scatter plot (SepalLengthCm vs SepalWidthCm, colored by Species)
  - Histograms of numeric features
  - Box plots to identify outliers

## Task 2 – Heart Disease Prediction

### 🔹 Task Objective
To build a machine learning model that predicts whether a person is at risk of heart disease based on medical attributes.

### 🔹 Dataset Used
- **Name:** Heart Disease UCI Dataset  
- **Source:** Kaggle  
- **Type:** Medical / Clinical data  
- **Target Variable:** `target` (0 = No disease, 1 = Disease)

### 🔹 Models Applied
- Logistic Regression

### 🔹 Key Results and Findings
- The dataset contained no missing values and required minimal preprocessing.
- Exploratory Data Analysis (EDA) revealed relationships between features such as age, thalach, oldpeak, and heart disease.
- Logistic Regression achieved good predictive performance on test data.
- ROC-AUC and confusion matrix results indicate the model can effectively distinguish between patients with and without heart disease.
- Feature coefficients highlight medically relevant attributes influencing prediction.

### Files for Task 2
- `Heart_Disease_Prediction.ipynb`
---

## Task 3 – House Price Prediction

### 🔹 Task Objective
To predict house prices based on property features such as area, number of bedrooms, bathrooms, parking, and other amenities using a regression model.

### 🔹 Dataset Used
- **Name:** Housing Price Prediction Dataset  
- **Source:** Kaggle  
- **Type:** Real estate dataset  
- **Target Variable:** `price`

### 🔹 Models Applied
- Linear Regression

### 🔹 Key Results and Findings
- The dataset was preprocessed by handling missing values and converting categorical features into numeric form using one-hot encoding.
- An 80–20 train-test split was applied to evaluate model performance on unseen data.
- A Linear Regression model was trained to learn the relationship between house features and prices.
- Model evaluation using **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)** showed reasonable predictive performance.
- RMSE was higher than MAE, indicating that larger prediction errors were penalized more heavily.

### 📁 Files for Task 3
- `House_Price_Prediction.ipynb`
