# 🇧🇪 Belgium Bank Dataset - Data Cleaning & Security Analysis

## 📊 Overview
Welcome to the official **Belgium Bank Dataset ETL & Analysis Repository**, designed for **fraud detection, data quality analysis, and banking security risk assessments**.

### 🔑 **Key Deliverables:**
- ✅ Full **data cleaning pipelines** (duplicates, invalids, missing values).
- ✅ Comprehensive **security and fraud risk analysis**.
- ✅ Visualized insights (charts, distributions).
- ✅ Executive-ready **Word document reports and JSON summaries**.

---

## 📂 Folder Structure

| Folder          | Description                                             |
|-----------------|---------------------------------------------------------|
| `raw_data/`     | 📥 Original datasets (Belgium IBAN etc.)                 |
| `output/`       | 💾 Clean datasets, invalid/duplicates reports            |
| `scripts/`      | ⚙️ Python notebooks for data cleaning & analysis        |
| `notebooks/`    | 📝 Stakeholder reports (Word), analysis, and charts      |

---

## 📈 Visualizations

- 🔶 **Missing Values per Column**
- 🔵 **Duplicate IBAN & Account Number Analysis**
- 📬 **Top 10 Email Domains Distribution**
- 📞 **Phone Number Length Distribution**
- 🧩 **Invalids vs Valids Overview**

---

## 🔐 Security Incident Reference: **Crelan Bank BEC Fraud (€70M Loss)**

**Lessons & Recommendations:**
- **Enforce security:** 2FA, SPF/DKIM, phishing filters.
- **Data validation:** Unique constraints on IBAN & Account Numbers.
- **Transactional controls:** Multi-signature approval.
- **Security training:** Anti-phishing and data privacy awareness.

---

## ✅ Recommendations for Belgium Bank

| Focus Area             | Recommendations                                    |
|----------------------|---------------------------------------------------|
| **Email Security**    | Enforce 2FA, SPF/DKIM, anti-phishing filters      |
| **Data Integrity**    | Schema constraints for IBAN/Account Numbers      |
| **Data Completeness** | Mandatory fields, real-time validation            |
| **Transaction Security** | Multi-approval large transactions             |
| **Training & Awareness** | Regular security workshops                   |

---

## 🚀 Getting Started

### 📥 Clone Repository
```bash
git clone https://github.com/ANADelta/Belgium-Bank-Dataset.git
