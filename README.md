#  K-Nearest Neighbors (KNN) Classification – Iris Dataset

# Task 6 – AI & ML Internship Project
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm using the popular **Iris dataset**. It includes data normalization, model training, evaluation, and visualization of decision boundaries.

# Dataset
- **Name**: Iris Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/iris)
- **Attributes**:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
  - Species (Target variable)

# Tools & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (sklearn)

# What I Did
1. Loaded the Iris dataset from a CSV file
2. Preprocessed the data (removed unnecessary columns, normalized features)
3. Split data into training and testing sets
4. Trained a **KNeighborsClassifier** from `sklearn`
5. Evaluated the model using:
   - Accuracy
   - Confusion Matrix
6. Plotted **Accuracy vs K**
7. Visualized **Decision Boundaries** using first two features

# Sample Results
- **Best Accuracy (k=3)**: `100%`
- **Confusion Matrix** showed perfect classification
- **Decision Boundary Plot** clearly separates the 3 iris classes

# What I Learned
- How KNN works using Euclidean distance
- Importance of **feature normalization** in distance-based algorithms
- How to choose the optimal **value of K**
- Visualizing classification regions in 2D
- Handling categorical labels with `LabelEncoder`
