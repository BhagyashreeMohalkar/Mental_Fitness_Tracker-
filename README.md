# 🧠 Mental Fitness Tracker using Machine Learning

This project analyzes mental health and substance use disorder data across countries and years to predict **mental fitness levels** using machine learning models. Built as part of the IBM Internship Projects, the system uses **Linear Regression** and **Random Forest Regressor** to understand and forecast mental health trends.

---

## 📌 Overview

- 📈 Predicts the level of mental fitness based on global mental health disorder data.
- 🌍 Works with country-wise and year-wise public health datasets.
- 🗂️ Merges and processes two comprehensive CSV files.
- 📊 Visualizes patterns using interactive and static plots.
- 🤖 Implements and compares multiple machine learning regression models.

---

## ✨ Features

- 📊 Data visualization using **Seaborn**, **Matplotlib**, and **Plotly**
- 🧹 Feature encoding and preprocessing with **Label Encoding**
- 🤖 Machine Learning with **Scikit-learn**
- 📈 Evaluation using **MSE**, **RMSE**, and **R² Score**
- 🔁 Comparison of **Linear Regression** and **Random Forest Regressor**

---

## 🛠️ Requirements

Make sure Python 3.7+ is installed.

### 📦 Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `plotly`
- `scikit-learn`

Install them using:

```bash
pip install -r requirements.txt
```

---

## ⚙️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/BhagyashreeMohalkar/mental-fitness-tracker.git
cd mental-fitness-tracker
```

2. **Add Dataset Files** to the root directory:

- `prevalence-by-mental-and-substance-use-disorder _AI.csv`
- `mental-and-substance-use-as-share-of-disease -AI.csv`

3. **Run the Jupyter Notebook**

```bash
jupyter notebook Mental_Fitness_Tracker.ipynb
```

---

## 📁 Dataset

These datasets provide yearly, country-wise data for various mental disorders:

- 📄 `prevalence-by-mental-and-substance-use-disorder _AI.csv`
- 📄 `mental-and-substance-use-as-share-of-disease -AI.csv`

📌 They include attributes like:
- Schizophrenia
- Bipolar Disorder
- Eating Disorders
- Anxiety
- Drug/Alcohol Use
- Depression
- Country, Year

---

## 🔄 Project Workflow

1. 📥 **Data Loading and Merging**  
   - Combined datasets using pandas.

2. 🧼 **Data Cleaning & Preprocessing**  
   - Renamed columns and encoded categorical features.

3. 📊 **Exploratory Data Analysis**  
   - Used heatmaps, pie charts, and time-series graphs to analyze trends.

4. 🔍 **Feature Engineering**  
   - Selected key predictors of mental fitness.

5. 🧠 **Model Training**  
   - Trained and compared Linear Regression and Random Forest Regressor models.

6. 📊 **Model Evaluation**  
   - Assessed models using MSE, RMSE, and R² scores on both training and test sets.

---

## 🚀 Usage

Run the main project file using:

```bash
jupyter notebook Mental_Fitness_Tracker.ipynb
```

You’ll see:
- 📊 Visualizations of trends across years/countries.
- 🤖 Model training outputs.
- 📈 Evaluation results of both models.

---

## 📌 Future Scope

- 🔍 Integrate more mental health indicators (e.g., suicide rate, GDP impact).
- 💡 Build a prediction web app using Flask or Streamlit.
- 🔁 Deploy the model with real-time monitoring features.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author

**Bhagyashree Mohalkar**   
🌐 [GitHub](https://github.com/BhagyashreeMohalkar) | [LinkedIn](https://www.linkedin.com/in/bhagyashree-mohalkar)

> *Empowering insights into mental health through data and AI.* 🌍💡
