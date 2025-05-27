  # 🧾 Invoice Data Analyzer

This project is a simple yet practical automation tool built in **Python** using **pandas**. It reads a CSV file of freelance invoice data, cleans and processes it, analyzes the performance by client, and outputs summary statistics, exports, and optional charts.

It’s ideal for freelancers or consultants who want quick insights into revenue, hours worked, and hourly rates — and a great beginner-friendly data automation project.

---

## 📌 Features

- ✅ Load and clean messy invoice data
- 📊 Analyze revenue, hours worked, and average hourly rate per client
- 📅 Group data by date/month (optional)
- 📈 Generate bar chart for client revenue (optional)
- 📁 Export cleaned data and summary to `.csv` and `.xlsx`
- ⚙️ 100% built with pandas in a Jupyter Notebook

---

## 🧰 Tech Stack

- Python 3.x
- pandas
- matplotlib (optional)
- Jupyter Notebook

---

## 📂 Files in This Project

| File | Description |
|------|-------------|
| `Invoice_Analyzer.ipynb` | Main Jupyter Notebook |
| `invoices.csv` | Sample invoice data (raw input) |
| `cleaned_invoices.csv` | Cleaned output data |
| `summary.csv` / `summary.xlsx` | Revenue summaries per client |
| `client_revenue.png` | (Optional) Revenue visualization |
| `README.md` | This file |
| `requirements.txt` | Python dependencies |

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/invoice-data-analyzer.git
   cd invoice-data-analyzer
