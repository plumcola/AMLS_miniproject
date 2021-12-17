# AMLS_miniproject

## Introduction of the tasks
Hello! Here are two main tasks: binary tumor image classification and 4-class tumor image classification based on supervised learning.

Task A. Binary classification
This task is divided into 2 parts: CNN model and SVM model.

Task B. Multiclass classification
This task is implemented by only CNN model.

## File organization

<<README.md

<<pure_code
<<<<task_a.py
<<<<task_b.py

<<runned_code
<<<<task_A.ipynb
<<<<task_B.ipynb

<<dataset
<<<<image
<<<<label.csv

<<dataset_after_preproccessing
<<<<image
<<<<yes
<<<<no
<<<<glioma_tumor
<<<<meningioma_tumor
<<<<pituitary_tumor
<<<<label.csv

<<test
<<<<image
<<<<label.csv

## How to run the code
To run the pure code, please do:
1. Use Google Colab Pro with configuration: high RAM and GPU
2. Create a folder in your Google Drive named: AMLS
3. Upload the original dataset and test folder to this AMLS folder
4. Create five new empty folders in this AMLS folder: yes, no, glioma_tumor, meningioma_tumor, pituitary_tumor
5. And then run the code in Google Colab

## Necessary packages
os, shutil, pandas, keras, numpy, tensorflow, opencv, scikit-learn (actually all of them are in Google Colab)
