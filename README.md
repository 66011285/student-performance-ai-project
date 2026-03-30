# AI-Based Student Performance Prediction

## 📌 Project Overview
This project uses machine learning to predict students' final grades (G3) based on academic and behavioral data.

## 📊 Dataset
- Source: UCI Student Performance Dataset
- File: student-mat.csv
- Records: 395 students
- Features: 33 variables including study time, absences, and previous grades

## 🧠 Methodology
The project follows a data science workflow:

1. Data loading and preprocessing
2. Exploratory data analysis (EDA)
3. Data visualization
4. Model training using Linear Regression
5. Performance evaluation

## 🤖 Machine Learning Model
- Algorithm: Linear Regression
- Features used:
  - studytime
  - failures
  - absences
  - G1 (first period grade)
  - G2 (second period grade)
- Target:
  - G3 (final grade)

## 📈 Results
- R² Score: 0.78
- Mean Absolute Error: 1.34

The model demonstrates strong predictive performance.

## 📷 Visualizations
The project includes:
- Grade distribution histogram
- Correlation heatmap
- Scatter plot (G2 vs G3)

## 🚀 Tools Used
- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📂 Files
- `student_performance_prediction.ipynb` → main notebook
- `student-mat.csv` → dataset

## 🎯 Conclusion
The model successfully predicts student performance and shows that previous grades are strong indicators of final outcomes.

## 🔗 Author
Vadhanasvas Svastivatana Na Ayudhaya 66011285
