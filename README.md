

## Task 1 – Exploring and Visualizing the Iris Dataset

###Task Objective
To load, inspect, and visualize the Iris dataset to understand feature distributions and relationships between variables.

###Dataset Used
- Name: Iris Species Dataset  
- Source:Kaggle (Iris.csv format)  
- Rows: 150  
- Columns:  
  - `SepalLengthCm`  
  - `SepalWidthCm`  
  - `PetalLengthCm`  
  - `PetalWidthCm`  
  - `Species`  

###Models Applied
- No machine learning model used in this task.  
- This task focuses on Exploratory Data Analysis (EDA) and data visualization only.

###Key Results and Findings
- Visualizations show clear differences between the three Iris species.
- Petal measurements (`PetalLengthCm`, `PetalWidthCm`) separate the species more clearly than sepal measurements.
- Distributions of features are well-behaved with limited outliers, making this dataset suitable for classification tasks.

###Files for Task 1
- `Task1_Iris_Exploration_Visualization.ipynb` – Colab notebook with:
  - Dataset loading using pandas
  - Shape, column names, `.head()`, `.info()`, `.describe()`
  - Scatter plot (SepalLengthCm vs SepalWidthCm, colored by Species)
  - Histograms of numeric features
  - Box plots to identify outliers
