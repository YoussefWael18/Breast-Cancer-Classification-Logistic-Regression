#  Breast Cancer Tumor Classification (Logistic Regression)

This project applies **Logistic Regression** to classify breast tumors as **Malignant (M)** or **Benign (B)** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**.  
The dataset contains **569 samples** with **30 numerical features** computed from digitized images of fine needle aspirates (FNA).
---

## Acknowledgments
This project was built to practice **machine learning classification** techniques and to demonstrate an end-to-end ML pipeline on a real-world healthcare dataset.
---

##  Dataset
- Source: [Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Features: Cell nuclei characteristics (mean, standard error, and worst value for radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension).
- Target:
  - **M** → Malignant (cancerous)  
  - **B** → Benign (non-cancerous)

---

##  Model
- **Logistic Regression**  
- Data split: 75% training / 25% testing  
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, and Confusion Matrix  

---

## Results
- **Accuracy:** 95–98%  
- **Confusion Matrix:**  

|                | Predicted Malignant | Predicted Benign |
|----------------|---------------------|------------------|
| **Actual Malignant** | 86                  |  5               |
| **Actual Benign**    | 4                   | 48               |

- The model performs very well, with minimal misclassifications.  

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YoussefWael18/breast-cancer-logreg.git
   cd breast-cancer-logreg
