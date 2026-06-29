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

**Uplar Sophia** is an analytics platform developed by **Uplar** that transforms structured CSV spreadsheets into modern, interactive business intelligence dashboards.

Upload your operational or financial data and instantly explore:

- 📊 Interactive Charts
- 📈 KPI Cards
- 🏭 Cost Center Breakdown
- 🔍 Smart Filtering System
- 📅 Time-based Analysis
- 💰 Expense Aggregation

No database required.

Just upload your CSV and start analyzing instantly.

---

# 📸 Preview

## 📊 Dashboard View

<p align="center">
<img src="./assets/images/preview.png" width="100%">
</p>

## 📄 Input Spreadsheet Example

<p align="center">
<img src="./assets/images/excel-preview.png" width="100%">
</p>

---

# ⚠️ IMPORTANT — Supported CSV Structure

Uplar Sophia **does NOT support generic CSV formats**.

Your file must follow this **fixed structure exactly**:

### 📌 Required Columns

| Column | Description |
|--------|-------------|
| MÊS | Reference month/date |
| DESC. CONTA | Expense description |
| DESC. C. CUSTO | Cost center / department |
| REALIZADO | Monetary value |

---

## 📊 Example (Correct Format)

| MÊS       | DESC. CONTA                | DESC. C. CUSTO            | REALIZADO |
|----------|----------------------------|----------------------------|------------|
| 01/04/2025 | SERVICOS DE TERCEIROS PJ   | FUNDICAO (D.V.)           | 3.288,61   |
| 01/04/2025 | TELEFONE                   | INJECAO PLASTICA (D.V.)   | 3,69       |
| 01/04/2025 | MANUTENCAO E REPAROS       | FUNDICAO (D.V.)           | 8.381,80   |

---

# 📌 CSV Rules (STRICT)

✔ Must contain headers in the first row  
✔ Column order must match the structure above  
✔ REALIZADO must be numeric (currency supported)  
✔ MÊS must be a valid date format  
✔ Empty values allowed but not recommended  
✔ Encoding: UTF-8 recommended  

---

# ⚙️ How It Works

```text
        CSV Upload
            │
            ▼
   Data Normalization Layer
            │
            ▼
 Cost Center Classification
            │
            ▼
 KPI & Aggregation Engine
            │
            ▼
  Interactive Dashboard Render
