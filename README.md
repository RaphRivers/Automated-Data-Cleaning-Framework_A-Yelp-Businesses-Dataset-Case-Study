# Automated Data Cleaning Framework (Yelp Dataset Case Study)

## 📖 Project Description  
This project focuses on building an **automated and adaptable data cleaning framework** designed to handle the challenges of **real-world, large-scale datasets**. Using the **Yelp dataset** as a case study, the framework provides reproducible methods for:  
- Identifying and handling missing values  
- Removing duplicates and inconsistencies  
- Standardizing formats (dates, text, categories)  
- Validating data quality before analysis  

Unlike one-off cleaning scripts, this project emphasizes **scalability and adaptability**—allowing the same framework to be applied across new datasets with minimal adjustments. The result is a **robust, analysis-ready dataset** that can directly feed into **machine learning pipelines or advanced analytics**, making it highly valuable for business and research use cases.  

## 🎯 Aim  
The aim of this project is to develop an **adaptable and automated data cleaning framework** that ensures **high data quality and consistency** for large datasets, using the **Yelp dataset** as a case study.

## 📌 Objectives  
1. **Data Exploration**  
   - Perform Exploratory Data Analysis (EDA) to understand dataset structure, distribution, and quality issues.  

2. **Data Cleaning**  
   - Automate cleaning steps such as:  
     - Handling missing values  
     - Removing duplicates  
     - Standardizing formats (e.g., dates, text, categorical values)  

3. **Adaptability**  
   - Build a **modular framework** that can adapt to new variables or different datasets with minimal manual intervention.  

4. **Validation**  
   - Verify that the cleaned dataset meets quality standards and is suitable for **analytics or machine learning tasks**.  

## 🛠️ Tech Stack  
- **Python** (pandas, numpy)  
- **Jupyter Notebook** (EDA & testing)  
- **Automated Scripts** (for pipeline execution)  

## 📂 Project Structure  
├── data/               # Raw and cleaned datasets  
├── notebooks/          # EDA and testing notebooks  
├── src/                # Source code for the cleaning framework  
│   ├── cleaning.py     # Core cleaning functions  
│   ├── validator.py    # Data validation methods  
│   └── utils.py        # Helper functions  
├── tests/              # Unit tests for framework adaptability  
├── README.md           # Project documentation  
└── requirements.txt    # Dependencies  

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/RaphRivers/automated-data-cleaning.git
   cd automated-data-cleaning

## Install dependencies:

pip install -r requirements.txt

## Run cleaning pipeline:

python src/cleaning.py --input data/raw/yelp.csv --output data/cleaned/yelp_cleaned.csv

### ✅ Expected Outcome

- Automated and reproducible cleaning workflow.
- Framework adaptable to new datasets with minimal adjustments.
- Clean dataset ready for analysis or ML tasks.

### Why This Project Matters

This project highlights practical data engineering and data science skills that employers value:
- Data Quality Expertise: Demonstrates the ability to handle real-world messy datasets.
- Automation & Scalability: Showcases building a reusable framework instead of one-off scripts.
- Adaptability: Framework is flexible enough to handle evolving business data needs.
- Readiness for ML/Analytics: Ensures cleaned, validated data that drives reliable insights.

By publishing this project, I aim to demonstrate strong problem-solving, technical implementation, and clean coding practices.
