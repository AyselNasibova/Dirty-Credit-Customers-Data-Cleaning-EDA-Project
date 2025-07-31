# Dirty-Credit-Customers-Data-Cleaning-EDA-Project

# 🧼 Credit Customers Dataset – Data Cleaning & Exploratory Data Analysis

This project demonstrates how to clean and analyze a messy credit customer dataset using Python in Google Colab. The workflow involves fixing missing values, removing outliers, converting formats, and visualizing key insights such as credit scores and age distribution.

## 📌 Project Goals

- Clean missing and inconsistent values from the dataset  
- Remove invalid records and outliers (e.g., unrealistic ages)  
- Normalize text fields like `Gender` and `FullName`  
- Convert date fields into datetime format  
- Create a new classification column: `CreditLevel` based on credit scores  
- Perform basic visual EDA with Matplotlib and Seaborn  

## 📁 Project Structure

```bash
credit-customers-cleaning-eda/
├── data/
│   └── dirty_credit_customers.csv      # Input dataset
├── notebooks/
│   └── cleaning_and_eda.ipynb          # Full code notebook
├── images/
│   ├── credit_score_dist.png           # Histogram of Credit Scores
│   └── age_distribution.png            # Histogram of Age
├── README.md                           # This documentation file
├── requirements.txt                    # Libraries used
└── .gitignore
```

## ⚙️ Technologies Used

- Python (Pandas, NumPy)
- Google Colab / Jupyter Notebook
- Matplotlib & Seaborn

## 📊 Exploratory Data Analysis

### 📈 Credit Score Distribution

Histogram of credit scores shows how customer credit values are spread across the dataset.

### 🎂 Age Distribution

Visualizes the frequency of customer ages after outlier removal and cleaning.

## 📦 How to Use

1. Clone the repo:  
   ```bash
   git clone https://github.com/yourusername/credit-customers-cleaning-eda.git
   ```

2. Upload your own `dirty_credit_customers.csv` into `/data` or use the sample provided.

3. Open the notebook in Google Colab or Jupyter:  
   `/notebooks/cleaning_and_eda.ipynb`

4. Run cells sequentially to reproduce the full cleaning and analysis.

## 📝 License

This project is licensed under the MIT License – feel free to use or modify.
