# Netflix Dataset Cleaning Using Python

## 📌 Project Overview

This project focuses on cleaning and preprocessing the Netflix Movies and TV Shows dataset using Python and Pandas. The objective is to prepare raw data for further analysis by handling missing values, removing duplicates, standardizing data formats, and exporting a clean dataset.

Data cleaning is an essential step in the data analysis pipeline, ensuring high-quality and reliable datasets for visualization and machine learning tasks.

---

## 🎯 Objectives

- Load the Netflix dataset from a compressed ZIP file.
- Identify and handle missing values.
- Remove duplicate records.
- Standardize text formatting and column names.
- Convert date columns into appropriate datetime format.
- Export a cleaned dataset for further analysis.

---

## 📂 Dataset

The project uses the **Netflix Movies and TV Shows Dataset**, which contains information such as:

- Show ID
- Title
- Type (Movie / TV Show)
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

## 🛠️ Technologies Used

- Python
- Pandas
- Google Colab
- Jupyter Notebook

---

## 🔄 Data Cleaning Steps

The notebook performs the following preprocessing tasks:

- Loaded the dataset from a ZIP archive.
- Examined dataset structure and missing values.
- Removed duplicate records.
- Filled missing values in:
  - Director
  - Cast
  - Country
  - Rating
  - Duration
- Converted the `date_added` column to datetime format.
- Renamed column names to lowercase with underscores.
- Standardized text formatting for categorical columns.
- Exported the cleaned dataset as `netflix_cleaned.csv`.

---

## 📊 Output

The final cleaned dataset is saved as:

```
netflix_cleaned.csv
```

This cleaned dataset is ready for:

- Exploratory Data Analysis (EDA)
- Data Visualization
- Dashboard Development
- Machine Learning Projects

---

## 📁 Project Structure

```
Netflix-Data-Cleaning/
│
├── task_1.ipynb
├── archive.zip
├── netflix_cleaned.csv
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Netflix-Data-Cleaning.git
```

### 2. Navigate to the project directory

```bash
cd Netflix-Data-Cleaning
```

### 3. Install dependencies

```bash
pip install pandas
```

### 4. Open Jupyter Notebook or Google Colab

Run:

```
task_1.ipynb
```

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Missing Value Treatment
- Duplicate Removal
- Data Transformation
- Date-Time Processing
- Feature Standardization
- Python Programming
- Pandas Library

---

## 📌 Future Improvements

- Perform Exploratory Data Analysis (EDA).
- Detect and handle outliers.
- Create interactive dashboards using Power BI or Tableau.
- Build recommendation or classification models.
- Automate the preprocessing pipeline.

---

## 👨‍💻 Author

**Vishnu Polanki**

GitHub: https://github.com/vishnupolanki9

---

## ⭐ If you found this project helpful, please consider giving it a star!
