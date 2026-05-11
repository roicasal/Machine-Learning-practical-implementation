# Machine Learning Model Analysis in Biophysics

This repository contains the practical project developed for the **Biophysics** course, focusing on the implementation and comparison of different supervised learning algorithms for data classification and prediction.

##  Authors
* **Xandre Álvarez González**
* **Roi Casal Blanco**

##  Project Description
The main objective of this study is to evaluate the effectiveness of various **Machine Learning** models to predict outcomes based on a specific dataset. Each model's accuracy and generalization capabilities are analyzed using statistical and visual tools.

##  Implemented Models
The main Jupyter Notebook (`.ipynb`) explores and compares several architectures:
1. **Logistic Regression:** The top-performing model in this study, achieving an accuracy of approximately **87%**.
2. **Decision Trees:** Used to understand variable hierarchy, tuned with `max_depth=3` to prioritize interpretability and avoid overfitting.
3. **Model Evaluation:** Implementation of **Confusion Matrices** and performance metrics (Precision, Recall, F1-Score) to validate the results.

##  Technological Stack
* **Language:** Python 3
* **Main Libraries:**
  * `scikit-learn`: For model creation, training, and validation.
  * `pandas` & `numpy`: For data cleaning and manipulation.
  * `matplotlib` & `seaborn`: For generating confusion matrices and data visualization.

##  Key Results
* A peak accuracy of **86.9%** was achieved using Logistic Regression.
* Confusion matrices revealed that the models are highly effective at identifying specific classes within the dataset.
* The study demonstrates the trade-off between model complexity (e.g., tree depth) and final accuracy.

##  Repository Content
* `XandreAlvarezGonzalez_RoiCasalBlanco.ipynb`: Jupyter Notebook containing the full workflow (data import, cleaning, training, and evaluation).

---
*This project was completed as part of the [Your Degree, e.g., Physics/Biology] degree program at the University of Santiago de Compostela.*
