# Netflix Dataset - Exploratory Data Analysis (EDA)

## 📌 Lab Description
This lab applies Exploratory Data Analysis (EDA) techniques learned in the lab on the Netflix Movies and TV Shows dataset.  
The goal is to clean the dataset, explore patterns, and visualize insights using Python.

This assignment demonstrates data cleaning, visualization, and basic data analysis using pandas, matplotlib, and seaborn.

---

## 📂 Dataset
Dataset used:  
Netflix Movies & TV Shows dataset (CSV)

The dataset includes:
- Title
- Type (Movie or TV Show)
- Country
- Release year
- Date added
- Rating
- Duration
- Genre

The dataset file is included in this repository.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning Steps
- Checked dataset shape and data types
- Handled missing values in:
  - director
  - cast
  - country
  - rating
- Converted `date_added` to datetime format
- Created a new column `year_added`
- Removed duplicates
- Handled missing duration values

---

## 📊 Analysis Performed

### 1. Distribution of Release Years
Used histogram to visualize release year distribution.

### 2. Movies vs TV Shows
Countplot comparing number of movies and TV shows.

### 3. Top Producing Countries
Bar chart showing countries with the most content.

### 4. Release Year vs Year Added
Scatterplot to compare release year and year added to Netflix.

### 5. Correlation Heatmap
Correlation between numerical columns.

### 6. Monthly Content Added
Time analysis showing how content was added over time.

---

## 📈 Key Insights
- Netflix contains more Movies than TV Shows.
- The United States produces the highest number of titles.
- Content increased significantly after 2015.
- Most content was added in recent years.
- TV-MA is the most common rating.

---

## 📎 Files Included
- `Netflix_EDA.ipynb` → Jupyter Notebook
- `netflix_titles.csv` → Dataset
- `README.md` → Project description

---

## ▶ How to Run
1. Download the repository
2. Open the notebook in Jupyter Notebook or JupyterLab
3. Install required libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn
