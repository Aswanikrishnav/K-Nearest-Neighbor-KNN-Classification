# K-Nearest-Neighbor-KNN-Classification



This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**.  
The goal is to understand how KNN works, experiment with different values of `k`, evaluate performance, and visualize decision boundaries.

---

## 📌 Objective
- Learn how to use KNN for classification.
- Compare accuracy for different values of `k`.
- Evaluate performance using accuracy and confusion matrix.
- Visualize decision boundaries for better understanding.

---

## ⚙️ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📂 Steps in the Project
1. **Load Dataset**  
   Used `load_iris()` from `scikit-learn.datasets`.

2. **Preprocess Data**  
   - Normalize features with `StandardScaler`.  
   - Split data into training and testing sets.

3. **KNN Model**  
   - Implemented with `KNeighborsClassifier` from `sklearn.neighbors`.  
   - Trained the model with different `k` values (1–10).  

4. **Model Evaluation**  
   - Accuracy score using `accuracy_score`.  
   - Confusion matrix with `ConfusionMatrixDisplay`.

5. **Decision Boundaries Visualization**  
   - Selected 2 features (sepal length & sepal width).  
   - Used a meshgrid to plot regions classified by KNN.  
   - Overlaid test points on the decision regions.

---

## 📊 Results
- Accuracy changes with different values of `k`.  
- The best `k` was chosen based on the highest accuracy.  
- Decision boundary plots show how KNN separates classes in 2D space.

---


