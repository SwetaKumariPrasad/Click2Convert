# 📊 Streamlit File Transformation App

## 🚀 Overview
This **Streamlit Web App** allows users to **upload CSV or Excel files**, perform **data cleaning**, create **visualizations**, and **convert files** between CSV and Excel formats with ease.

## 🎯 Features
- **Upload multiple CSV or Excel files** 📂
- **Data Cleaning:** Remove duplicates & fill missing values 🧼
- **Column Selection:** Choose specific columns for processing 🎯
- **Data Visualization:** Generate bar charts for numerical data 📊
- **File Conversion:** Convert CSV to Excel & vice versa 🔄
- **Download Processed Files** ⬇️

## 🛠️ Installation & Setup
### 1️⃣ Install Dependencies
Ensure you have **Python 3.7+** installed. Then, install the required packages:
```sh
pip install streamlit pandas openpyxl
```

### 2️⃣ Run the App
Save the script as `App.py` and launch the Streamlit app:
```sh
streamlit run App.py
```

## 🔄 How It Works
1. **Upload a CSV or Excel file**.
2. **Preview the data** (first 5 rows displayed automatically).
3. **Perform Data Cleaning:**
   - Remove duplicate rows.
   - Fill missing values with column mean (for numerical data).
4. **Select Columns** for processing.
5. **Generate Bar Charts** (for numeric data columns).
6. **Choose Conversion Format** (CSV or Excel).
7. **Download the Processed File**.

## 📌 File Structure
```
📂 Streamlit-App
│── App.py            # Main Streamlit application
│── requirements.txt  # Dependencies
│── README.md         # Project documentation
```

## 🛠️ Dependencies
- **Python** (3.7+)
- **Streamlit** (UI framework)
- **Pandas** (Data processing)
- **Openpyxl** (Excel file handling)

## 📜 License
This project is **open-source** under the MIT License.

## 🙌 Contribution
Feel free to fork, improve, and submit a PR!

🚀 **Happy Coding!** 🎉

