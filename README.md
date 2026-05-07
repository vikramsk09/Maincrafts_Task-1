# 📊 Student Performance Data Analysis

This project focuses on analyzing students' academic performance using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.  
The analysis explores how factors like **study time** and **gender** affect students' final grades (`G3`) and visualizes insights using various charts and graphs.

---

# 🚀 Project Objectives

- Analyze students' final grades
- Study the relationship between study time and performance
- Compare average grades of male and female students
- Identify patterns and trends through data visualization
- Practice real-world data analysis using Python

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Dataset Information

The dataset contains information about students, including:

- Gender (`sex`)
- Study Time (`studytime`)
- Final Grade (`G3`)
- Other academic and personal attributes

The dataset was loaded from a CSV file and analyzed using Pandas.

---

# 📈 Analysis Performed

## ✅ Data Cleaning
- Loaded semicolon-separated CSV dataset
- Checked missing values
- Checked and removed duplicate rows

## ✅ Exploratory Data Analysis
- Analyzed distribution of final grades
- Compared study time with grades
- Compared male vs female average scores
- Calculated correlations between features

## ✅ Data Visualization
Created multiple visualizations including:

- Histograms
- Scatter Plots
- Bar Charts
- Correlation Heatmap

---

# 📊 Visualizations Included

## 📌 Histogram
Shows the distribution of students' final grades.

## 📌 Scatter Plot
Visualizes the relationship between:
- Study Time
- Final Grades (`G3`)

## 📌 Bar Chart
Compares average grades of:
- Male Students
- Female Students

## 📌 Heatmap
Displays correlations between numerical columns in the dataset.

---

# 📷 Sample Code

## Correlation Heatmap

```python
import seaborn as sns
import matplotlib.pyplot as plt

correlation = df.corr(numeric_only=True)

plt.figure(figsize=(12,8))
sns.heatmap(correlation, annot=True, cmap='coolwarm')

plt.show()
```

---

# 📌 Key Insights

- Students with higher study time generally performed better.
- Average grades differed slightly between male and female students.
- Data visualization helped identify patterns clearly and effectively.

---

# ▶️ How to Run the Project

1. Clone this repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells

---

# 📁 Project Structure

```bash
├── students.csv
├── Student_Performance_Analysis.ipynb
├── README.md
```

---

# 🎯 Learning Outcomes

Through this project, I learned:

- Data cleaning using Pandas
- Exploratory Data Analysis (EDA)
- Data visualization techniques
- Correlation analysis
- Working with real-world datasets

---

# 🤝 Contributing

Contributions, suggestions, and feedback are always welcome.

---

# ⭐ If You Like This Project

Please consider giving this repository a ⭐ on GitHub!

---

# 👨‍💻 Author

Vikram Kushwaha

```
