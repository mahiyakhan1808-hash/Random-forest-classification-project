# 🌸 Iris Flower Classification Using Random Forest

This project demonstrates **Iris Flower Classification using the Random Forest Classifier** in Python. The Iris dataset from Scikit-learn is used to train and evaluate a machine learning classification model.

## 📌 Project Overview

The goal of this project is to classify Iris flowers into their respective classes based on four flower features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

A **Random Forest Classifier** is trained on the dataset and evaluated using test data.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Random Forest Classifier

## 📊 Dataset

The project uses the built-in **Iris dataset** available in Scikit-learn.

The dataset contains:

* 150 samples
* 4 input features
* 3 flower classes

## 🔄 Project Workflow

1. Import required Python libraries
2. Load the Iris dataset
3. Convert the dataset into a Pandas DataFrame
4. Separate features (`X`) and target (`y`)
5. Split the data into training and testing sets
6. Create a Random Forest Classifier
7. Train the model
8. Make predictions on test data
9. Evaluate the model using:

   * Confusion Matrix
   * Classification Report

## 🤖 Machine Learning Model

The project uses:

```python
RandomForestClassifier(
    n_estimators=10,
    max_depth=10,
    max_leaf_nodes=7
)
```

The model is trained using the training dataset and then used to predict the classes of the test dataset.

## 📈 Model Evaluation

The model performance is evaluated using:

### Confusion Matrix

The confusion matrix shows the number of correctly and incorrectly classified samples for each class.

### Classification Report

The classification report provides:

* Precision
* Recall
* F1-score
* Support

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### 2. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 3. Run the Python file

```bash
python 28_sept_rfc_2.py
```

## 📁 Project Structure

```text
📦 Iris-Random-Forest-Classification
 ├── 28_sept_rfc_2.py
 └── README.md
```

## 🎯 Key Learning

This project demonstrates how to:

* Load a built-in machine learning dataset
* Prepare data using Pandas
* Split data into training and testing sets
* Build a Random Forest classification model
* Make predictions
* Evaluate classification performance

## 👩‍💻 Author

**Mahiya Khan**

---

⭐ If you found this project useful, feel free to star t
