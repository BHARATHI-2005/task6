Task 6: K-Nearest Neighbors (KNN) Classification

Objective
To understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**. This task is part of the AI & ML Internship program.

Dataset
- Name:Iris Dataset
- Features:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- Target:Species (Setosa, Versicolor, Virginica)

Tools Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn (optional)
- PCA (for visualization)

Steps Performed

1. Loaded-the dataset from `Iris.csv` and removed unnecessary columns like `Id`.
2. Encoded-the target class labels (`Species`) into numeric format.
3. Normalized-the features using `StandardScaler`.
4. Split-the dataset into training and testing sets (80-20 split).
5. Implemented-KNN using `KNeighborsClassifier` from `sklearn`.
6. Tested-different values of K (from 1 to 20) to find the best performance.
7. Evaluated-the best model using:
   - Accuracy
   - Confusion Matrix
8. Visualized-the decision boundary using PCA for 2D plotting.
   
Results

- Best K value:`3`
- Test Accuracy:`~96.67%`
