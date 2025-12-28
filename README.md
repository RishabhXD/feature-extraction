# 📺 Anime Data Analysis

## 📌 Project Overview
This project performs **exploratory data analysis (EDA)** and **feature engineering** on an anime dataset. The objective is to clean raw textual data, extract structured information such as episode count and runtime, and transform date ranges into measurable metrics useful for analysis.

The project demonstrates practical **data preprocessing techniques** commonly used in data science workflows, including regex-based text parsing, date manipulation, and DataFrame enrichment using Python.

---

## 📂 Repository Structure

```text
.
├── Anime.ipynb        # Jupyter notebook with full analysis and transformations
├── anime.csv          # Raw anime dataset
└── README.md          # Project documentation
```

---

## 🧾 Dataset Description
The dataset (`anime.csv`) contains metadata related to anime shows, including:
- Anime title  
- Total airing duration (text format)  
- Episode information (embedded in text)  
- Additional descriptive fields  

Some fields contain **unstructured or semi-structured text**, making them ideal for feature extraction and cleaning exercises.

---

## 🛠️ Tech Stack & Libraries
- Python 3  
- pandas  
- numpy  
- re (Regular Expressions)  
- datetime  

---

## 🔍 Key Functionalities

### Episode Extraction
- Extracts episode counts from text fields using regex
- Handles inconsistent formats such as brackets and mixed strings

### Runtime Calculation
- Converts date ranges like `Apr 2011 - Sep 2011` into total runtime in **months**
- Stores results in a derived column for analysis

### Data Cleaning & Feature Engineering
- Handles missing or malformed values
- Enhances the dataset with analysis-ready features

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Navigate to the project directory:
```bash
cd feature-extraction
```

3. Open the notebook:
```bash
jupyter notebook Anime.ipynb
```


