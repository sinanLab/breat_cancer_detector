# breat_cancer_detector
This repository contains the code how the model has trained and deployed

## Table to show the comparison between FineTuned model and baseline
| Model                   | Accuracy | Precision (Malignant) | Recall (Malignant) | F1-Score (Malignant) | Comments                                                               |
| ----------------------- | -------- | --------------------- | ------------------ | -------------------- | ---------------------------------------------------------------------- |
| **Tuned Random Forest** | 0.9737   | 1.0000                | 0.9048             | 0.9500               | Highest accuracy and F1; tuning improved generalization slightly.      |
| Random Forest           | 0.9649   | 1.0000                | 0.9048             | 0.9500               | Very strong by default; tuning only slightly improved performance.     |
| Logistic Regression     | 0.9386   | 0.9730                | 0.8571             | 0.9114               | Performs well, interpretable, slightly lower recall.                   |
| Decision Tree           | 0.9211   | 0.9231                | 0.8571             | 0.8889               | Good but prone to overfitting; tuning helps.                           |
| K-Nearest Neighbors     | 0.9123   | 0.9706                | 0.7857             | 0.8684               | High precision, lower recall; may miss malignant cases.                |
| Support Vector Machine  | 0.9035   | 1.0000                | 0.7381             | 0.8493               | Perfect precision but low recall; too conservative in malignant class. |


## Bar graph of the comparison between baseline and best model 
![bar_graph_breast_cancer_model_comparison](https://github.com/user-attachments/assets/0551c306-b6ca-40ff-97a3-f5b45cc4a47e)

## Feature importance
![feature_importances_breast_cancer_tuned_rf](https://github.com/user-attachments/assets/72f7c786-1519-46ff-b583-185ff5035c32)

## deployment using tkinter
![image](https://github.com/user-attachments/assets/d794f0cd-6e58-4e8d-9366-12a63fdc550e)
