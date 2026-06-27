# Iris KNN Classifier

This project contains a complete Python implementation of the **K-Nearest Neighbors (KNN)** classification algorithm built from scratch. The model is trained and evaluated on the classic **Iris Dataset** to predict plant species based on their sepal and petal measurements.

---

## Features

- **Data Exploration & Preprocessing**:
  - Explores the dataset structure
  - Checks for missing values
  - Standardizes features using `StandardScaler`
- **Custom KNN Implementation**:
  - Built purely using NumPy to handle Euclidean distance metrics
  - Model fitting
  - Batch predictions
- **Hyperparameter Tuning**: Utilizes the **Elbow Method** to dynamically find the optimal number of neighbors ($k$).
- **Data Visualization**:
  - **Elbow Method Plot**: Features line plots evaluating accuracy performance across multiple $k$ values using Matplotlib.
  - **Species Prediction Scatterplot**: A scatter plot displaying how effectively the KNN algorithm separates and clusters the different flower classes based on their petal dimensions.

---

## Project Structure

```
├── src/
│   └── KNN.ipynb
├── visualizations/
│   |── elbow_method.png
│   └── iris_scatterplot.png
├── .gitignore
└── README.md
```
