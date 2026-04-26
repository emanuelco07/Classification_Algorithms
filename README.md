# Classification Algorithms: Teenager Mental Health Analysis 

This repository contains a comprehensive study and implementation of various **Machine Learning Classification Algorithms** as part of the 3rd-year Computer Science curriculum at the **"Petrol – Gaze" University of Ploiești**.

The project focuses on predicting and analyzing symptoms of depression among teenagers based on their lifestyle, social media usage, and academic performance.

---

## Project Overview
The primary goal is to build and evaluate predictive models capable of classifying whether an adolescent presents symptoms of depression (`depression_label`). The analysis explores factors such as:
*   **Daily Social Media Hours** & **Platform Usage**
*   **Sleep Quality** & **Screen Time before sleep**
*   **Academic Performance** (GPA)
*   **Physical Activity** & **Social Interaction Levels**

---

## Models Implemented
The following classification architectures were implemented using `scikit-learn`, featuring rigorous evaluation through **K-Fold Cross Validation**:

1.  **Perceptron**: A linear baseline model for binary classification.
2.  **Naive Bayes (Gaussian)**: A probabilistic approach based on Bayes' Theorem.
3.  **K-Nearest Neighbors (KNN)**: A distance-based "lazy learning" algorithm.
4.  **Support Vector Machine (SVM)**: Utilizing RBF and Linear kernels for optimal hyper-plane separation.
5.  **Decision Trees**: Providing interpretable decision rules for diagnostic logic.

---

## Methodology & Evaluation
To ensure the reliability of the results, the following metrics and techniques were applied:
*   **K-Fold Cross Validation**: Data was split into multiple folds to ensure model stability.
*   **Statistical Metrics**: Models were compared based on **Accuracy**, **Precision**, **Recall**, and **F1-Score**.
*   **Visualization**: Confusion Matrices and "Real vs. Predicted" plots are provided for each experiment.
*   **Feature Scaling**: Implemented `StandardScaler` to normalize numerical ranges.

---

## Repository Structure
*   `data/`: Contains the `Teen_Mental_Health_Dataset.csv`.
*   `notebooks/` or `scripts/`: Python implementation of the 5 classification models.
*   `docs/`: Detailed project documentation (PDF/Word) including experimental logs and conclusions.

---

## Further Documentation
For an in-depth analysis of the experiments, detailed parameter tuning for each model, statistical comparison tables, and final conclusions, **please refer to the full project documentation available in this repository.**

**[Access the Full Documentation Here](Algoritmi_de_clasificare.pdf)** 

---

## Technologies Used
*   **Language**: Python 3.x
*   **Libraries**: 
    *   `pandas` (Data manipulation)
    *   `numpy` (Numerical computation)
    *   `scikit-learn` (Machine Learning models & evaluation)
    *   `matplotlib` / `seaborn` (Data visualization)

---

## Author
**Emanuel Coșereanu**  
*Computer Science Student (Year 3, Group 40322)*  
Universitatea „Petrol – Gaze” din Ploiești

***

### How to use this for your Git:
1.  Go to your GitHub repository.
2.  Click on **Add file** -> **Create new file**.
3.  Name it `README.md`.
4.  Paste the text above.
5.  Commit the changes! 
