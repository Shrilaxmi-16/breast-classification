# Breast Cancer Classification Using Machine Learning with Streamlit
- Please click the Streamlit Link [here](https://breast-cancer-classification-with-app-demo.streamlit.app/) to interact with the App.

<img src="https://raw.githubusercontent.com/WangHuangHan/Breast-Cancer-Classification-with-Streamlit/main/images/SS%20from%20Streamlit%20Deployment1.png" width="800">

## Description
This project focuses on the classification of breast tumors as either Malignant or Benign using various machine-learning algorithms such as KNN, Logistic Regression, and Random Forest. Leveraging a dataset containing comprehensive tumor metrics such as radius, texture, perimeter, area, smoothness, and more, we aim to build robust models for accurate tumor classification.

## Dataset
- [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

The dataset comprises tumor characteristics such as radius, texture, perimeter, and other measurable features extracted from breast cancer images. These attributes serve as crucial inputs for training and testing the classification models.

Final project for the **WQD7003 | Data Analytics** course at the University of Malaya

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1R4VJCcRQwdd3IrBQzCjC_gFgU50uI9b7?usp=sharing)

Team members:

- [Huang Han Wang](https://www.linkedin.com/in/huang-han-harry-wang-517386a8/)
- [Shuangdan Ni](https://www.linkedin.com/in/%E5%8F%8C%E4%B8%B9-%E5%80%AA-bb561426a/)
- Xinrui Guo
- Ding Jie
- Naxin Dong

Instructor: [Dr. Hema Subramaniam](https://scholar.google.com/citations?user=JFphXI0AAAAJ&hl=en)

## Project objectives
- To perform preprocessing and exploratory analysis on the dataset.
- To build the classification model to judge whether the tumor type is malignant or benign.
- To compare the advantages and disadvantages of different classification algorithms based on evaluation metrics.
- To fine-tune and optimize the hyperparameters and improve the accuracy, stability, and execution speed of the tumor-type judgment model.

## Infographics of this Project
<img src="https://raw.githubusercontent.com/WangHuangHan/Breast-Cancer-Classification-with-Streamlit/main/images/Breast%20Cancer%20Diagnosis.png" width="900">

## Streamlit Breast Cancer Detection App Explanation ([Link](https://breast-cancer-classification-with-app-demo.streamlit.app/))
**Important Note:** Please refer to this file [breast_cancer_app.py](https://raw.githubusercontent.com/WangHuangHan/Breast-Cancer-Classification-with-Streamlit/main/breast_cancer_app.py).

### Section 1: Importing Libraries

The initial part involves importing the necessary libraries and modules required for the application. These include libraries for data manipulation (`pandas`, `numpy`), visualization (`seaborn`, `matplotlib`, `plotly`), machine learning models (`sklearn`), and the Streamlit framework (`streamlit`).

---

### Section 2: Define Main Function

The `main()` function sets up the Streamlit app's layout, title, and initial configurations like page icon, title, and sidebar title.

---

### Section 3: Data Loading and Processing Functions

- `load_data()`: Loads the Breast Cancer dataset using `load_breast_cancer()` from `sklearn`, processes it into a DataFrame, and performs label encoding.
  
- `split(df)`: Splits the dataset into training and testing sets using `train_test_split()` from `sklearn`.

---

### Section 4: Data Analysis Section

This part handles the visualizations and displays for the data analysis section of the app. It includes:
- Displaying raw data and features
- Generating different types of plots based on user selection (scatter matrix, counts of malignant and benign cases, heatmap, scatter plots)

---

### Section 5: Prediction Section

This section allows users to select different classifiers (Logistic Regression, Random Forest, KNN) and their hyperparameters, then displays metrics such as accuracy, precision, recall, and confusion matrices for the chosen classifier.

The workflow includes:
- Choosing a classifier from the sidebar
- Selecting hyperparameters for the chosen classifier
- Displaying classification results and metrics based on user selections

---

### Section 6: About Section

At the sidebar's bottom, information about the app creator and a reference to the app's GitHub repository are provided.


