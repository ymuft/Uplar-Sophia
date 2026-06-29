<div align="center">

# 🧠 Uplar Sophia

### Transform CSV into Beautiful Dashboards

Turn structured CSV spreadsheets into beautiful, interactive dashboards with charts, KPIs, and actionable business insights.

<img src="./assets/images/banner.png" alt="Uplar Sophia Banner"/>

<br>

![Version](https://img.shields.io/badge/version-1.0-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/status-active-success?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Made with](https://img.shields.io/badge/Made%20with-JavaScript-yellow?style=for-the-badge)

</div>

---

# ✨ About

**Uplar Sophia** is an analytics platform developed by **Uplar** that automatically transforms structured CSV spreadsheets into modern business intelligence dashboards.

Upload your financial spreadsheet and instantly explore:

- 📊 Interactive Charts
- 📈 KPI Cards
- 📅 Monthly Trends
- 🏭 Cost Center Analysis
- 🔍 Smart Filtering
- 💰 Expense Breakdown

No database required.

Simply upload your CSV and start analyzing.

---

# 📸 Preview

<p align="center">
<img src="./assets/images/preview.png" width="100%">
</p>

---

# 🚀 Features

- 📁 CSV Upload
- 📊 Automatic Dashboard Generation
- 📈 KPI Cards
- 🏭 Cost Center Filters
- 🔎 Search by Description
- 📅 Date Range Filter
- 📉 Expense Trends
- 📋 Expense Ranking
- 🎨 Modern UI
- ⚡ Fast Rendering
- 📱 Responsive Design

---

# ⚠️ Supported CSV Format

> **Important**
>
> Uplar Sophia only supports CSV files following the required spreadsheet structure.

Generic CSV files are **not supported**.

The spreadsheet **must** contain the following layout.

| Column | Description |
|---------|-------------|
| DESC. CONTA | Expense description |
| DESC. C. CUSTO | Cost center / department |
| Month Columns | Monthly values (Apr/26, May/26, Jun/26...) |

Example:

| DESC. CONTA | DESC. C. CUSTO | Apr/26 | May/26 |
|--------------|----------------|---------|---------|
| SERVICOS DE TERCEIROS PJ | FUNDICAO (D.V.) | 3276.19 | 6471.51 |
| TELEFONE | INJECAO PLASTICA (D.V.) | 3.83 | 3.83 |
| MANUTENCAO E REPAROS | FUNDICAO (D.V.) | 23642.24 | 19675.82 |

---

# 📌 CSV Requirements

✔ First row must contain headers

✔ Column A = **DESC. CONTA**

✔ Column B = **DESC. C. CUSTO**

✔ Remaining columns = Months

✔ Monetary values must be numeric

✔ Empty cells can remain blank or contain "-"

---

# ⚙️ How It Works

```text
                CSV Spreadsheet
                       │
                       ▼
            Automatic Data Processing
                       │
                       ▼
        Expense Classification by Sector
                       │
                       ▼
        KPI Calculation & Aggregation
                       │
                       ▼
     Interactive Charts & Visual Analytics
```

---

# 📊 Dashboard Includes

- Total Expenses
- Monthly Average
- Largest Cost Category
- Monthly Evolution
- Cost Center Participation
- Dynamic Filters
- Search Engine
- Interactive Charts

---

# 🏭 Perfect For

- Manufacturing
- MES Systems
- ERP Financial Reports
- Cost Analysis
- Industrial Companies
- Accounting
- Finance Teams
- Business Intelligence

---

# 🧩 Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Interface |
| JavaScript | Application Logic |
| Chart.js | Charts |
| PapaParse | CSV Parsing |

---

# 📁 Project Structure

```text
Uplar-Sophia
│
├── assets
│   ├── css
│   ├── js
│   ├── icons
│   └── images
│       ├── banner.png
│       └── preview.png
│
├── examples
│   └── sample.csv
│
├── index.html
└── README.md
```

---

# 📥 Sample CSV

A sample CSV file is available inside:

```text
examples/sample.csv
```

Use it as a reference for your own spreadsheets.

---

# 🌟 Philosophy

> **"Where Data Becomes Wisdom."**

Inspired by the Greek concept of **Sophia (Wisdom)**, this project aims to transform raw operational data into clear, meaningful insights through elegant visualizations.

---

# 🗺 Roadmap

- [ ] AI-powered Insights
- [ ] Excel (.xlsx) Import
- [ ] PDF Export
- [ ] Dashboard Themes
- [ ] Multiple Languages
- [ ] Custom KPI Widgets
- [ ] Saved Dashboards
- [ ] User Authentication
- [ ] Cloud Synchronization

---

# 🤝 Contributing

Contributions are welcome.

Feel free to:

- Fork the repository
- Submit pull requests
- Open issues
- Suggest new features

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

## 🧠 Uplar Sophia

### Transform CSV into Beautiful Dashboards

Built with ❤️ by **Uplar**

</div>
