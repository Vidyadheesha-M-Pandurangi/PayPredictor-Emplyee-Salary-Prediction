
# 💼 PayPredictor – Employee Salary Prediction using Machine Learning Algorithms

A Streamlit-based web application that predicts whether an employee's salary exceeds $50K/year based on various demographic and employment features. This project evaluates multiple machine learning models and deploys the best one for public use.

## 🔗 GitHub Repository

[PayPredictor – Employee Salary Prediction](https://github.com/Vidyadheesha-M-Pandurangi/PayPredictor-Emplyee-Salary-Prediction.git)

---

## 🔗 Website URL

[🌐 PayPredictor](https://paypredictorai.streamlit.app/)

---


## 📌 Overview

**PayPredictor** is an intelligent machine learning system designed to predict an individual's income class (`>50K` or `<=50K`) based on input features such as age, education, occupation, and working hours. The model is trained on the UCI Adult dataset and deployed using **Streamlit Cloud**.

---

## 🎯 Objectives

- Build and train classification models for salary prediction.
- Compare multiple algorithms to identify the best performer.
- Deploy the best model with a user-friendly web interface.

---

## 📊 Algorithms Used

The following machine learning algorithms were trained and evaluated:

- **CatBoostClassifier**  
  > Gradient boosting on decision trees with built-in handling of categorical features.  
  ✅ *Best performing model in this project.*

- **LightGBMClassifier**  
  > Fast and efficient gradient boosting framework by Microsoft.

- **Quadratic Discriminant Analysis (QDA)**  
  > A generative probabilistic model with Gaussian assumptions.

- **ExtraTreesClassifier**  
  > An ensemble learning method based on randomized decision trees.

---

## 🧪 Evaluation Metrics

- **Train-Test Split:** 80% Training / 20% Testing  
- **Metric Used:** Accuracy Score

**Best Performance:**  
✔️ CatBoostClassifier with ~**84.13% Accuracy**
---

## 📁 Dataset

- **Source:** [UCI Machine Learning Repository – Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- **Attributes used:**

  - age
  - workclass
  - fnlwgt
  - education
  - educational-num
  - marital-status
  - occupation
  - relationship
  - race
  - gender
  - capital-gain
  - capital-loss
  - hours-per-week
  - native-country
  - income (target)

---

## 🏗️ Project Structure

```bash
PayPredictor/
│
├── PayPredictor.py         # Streamlit application code
├── best_model.pkl          # Trained model (CatBoost)
├── Code_for_the_Project.ipynb    # Code for data analysis, training, and evaluation
├── Dataset.csv             # Training dataset
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
└── Project Report.pdf          # Project Report
└── Snaps of Result         # Snaps of Result
```

---

## 🖥️ Streamlit App Features

- Clean user interface with input sliders and dropdowns
- Real-time prediction of income class
- Success message for output
- Centered prediction button for aesthetics

---

## 🚀 Deployment

### 🌐 Streamlit Cloud Deployment

1. Push the project to GitHub.
2. Visit [https://streamlit.io/cloud](https://streamlit.io/cloud).
3. Click **New App** and connect your GitHub repo.
4. Set **entry point** to `app.py`.
5. Ensure `requirements.txt` is present.
6. Click **Deploy** and run the app in the browser.

---

## 📷 Suggested Screenshots (for Project Report)

- Dataset preview (first few rows)
- Boxplot showing outlier removal
- Correlation heatmap (optional)
- Accuracy comparison bar chart
- Streamlit app input form
- Final prediction output screen

---

## 🔮 Future Scope

- Expand the dataset with more real-world entries.
- Apply **cross-validation** and **Optuna/GridSearchCV** for hyperparameter tuning.
- Integrate SHAP/LIME for model explainability.
- Improve UI with visualization elements.
- Add database to store predictions.
- Deploy on scalable platforms like **AWS**, **GCP**, or **Azure**.
- Export prediction results as downloadable PDF.

---

## 📚 References

- [CatBoost Docs](https://catboost.ai/en/docs/)
- [LightGBM Docs](https://lightgbm.readthedocs.io/)
- [QDA – Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.QuadraticDiscriminantAnalysis.html)
- [Extra Trees – Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesClassifier.html)
- [Streamlit Docs](https://docs.streamlit.io/)
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Docs](https://matplotlib.org/stable/index.html)
- [Numpy Docs](https://numpy.org/doc)
- [Joblib Docs](https://joblib.readthedocs.io/en/latest)
---

## 👨‍💻 Author

**Vidyadheesha M. Pandurangi**  
🎓 Electronics and Communication Engineering  
📍 India  
🔗 [GitHub Profile](https://github.com/Vidyadheesha-M-Pandurangi)

