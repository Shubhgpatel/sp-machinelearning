# 🤖 PenguinPredictor App


This is a fun machine learning project built using **Streamlit** to predict the species of penguins based on physical characteristics. It helped me gain hands-on experience in deploying ML models with interactive UIs.

---

## 🚀 Demo App

Experience the live version of this machine learning app built using Streamlit:

👉 [🪄 Open in Streamlit](https://sp-machinelearning.streamlit.app/#c6b76bd7)



## ⚙️ How It Works

This app predicts the **species** of a penguin (Adelie, Chinstrap, or Gentoo) based on user inputs:

- **Island**
- **Bill Length (mm)**
- **Bill Depth (mm)**
- **Flipper Length (mm)**
- **Body Mass (g)**
- **Gender**

### 🧠 Machine Learning Pipeline

1. **Dataset**: Loaded from the cleaned [Palmer Penguins dataset](https://github.com/dataprofessor/data/blob/master/penguins_cleaned.csv).
2. **Feature Engineering**: Encoded categorical features using `pd.get_dummies()`.
3. **Model**: Trained a `RandomForestClassifier` from scikit-learn.
4. **Prediction**: Based on sidebar inputs, a new penguin is added to the dataset and classified.
5. **Output**: Shows predicted probabilities and the final predicted species using `st.dataframe()` and `st.success()`.

---

## 📊 Features

- Live prediction with sliders and dropdowns.
- Data visualization using Streamlit's built-in charts.
- Progress bars for prediction probabilities.
- Data exploration via expandable sections.

---

## 🛠️ Tech Stack

- Python 🐍
- Streamlit 🌐
- Pandas, NumPy, scikit-learn 📦

---


