# 🌍 Global Happiness Analysis (Python Project)

## 📌 Project Overview

This project is a **menu-driven Python program** that analyzes the **World Happiness Dataset**. It allows users to explore data, visualize trends, and understand factors affecting happiness across countries.

---

## 🎯 Features

* 📂 Load dataset from CSV file
* 📊 Display first 5 rows of data
* 🏆 Show Top 10 happiest countries
* 📈 GDP vs Happiness scatter plot
* 🔥 Correlation heatmap visualization
* 🔁 Menu-driven interactive program

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**

---

## 📂 Dataset

* File Name: `happiness.csv`
* Make sure the dataset path is correctly set in the code:

```python
pd.read_csv("your_file_path/happiness.csv")
```

---

## ▶️ How to Run

### 1️⃣ Install Required Libraries

```bash
pip install pandas matplotlib seaborn
```

### 2️⃣ Run the Program

```bash
python main.py
```

---

## 🧭 Menu Options

When you run the program, you will see:

```
========== GLOBAL HAPPINESS ANALYSIS ==========
1. Load Dataset
2. Show First 5 Rows
3. Top 10 Happiest Countries
4. GDP vs Happiness Graph
5. Correlation Heatmap
6. Exit
```

---

## 📊 Output Details

### 📌 Top 10 Happiest Countries

* Displays top countries based on **Happiness Score**
* Shows a **bar chart visualization**

### 📈 GDP vs Happiness

* Scatter plot showing relationship between:

  * GDP per capita
  * Happiness Score

### 🔥 Correlation Heatmap

* Displays relationships between all numeric columns
* Helps identify important factors affecting happiness

---

## ⚠️ Error Handling

* Shows warning if dataset is not loaded
* Handles file not found error

---

## 🚀 Conclusion

This project helps in understanding how **economic and social factors** impact happiness. It provides a simple but powerful way to analyze real-world data using Python.

---

## 💡 Future Improvements

* Add more visualizations
* Use interactive dashboards (Streamlit)
* Add machine learning predictions
* Improve UI/UX

---

## 👨‍💻 Author

**Jiya Patel**
