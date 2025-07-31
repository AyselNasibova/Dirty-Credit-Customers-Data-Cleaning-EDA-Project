# 🧹 Dirty Credit Customers — Data Cleaning & EDA Project

This project presents a complete data cleaning and exploratory data analysis (EDA) pipeline for a messy credit customer dataset. Using Python in Google Colab, we handle real-world data issues — such as missing values, inconsistent formatting, and outliers — to extract meaningful business insights.

---

## 📌 Project Goals

- Identify and handle missing or inconsistent values
- Remove outliers and unrealistic entries (e.g., negative or extreme ages)
- Standardize and clean text fields like `Gender` and `FullName`
- Convert date columns to proper `datetime` format
- Derive a new column `CreditLevel` based on credit scores
- Perform visual EDA using Matplotlib and Seaborn

---

## 📁 Project Structure

```
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

---

## ⚙️ Technologies Used

- Python (Pandas, NumPy)
- Google Colab / Jupyter Notebook
- Matplotlib
- Seaborn

---

## 📊 Exploratory Data Analysis

📈 **Credit Score Distribution**  
Histogram showing how credit scores are distributed across customers. This helps identify scoring patterns and potential anomalies.

🎂 **Age Distribution**  
Visualizes customer age distribution after removing unrealistic entries like negative or extreme values.

---

## 📈 Sample Visuals

**Credit Score Distribution**

![Credit Score Distribution](images/credit_score_dist.png)

**Age Distribution**

![Age Distribution](images/age_distribution.png)

---

## 📦 How to Use

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/AyselNasibova/Dirty-Credit-Customers-Data-Cleaning-EDA-Project.git
   ```

2. **Upload Your Dataset**  
   Place your `dirty_credit_customers.csv` file into the `/data` folder, or use the provided example.

3. **Run the Notebook**  
   Open `notebooks/cleaning_and_eda.ipynb` using:
   - Google Colab *(recommended for beginners)*
   - Or Jupyter Notebook (local environment)

4. **Follow the steps** to perform full cleaning and analysis. Outputs are generated step-by-step with visual explanations.

---

## 📝 License

This project is licensed under the **MIT License** — feel free to use, modify, and share.

---

## 🙌 Acknowledgements

Thanks to open-source tools like Pandas, Seaborn, and the community that supports data cleaning best practices.

---