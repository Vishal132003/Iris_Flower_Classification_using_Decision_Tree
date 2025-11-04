# 🌸 Iris Flower Classification using Decision Tree

This project focuses on classifying iris flowers into their respective species using a **Decision Tree Classifier**.  
It’s a simple and effective way to understand how decision trees can be used for classification problems in machine learning.

---

## 📘 Project Overview

The **Iris dataset** contains measurements of iris flowers belonging to three species:
- Setosa  
- Versicolor  
- Virginica  

Each sample has four numerical features:
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

The goal is to predict the flower species based on these measurements.

---

## 📊 About the Dataset

- Total samples: 150  
- Features: 4  
- Classes: 3 (Setosa, Versicolor, Virginica)  
- Source: Built-in Scikit-learn dataset  
  [Scikit-learn Iris Dataset]:-https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-dataset

---

## 🧰 Tools and Libraries Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

These libraries are used for data handling, visualization, model training, and evaluation.

---

## ⚙️ Steps Followed

1. **Import Libraries**  
   Import all required libraries.

2. **Load Dataset**  
   Load the Iris dataset using Scikit-learn.

3. **Data Splitting**  
   Split the data into training and testing sets (80% training, 20% testing).

4. **Model Training**  
   Train the Decision Tree Classifier using the “entropy” criterion.

5. **Prediction**  
   Make predictions on the test dataset.

6. **Evaluation**  
   Measure the model’s accuracy and generate a classification report.

7. **Visualization**  
   Visualize the trained decision tree using Matplotlib.

---

## 🤖 Model Details

- **Algorithm:** Decision Tree Classifier  
- **Criterion:** Entropy  
- **Test Size:** 20%  
- **Random State:** 42  
- **Accuracy:** 100%

---

## 🔍 Example Prediction

```python
new_data = [[5.1, 3.5, 1.4, 0.2]]
prediction = model.predict(new_data)
print("Predicted Flower Type:", iris.target_names[prediction][0])
