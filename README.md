# Rocks-and-Mines

 # 🌊 Rock vs Mine Classification using Logistic Regression

This project uses a supervised machine learning approach to classify sonar signals as either **Rock (R)** or **Mine (M)** based on 60 numeric features derived from sonar signals.

## 📊 Dataset
- Each instance contains 60 features (numerical values from sonar returns)
- Target label:
  - `R` = Rock
  - `M` = Mine

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Google Colab

## 🧠 Model Used
- **Logistic Regression**
- Evaluation: Accuracy on both training and test sets

## ✅ Workflow
1. Load and inspect the dataset
2. Analyze class distribution
3. Split the dataset (90% training, 10% testing)
4. Train Logistic Regression model
5. Predict and evaluate with accuracy score
6. Predict object class for custom input data

## 📈 Results
- Training Accuracy: `0.8342245989304813%`
- Test Accuracy: ` 0.7619047619047619%`

## 💡 Future Enhancements
- Try other classification algorithms (SVM, KNN, Random Forest)
- Feature scaling and PCA
- Model performance metrics: Confusion matrix, ROC-AUC
- Deploy using Streamlit or Flask

## 📁 Files
- `sonar_classification.ipynb`: Main Colab notebook
- `README.md`: Project description

