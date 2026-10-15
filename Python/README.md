# 🐍 Python for Data Science

## 📌 About This Repository

Welcome to my **Python for Data Science** repository! This repository contains my learning notes, practice programs, examples, and exercises covering Python fundamentals and essential data science libraries.

The goal of this repository is to build a strong foundation in Python programming, data manipulation, numerical computing, and data visualization as part of my journey toward becoming a Data Scientist.

## 🎯 Learning Objectives

- Understand Python fundamentals and programming concepts.
- Perform numerical operations using NumPy.
- Clean, manipulate, and analyze datasets using Pandas.
- Create charts and visualizations using Matplotlib.
- Explore statistical data visualization using Seaborn.
- Develop practical skills for Exploratory Data Analysis (EDA).

## 🛠️ Technologies & Libraries

| Technology | Description |
|---|---|
| Python | Programming fundamentals and problem-solving |
| NumPy | Numerical computing and array operations |
| Pandas | Data cleaning, manipulation, and analysis |
| Matplotlib | Data visualization and chart creation |
| Seaborn | Statistical visualization and data exploration |
| Jupyter Notebook | Interactive coding and documentation |

## 📚 Topics Covered

### 1. Python Basics 🐍

- Variables and data types
- Operators and expressions
- Strings and string methods
- Lists, tuples, sets, and dictionaries
- Conditional statements (`if`, `elif`, `else`)
- Loops (`for` and `while`)
- Functions and lambda expressions
- List comprehensions
- Exception handling
- File handling
- Basic object-oriented programming

### 2. NumPy 🔢

- Creating and working with arrays
- Array indexing and slicing
- Array dimensions and shapes
- Reshaping and flattening arrays
- Mathematical and statistical operations
- Broadcasting
- Array filtering and sorting
- Random number generation
- Aggregation functions such as `sum()`, `mean()`, `min()`, and `max()`

### 3. Pandas 🐼

- Creating Series and DataFrames
- Importing CSV and Excel files
- Exploring datasets using `head()`, `info()`, and `describe()`
- Selecting rows and columns
- Filtering and sorting data
- Handling missing values
- Removing duplicate records
- Renaming columns
- Data type conversion
- Grouping and aggregation using `groupby()`
- Combining datasets using `merge()`, `join()`, and `concat()`
- Working with dates and text data
- Exporting processed datasets

### 4. Matplotlib 📊

- Creating line charts
- Bar charts and horizontal bar charts
- Histograms
- Scatter plots
- Pie charts
- Adding chart titles and axis labels
- Legends, markers, and grid lines
- Customizing figure size and layout
- Saving visualizations

### 5. Seaborn 📈

- Statistical data visualization
- Count plots
- Bar plots
- Histograms and distribution plots
- Box plots and violin plots
- Scatter plots and pair plots
- Heatmaps
- Correlation analysis
- Categorical data visualization
- Customizing plot styles and themes

## 📂 Repository Structure

```text
Python-for-Data-Science/
│
├── Python_Basics/
│   └── python_fundamentals.ipynb
│
├── NumPy/
│   └── numpy_practice.ipynb
│
├── Pandas/
│   └── pandas_practice.ipynb
│
├── Matplotlib/
│   └── matplotlib_visualization.ipynb
│
├── Seaborn/
│   └── seaborn_visualization.ipynb
│
├── Datasets/
│   └── sample_data.csv
│
└── README.md
```

*The structure above is a suggested organization. Adjust the filenames and folders to match the notebooks you actually upload.*

## ⚙️ Installation and Setup

### Step 1: Install Python

Download Python from the official website:

https://www.python.org/downloads/

### Step 2: Install the Required Libraries

Run the following command in your terminal:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Step 3: Clone This Repository

```bash
git clone https://github.com/YOUR-USERNAME/Python-for-Data-Science.git
```

### Step 4: Open the Project

```bash
cd Python-for-Data-Science
jupyter notebook
```

Open the notebook you want to explore and execute the cells step by step.

## 💻 Example: Data Analysis with Pandas

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Create a sample dataset
data = {
    "Name": ["Amit", "Riya", "Rahul", "Priya"],
    "Age": [22, 24, 23, 25],
    "Score": [85, 92, 78, 95]
}

df = pd.DataFrame(data)

# Display the dataset
print(df)

# Calculate summary statistics
print(df.describe())

# Visualize scores
sns.barplot(data=df, x="Name", y="Score")
plt.title("Scores by Student")
plt.xlabel("Student")
plt.ylabel("Score")
plt.tight_layout()
plt.show()
```

## 🚀 Skills Developed

- Python programming
- Numerical computing
- Data manipulation and cleaning
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Data visualization
- Problem-solving and analytical thinking
- Jupyter Notebook workflows

## 📌 Learning Progress

- [ ] Python Basics
- [ ] NumPy
- [ ] Pandas
- [ ] Matplotlib
- [ ] Seaborn
- [ ] Mini Data Analysis Projects

## 🎯 Future Goals

- Practice Python coding problems regularly.
- Work with real-world datasets.
- Perform end-to-end EDA projects.
- Build interactive dashboards using Power BI.
- Apply Python skills to Machine Learning and AI projects.

## 👨‍💻 About Me

I am an **Aspiring Data Scientist** pursuing Data Science with AI/ML. I am continuously developing my technical skills in Python, data analysis, visualization, SQL, and business intelligence.

🔗 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/sibaprasad-sahoo-6595a3419/)

---

⭐ If you find this repository useful, consider giving it a star!

*Learning step by step, practicing consistently, and building a strong foundation in Data Science.*

