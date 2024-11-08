
# MNIST Digit Classification using K-Nearest Neighbors (KNN)

This is an **educational project** designed to demonstrate the implementation of the **K-Nearest Neighbors (KNN)** algorithm on the **MNIST dataset**. It is a simple, **beginner-friendly** project aimed at learning the basics of machine learning and classification tasks.

## Key Steps:

1. **Loading the Dataset**: 
   The MNIST dataset, which contains images of handwritten digits, is loaded using `fetch_openml`.

2. **Data Preprocessing**: 
   - The data is split into training and testing sets.
   - **Standardization** is applied to scale the pixel values using `StandardScaler` for better model performance.

3. **Model Training**: 
   - The **KNN classifier** is trained on the preprocessed data to classify the digits.

4. **Model Evaluation**:
   - The model is evaluated using **cross-validation**, and its performance is measured with **accuracy** and a **confusion matrix**.

5. **Saving the Model**:
   - After training, the model is saved using `joblib`, so it can be reused later without retraining.

I learned the concepts of machine learning by working on this project and implemented it myself. It focuses on classification using the K-Nearest Neighbors (KNN) algorithm, and through this, I gained hands-on experience with key tasks such as data loading, preprocessing, model training, and evaluation.

## Requirements:
To run the code, you need to install the following libraries:

```
pip install scikit-learn numpy matplotlib seaborn joblib
```

