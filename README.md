# Binary-Classificationn-using-KNN
Build KNN based classification model from scratch to be trained on a given  dataset and recommend the best value for K (number of neighbors) and  distance matrix that produces the highest accuracy for test data.

---

## 📊 Dataset Description
The dataset (`data.csv`) contains measurements from a digitized image of a breast mass.

### 🎯 Target Variable
- **Diagnosis**
  - `M` → Malignant
  - `B` → Benign

### 🔢 Independent Variables (Features)
1. Radius_mean  
2. Texture_mean  
3. Perimeter_mean  
4. Area_mean  
5. Smoothness_mean  
6. Compactness_mean  
7. Concavity_mean  
8. Concavepoints_mean  
9. Symmetry_mean  
10. Fractal_dimension_mean  
11. Radius_se  
12. Texture_se  
13. Perimeter_se  
14. Area_se  
15. Smoothness_se  
16. Compactness_se  
17. Concavity_se  
18. Concavepoints_se  
19. Symmetry_se  
20. Fractal_dimension_se  
21. Radius_worst  
22. Texture_worst  
23. Perimeter_worst  
24. Area_worst  
25. Smoothness_worst  
26. Compactness_worst  
27. Concavity_worst  
28. Concavepoints_worst  
29. Symmetry_worst  
30. Fractal_dimension_worst  

---

## 🧠 Methodology
- The dataset is split into:
  - **80% Training data**
  - **20% Testing data**
- A **KNN classifier is implemented from scratch** (without using built-in KNN functions)
- The model is evaluated using various hyperparameter combinations

---

## ⚙️ Hyperparameters Tested

### 🔹 Values of K
  3, 4, 9, 20, 47

### 🔹 Distance Metrics
- Euclidean Distance  
- Manhattan Distance  
- Minkowski Distance  
- Cosine Similarity  
- Hamming Distance  

---

## 📈 Evaluation Metrics
- **Accuracy** on test data
- **Confusion Matrix**
- **Precision**
- **Recall**

For the best-performing K and distance metric, all the above metrics are reported.

---

## 📉 Visualizations
- **Accuracy vs K** plots for different distance metrics
- Comparative analysis across distance measures
- **Decision boundary visualization** for the best KNN model (Bonus)

---

## 📌 Results & Inferences
- The best value of **K** and **distance metric** is selected based on maximum testing accuracy
- Performance trends across different K values are analyzed
- Observations and conclusions are discussed in detail in the project report

---

## ▶️ How to Run the Code
1. Clone or download the repository
2. Open `Task1_KNN.ipynb` using:
   - Google Colab **or**
   - Jupyter Notebook
3. Ensure `data.csv` is placed in the `data/` directory
4. Run all cells sequentially to reproduce results and plots

---

It includes:
- Problem formulation
- Algorithm explanation
- Experimental setup
- Results and plots
- Inferences and conclusions

---

## 🛠️ Tools & Technologies
- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Google Colab / Jupyter Notebook**
- **GitHub**


