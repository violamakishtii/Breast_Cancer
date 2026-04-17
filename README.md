# Breast_Cancer

# Breast Cancer Classification using SVM

## 📌 Project Description
This project applies a Support Vector Machine (SVM) model to classify breast cancer tumors as malignant or benign using a dataset stored in `data.csv`.

## ⚙️ Steps Performed
1. Loaded dataset using pandas
2. Cleaned data (removed unnecessary columns, handled missing values)
3. Encoded target variable (M = 1, B = 0)
4. Split dataset into training and testing sets
5. Scaled features using StandardScaler
6. Trained SVM model (RBF kernel)
7. Evaluated performance using accuracy, confusion matrix, and classification report

## 🤖 Model Used
- Support Vector Machine (SVM)
- Kernel: RBF
- C = 1.0
- Gamma = scale

## 📊 Results
- Accuracy: ~97% (may vary slightly)
- Strong performance in detecting both malignant and benign cases

## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score

## 💡 Conclusion
The SVM model performed very well on this dataset. Feature scaling significantly improved performance, and the RBF kernel helped capture non-linear patterns in the data.

## 📂 File Structure
- data.csv → Dataset
- svm_breast_cancer.ipynb → Jupyter Notebook
