# 🚢 Titanic Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset** using Python and Jupyter Notebook.

The main goal of this project is to understand the Titanic passenger data, identify important patterns, analyze survival rates, and visualize relationships between different passenger attributes.

The analysis uses **Pandas** for data manipulation and **Matplotlib** for data visualization.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand the Titanic dataset.
* Explore the structure and characteristics of the data.
* Identify missing values and data-quality issues.
* Perform basic data cleaning.
* Generate descriptive statistics.
* Analyze passenger survival.
* Compare survival based on gender.
* Analyze survival based on passenger class.
* Explore the relationship between age and survival.
* Analyze fare and passenger characteristics.
* Create meaningful visualizations.
* Extract useful insights from the dataset.

---

## 🛠️ Technologies Used

| Technology          | Purpose                        |
| ------------------- | ------------------------------ |
| 🐍 Python           | Programming language           |
| 📓 Jupyter Notebook | Development environment        |
| 🐼 Pandas           | Data manipulation and analysis |
| 📊 Matplotlib       | Data visualization             |
| 📗 OpenPyXL         | Excel file support             |
| 🔢 NumPy            | Numerical operations           |

---

## 📂 Project Structure

```text
Titanic-Data-Analysis/
│
├── Titanic_Data_Analysis.ipynb
├── Titanic.csv
└── README.md
```

### Files Description

**`Titanic_Data_Analysis.ipynb`**

Contains the complete Python analysis, data exploration, calculations, and visualizations.

**`Titanic.csv`**

Contains the Titanic passenger dataset used for the analysis.

**`README.md`**

Contains the project documentation and instructions.

---

# 📊 Dataset

The Titanic dataset contains information about passengers who were aboard the Titanic.

The dataset includes attributes such as:

| Column        | Description                            |
| ------------- | -------------------------------------- |
| `PassengerId` | Unique passenger identification number |
| `Survived`    | Survival status                        |
| `Pclass`      | Passenger class                        |
| `Name`        | Passenger name                         |
| `Sex`         | Passenger gender                       |
| `Age`         | Passenger age                          |
| `SibSp`       | Number of siblings/spouses aboard      |
| `Parch`       | Number of parents/children aboard      |
| `Ticket`      | Ticket number                          |
| `Fare`        | Passenger fare                         |

---

# 🔍 Exploratory Data Analysis

The notebook performs several stages of data analysis.

## 1️⃣ Import Libraries

The project uses:

```python
import pandas as pd
import matplotlib.pyplot as plt
```

Pandas is used for data manipulation, while Matplotlib is used for creating visualizations.

---

## 2️⃣ Load the Dataset

The Titanic dataset is loaded using Pandas:

```python
df = pd.read_csv("Titanic.csv")
```

Using a relative path makes the project easier to run after downloading it from GitHub.

---

## 3️⃣ Data Inspection

The dataset is inspected to understand:

* Number of rows
* Number of columns
* Column names
* Data types
* Sample records
* Dataset structure

Example:

```python
df.head()
```

The notebook displays the passenger information and allows the dataset to be examined before further analysis.

---

## 4️⃣ Data Cleaning

The dataset is examined for potential data-quality issues, including:

* Missing values
* Incorrect data types
* Duplicate records
* Unnecessary columns
* Inconsistent values

Data cleaning is an important step before performing analysis.

---

# 📈 Data Analysis

The project analyzes different aspects of the Titanic dataset.

## 👥 Passenger Analysis

The dataset is explored to understand passenger characteristics such as:

* Gender
* Age
* Passenger class
* Fare
* Family relationships

---

## ⚓ Survival Analysis

The `Survived` column is analyzed to determine passenger survival.

The values represent:

```text
0 → Did not survive
1 → Survived
```

The analysis compares survival patterns across different passenger groups.

---

## 👩‍🦰 Gender-Based Analysis

Passenger survival is analyzed based on gender.

This helps identify differences in survival patterns between:

* Male passengers
* Female passengers

---

## 🎫 Passenger Class Analysis

The Titanic dataset contains three passenger classes:

```text
1 → First Class
2 → Second Class
3 → Third Class
```

The project examines how passenger class relates to survival.

---

## 🎂 Age Analysis

Passenger ages are analyzed to understand:

* Age distribution
* Average passenger age
* Age-related survival patterns
* Differences between passenger groups

---

## 💰 Fare Analysis

Passenger fares are also explored.

The analysis helps understand the relationship between:

* Fare
* Passenger class
* Survival

---

# 📊 Visualizations

The project uses **Matplotlib** to create visual representations of the Titanic data.

The notebook includes visual analysis for different passenger characteristics and survival patterns.

Examples of possible visualizations include:

* 📊 Survival count charts
* 👩‍🦰 Gender distribution
* 🎫 Passenger-class distribution
* 📈 Age distribution
* 💰 Fare analysis
* ⚓ Survival comparison
* 📊 Categorical comparisons

Visualizations make it easier to identify patterns and trends in the dataset.

---

# 💡 Key Insights

The analysis helps understand important relationships within the Titanic dataset.

Some of the major areas explored include:

### 👩 Gender and Survival

Survival patterns differ between male and female passengers.

### 🎫 Passenger Class and Survival

Passenger class provides useful information when analyzing survival patterns.

### 🎂 Age and Survival

Age distribution helps identify different passenger groups and their survival characteristics.

### 💰 Fare and Class

Passenger fare is related to passenger class and can be used to explore socioeconomic differences among passengers.

---

# 🚀 How to Run the Project

## Step 1 — Clone the Repository

Open your terminal or Command Prompt and run:

```bash
git clone https://github.com/DokkaChinnari/Titanic-Data-Analysis.git
```

Replace `YOUR-USERNAME` with your GitHub username.

---

## Step 2 — Open the Project Folder

```bash
cd Titanic-Data-Analysis
```

---

## Step 3 — Install Required Libraries

Install the required Python packages:

```bash
pip install pandas matplotlib openpyxl numpy
```

---

## Step 4 — Start Jupyter Notebook

Run:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

---

## Step 5 — Open the Notebook

Open:

```text
Titanic_Data_Analysis.ipynb
```

---

## Step 6 — Run the Cells

Run the notebook cells from top to bottom.

Make sure `Titanic.csv` is located in the same folder as the notebook.

---

# 📋 Requirements

The project requires the following libraries:

```text
pandas
matplotlib
openpyxl
numpy
jupyter
```

You can install them using:

```bash
pip install pandas matplotlib openpyxl numpy jupyter
```

---

# 📸 Project Screenshots

You can add screenshots of your notebook and graphs here.

Create a folder:

```text
screenshots/
```

Then add images such as:

```text
screenshots/
├── dataset.png
├── survival_chart.png
├── gender_analysis.png
├── class_analysis.png
└── age_analysis.png
```

Then add them to this README:

```markdown
## 📸 Project Screenshots

### Dataset Preview

![Dataset Preview](screenshots/dataset.png)

### Survival Analysis

![Survival Analysis](screenshots/survival_chart.png)

### Gender Analysis

![Gender Analysis](screenshots/gender_analysis.png)

### Passenger Class Analysis

![Passenger Class Analysis](screenshots/class_analysis.png)
```

---

# 📁 Repository Structure

After adding screenshots, your complete repository can look like:

```text
Titanic-Data-Analysis/
│
├── 📓 Titanic_Data_Analysis.ipynb
├── 📊 Titanic.csv
├── 📸 screenshots/
│   ├── dataset.png
│   ├── survival_chart.png
│   ├── gender_analysis.png
│   ├── class_analysis.png
│   └── age_analysis.png
│
└── 📄 README.md
```

---

# 🌟 Project Highlights

* ✅ Exploratory Data Analysis
* ✅ Data inspection
* ✅ Data cleaning
* ✅ Missing-value analysis
* ✅ Statistical analysis
* ✅ Survival analysis
* ✅ Gender-based analysis
* ✅ Passenger-class analysis
* ✅ Age analysis
* ✅ Fare analysis
* ✅ Data visualization
* ✅ Jupyter Notebook implementation

---

# 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Python programming
* Pandas DataFrames
* Data cleaning
* Exploratory Data Analysis
* Statistical analysis
* Data visualization
* Matplotlib
* Working with CSV datasets
* Jupyter Notebook
* Git and GitHub

---

# 🔮 Future Improvements

The project can be extended by adding:

* 🤖 Machine Learning survival prediction
* 📊 Interactive dashboards
* 🌐 Streamlit web application
* 📈 Additional visualizations
* 🔍 Feature engineering
* 🧠 Multiple ML algorithms
* 📋 Model performance comparison
* 🚀 Online deployment

---

# 👩‍💻 Author

## Chinnari Dokka

B.Tech - Artificial Intelligence & Machine Learning

Passionate about Data Analytics, Power BI, SQL, Python, and Machine Learning.

GitHub: https://github.com/DokkaChinnari

LinkedIn: https://www.linkedin.com/in/dokka-chinnari-aiml/

---

# ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

---
