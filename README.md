# 🚀 n8n AI-Powered ETL Pipeline

An AI-driven **ETL (Extract, Transform, Load) automation workflow** built using **n8n, OpenAI, and JavaScript** to clean, validate, and standardize student enrollment data from CSV files.

## 📌 Project Overview

This project demonstrates how AI can automate traditional ETL operations, reduce manual data-cleaning effort, and improve data quality.

### 🔄 Workflow

CSV Upload → Extract CSV → OpenAI LLM → JavaScript Processing → Data Validation → CSV Export

## ✨ Key Features

- **CSV Extraction:** Import and process student enrollment records.
- **AI Data Cleaning:** Standardize names, emails, phone numbers, courses, cities, and dates.
- **Email Correction:** Automatically correct common email domain spelling mistakes.
- **Data Validation:** Identify valid and invalid email addresses.
- **JavaScript Processing:** Parse AI-generated JSON into structured records.
- **Automated CSV Export:** Generate a cleaned CSV file containing validated records.

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **OpenAI** – AI-powered data transformation
- **JavaScript** – JSON parsing and data validation
- **CSV** – Input and output data format

## 📊 Test Results

| Metric | Result |
|---|---|
| Total Records Processed | 50 |
| Valid Email Records | 12 |
| Invalid Email Records | 38 |
| Processing | Automated |

*Results are based on the initial test dataset and email-validation rules.*

## ⚙️ How to Use

1. Install or access n8n.
2. Import the workflow JSON into n8n.
3. Configure your OpenAI API credentials.
4. Upload a student enrollment CSV file.
5. Execute the workflow.
6. Review validated records and export the cleaned CSV.

## 🔮 Future Enhancements

- Database integration with MySQL/PostgreSQL.
- Duplicate student record detection.
- Automated error reporting.
- Data quality dashboard.
- Batch processing for larger datasets.

## 📄 License

MIT License

---

**Built with n8n + OpenAI + JavaScript**

#n8n #OpenAI #ETL #AIAutomation #DataEngineering
