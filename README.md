# Principal Component Analysis (PCA) on Wine Dataset

## Project Overview

This project demonstrates the implementation of **Principal Component Analysis (PCA)**, a dimensionality reduction technique used to simplify high-dimensional datasets while preserving the maximum amount of information.

The Wine Dataset from Scikit-Learn was used to reduce 13 numerical features into 2 principal components, making the dataset easier to visualize and analyze.

The project also evaluates the explained variance ratio and visualizes the transformed data in two dimensions.

---

## Dataset Information

### Dataset Source

Scikit-Learn Built-in Wine Dataset

### Dataset Size

* Total Samples: **178**
* Total Features: **13**
* Target Classes: **3 Wine Categories**

### Features

The dataset contains chemical analysis measurements of wines, including:

* Alcohol
* Malic Acid
* Ash
* Alcalinity of Ash
* Magnesium
* Total Phenols
* Flavanoids
* Nonflavanoid Phenols
* Proanthocyanins
* Color Intensity
* Hue
* OD280/OD315
* Proline

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Google Colab

---

## Project Workflow

### 1. Data Loading

Loaded the Wine Dataset directly from the Scikit-Learn library.

### 2. Data Exploration

Performed exploratory analysis by:

* Viewing dataset structure
* Checking dataset dimensions
* Examining feature information
* Generating statistical summaries

### 3. Feature Scaling

Standardized all numerical features using **StandardScaler** before applying PCA.

Feature scaling is necessary because PCA is sensitive to differences in feature scales.

### 4. Principal Component Analysis

Applied PCA to reduce the dataset from **13 features** to **2 principal components**.

### 5. Transformed Dataset

Generated a new dataset containing:

* Principal Component 1
* Principal Component 2
* Target Class

### 6. Explained Variance Analysis

Calculated the explained variance ratio to determine how much information each principal component retained from the original dataset.

### 7. Data Visualization

Created:

* Explained Variance Plot
* 2D PCA Scatter Plot

to better understand the reduced feature space.

---

## Deliverables

* PCA Model
* Transformed Dataset
* Explained Variance Ratio
* Variance Plot
* 2D PCA Visualization

---

## Results

### Principal Components

The original dataset with 13 numerical features was successfully reduced to **2 principal components**.

### Explained Variance

The explained variance ratio indicates the proportion of total dataset variance captured by each principal component.

### Visualization

The 2D PCA visualization demonstrates how the three wine classes are distributed after dimensionality reduction while preserving the overall data structure.

---

## Visualizations

### Explained Variance Plot

Displays the amount of variance explained by each principal component.

### PCA Scatter Plot

Shows the transformed dataset in two dimensions and highlights the separation of different wine classes.

---

## Key Concepts Learned

* Unsupervised Learning
* Principal Component Analysis (PCA)
* Dimensionality Reduction
* Feature Scaling
* Explained Variance Ratio
* Data Visualization
* High-Dimensional Data Analysis

---

## Interview Questions

### What is Dimensionality Reduction?

Dimensionality Reduction is the process of reducing the number of input features while retaining as much important information as possible. It helps simplify data, reduce computational cost, and improve visualization.

### Why is PCA Used?

PCA is used to:

* Reduce feature dimensions
* Remove redundant information
* Improve computational efficiency
* Minimize noise
* Visualize high-dimensional datasets in lower dimensions

### Why is Feature Scaling Required Before PCA?

PCA is based on variance. Features with larger scales can dominate the analysis. Standardizing features ensures that every feature contributes equally.

---

## Conclusion

Principal Component Analysis (PCA) was successfully implemented on the Wine Dataset to reduce dimensionality while preserving the majority of the dataset's variance.

The transformed dataset and visualizations demonstrate that PCA effectively simplifies high-dimensional data, making it easier to analyze and visualize without significantly losing information.

This project provides a practical understanding of dimensionality reduction techniques used in machine learning and data analysis.

---

## Repository Structure

Task11-PCA-Wine-Dataset/

├── Task11_Principal_Component_Analysis.ipynb

├── variance_plot.png

├── pca_visualization.png

├── README.md

---

## Author

**Ankit Yadav**

MCA Student


