# 📊 Northwind Business Intelligence Project

## 🧠 Project Description

This project is an academic **Business Intelligence (BI)** project developed as part of a university course.
It is based on the **Northwind** database and aims to demonstrate the main concepts of BI through a practical implementation.

The project focuses on:

* Extracting data from relational databases (SQL Server or Microsoft Access)
* Transforming and cleaning data using Python (ETL process)
* Loading the processed data into an analytical database
* Creating an analytical dashboard to visualize key business indicators

---

## 🎯 Project Objectives

* Understand and apply Business Intelligence concepts
* Implement an ETL process using Python
* Analyze sales data from the Northwind database
* Create visual reports and dashboards for decision support

---

## 🗂️ Project Structure

```
Northwind-BI/
│
├── data/           # Raw and processed data
├── scripts/        # Python scripts
│   ├── etl.py      # ETL process (Extract, Transform, Load)
│   └── dashboard.py# Analytical dashboard
├── reports/        # Project report (PDF)
├── figures/        # Charts and visual outputs
├── video/          # Presentation video (screen recording + voice)
├── notebooks/      # Jupyter notebooks (optional)
├── README.md       # Project documentation
└── requirements.txt
```

---

## ⚙️ Technologies Used

* Python
* Pandas
* SQLAlchemy / PyODBC
* SQLite (analytical database)
* Streamlit / Plotly
* Jupyter Notebook

---

## 🔄 ETL Process

1. **Extract**: Data is extracted from the Northwind database.
2. **Transform**:

   * Data cleaning and formatting
   * Date processing
   * Calculation of sales indicators
3. **Load**: Transformed data is loaded into an analytical database for analysis.

---

## 📈 Dashboard & KPIs

The dashboard presents the following key performance indicators:

* Total Sales
* Number of Orders
* Average Order Value
* Sales evolution over time
* Top customers and products

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the ETL Process

```bash
python scripts/etl.py
```

### 3️⃣ Launch the Dashboard

```bash
streamlit run scripts/dashboard.py
```

---

## 📄 Deliverables

* Python ETL scripts
* Analytical dashboard
* Project report (PDF)
* Presentation video
* GitHub repository with structured files

---

## 👤 Author

* **Name:** Abdelmajid Baghdali
* **Course:** Business Intelligence
* **Project Type:** Individual

---

⭐ This project is developed for educational purposes only.
