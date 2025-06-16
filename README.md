# Secure_Email_Threat_Analyzer
Secure_Email_Threat_Detection_Dashboard`

---

### 📄 README.md (Professional Version)
Here’s a clean and job-ready `README.md` you can use:

```markdown
# 🔐 Data-Driven Secure Email Transfer & Threat Analytics

### 📁 Repository: Secure_Email_Threat_Analyzer

### 🧪 Tech Stack:
- Python
- Flask (Web App Framework)
- Pandas (Data Handling)
- Power BI (Real-time Visualization)
- HTML/CSS (Frontend Templates)

---

## 📌 Project Overview
This full-stack project is built to **analyze email content for potential threats** such as phishing, spam, and suspicious keywords. It provides a **Flask web interface** to analyze emails manually or in batch (via CSV upload), and logs results to a backend CSV file. These logs are further visualized through **Power BI dashboards** for threat monitoring.

---

## 🎯 Objectives
- Analyze email data for phishing/spam threats using a rule-based model.
- Allow real-time analysis of individual or bulk emails.
- Store and log threat details to CSV with timestamps.
- Visualize email threat patterns and trends using Power BI.

---

## ⚙️ How It Works

- **Step 1:** User submits single email or uploads CSV file.
- **Step 2:** Backend parses body, checks for spam keywords and suspicious links.
- **Step 3:** Generates a `trust score` and assigns threat level (Safe, Suspicious, Phishing).
- **Step 4:** All results logged into `email_analysis_output.csv`.
- **Step 5:** Power BI dashboard visualizes patterns from the log data.

---



## 🚀 Project Features
✅ Real-time threat detection  
✅ CSV bulk upload for batch scanning  
✅ Spam keyword + link detection logic  
✅ Easy visual insights through Power BI  
✅ Flask web interface with logs

---

## ✅ Result
The system was able to detect and categorize email threats with **~80% efficiency** using rule-based logic. The dashboard enables security teams to quickly respond to risky email behavior patterns.

---

## 🙋‍♀️ Built By
**Lubna Shaikh** –  Data Analyst

---

## 🔒 Note
This project uses a simple keyword-based detection engine and is for educational/demo purposes. For production-level email security, advanced models (ML/NLP) and stricter sanitization are required.
