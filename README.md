
# 🎓 Campus Placement Prediction Project

This project uses **machine learning** to predict whether a student will be placed based on academic performance and other personal attributes. Visualizations were created using **Tableau** to help interpret patterns in placement data.

---

## 📁 Project Structure

```
├── placement_prediction_project.pdf      # Final project report
├── placement_model.ipynb                 # Python ML notebook (Jupyter)
├── placement_predictions.csv             # Predicted outputs for Tableau
├── zfdsfxb.twb                           # Tableau dashboard file
├── README.md                             # Project summary
└── requirements.txt                      # Python packages used
```

---

## 🧠 Problem Statement

> Predict student campus placement outcomes using academic scores, experience, and specialization using supervised machine learning.

---

## 🛠️ Tools & Technologies

- **Python**: pandas, scikit-learn, seaborn, matplotlib
- **Jupyter Notebook**: For data cleaning, EDA, and modeling
- **Logistic Regression**: Best-performing ML model
- **Tableau**: For dashboard visualizations and storytelling
- **GitHub**: Version control and project publishing

---

## 🔍 Steps Followed

### ✅ Day 1: Dataset Setup
- Cleaned data, handled missing values
- Encoded categorical features using LabelEncoder

### ✅ Day 2: Exploratory Data Analysis (EDA)
- Analyzed relationships between academic scores and placement
- Visualized trends using boxplots and correlation heatmaps

### ✅ Day 3: Model Building
- Tried Logistic Regression, Decision Tree, Random Forest
- Logistic Regression achieved the best accuracy
- Evaluated using Accuracy, Confusion Matrix, ROC Curve

### ✅ Day 4: Tableau Dashboard
- Visualized actual vs predicted placements
- Built bar charts, pie charts, confusion matrix views
- Used filters like gender, specialization, degree type

### ✅ Day 5: Final Touches
- Exported predictions to CSV
- Uploaded Tableau workbook
- Documented project and published on GitHub

---

## 📊 Tableau Dashboard Highlights

- Placement success rate breakdown
- Analysis of academic score impact on placement
- Gender-wise and specialization-wise insights
- Confusion matrix of actual vs predicted outcomes

🧭 View Tableau workbook in: `zfdsfxb.twb`

---

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/campus-placement-prediction.git
   cd campus-placement-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run `placement_model.ipynb` in Jupyter Notebook.

---

## 📄 License

This project is for educational purposes and is open for contributions. Add enhancements or visualizations!

---

## 🙌 Acknowledgments

- Kaggle: Campus Placement Dataset
- Tableau Public
- Scikit-learn Documentation

---
