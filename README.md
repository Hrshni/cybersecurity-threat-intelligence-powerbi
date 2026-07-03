# 🔐 Cybersecurity Threat Intelligence Dashboard

> An interactive Power BI dashboard analyzing 219,720 network security events 
> to identify attack patterns, threat severity, and network vulnerabilities 
> using the CICIDS 2017 dataset.

---

## 📊 Key Insights

| Metric | Value |
|---|---|
| Total Network Events Analyzed | 219,720 |
| Total Attacks Detected | 101,350 |
| Overall Attack Rate | 46.13% |
| Critical Severity Attacks | 79,329 |
| Normal Traffic | 118,370 |
| Most Common Attack | DDoS — 79,329 events |

---

## 🗂️ Dashboard Pages

| Page | Description |
|---|---|
| **Threat Overview** | KPI summary, attack categories, severity distribution |
| **Attack Trends** | Peak attack hours, day of week patterns, top attack types |
| **Severity Analysis** | Severity breakdown, category vs severity matrix |
| **Network Analysis** | Destination ports, flow duration, traffic patterns |
| **Incident Log** | Filterable incident table with date and severity slicers |

---

## 📸 Screenshots

### Threat Overview
![Threat Overview](screenshots/01_Threat_Overview.png)

### Attack Trends
![Attack Trends](screenshots/02_Attack_Trends.png)

### Severity Analysis
![Severity Analysis](screenshots/03_Severity_Analysis.png)

### Network Analysis
![Network Analysis](screenshots/04_Network_Analysis.png)

### Incident Log
![Incident Log](screenshots/05_Incident_Log.png)

---

## 🛠️ Tech Stack

- **Power BI Desktop** — Dashboard development and DAX measures
- **Python** — Data cleaning and preprocessing
- **Pandas** — Data manipulation and feature engineering
- **Dataset** — CICIDS 2017 Network Intrusion Detection Dataset

---

## ✨ Features

- 5 interactive dashboard pages with cross-filtering
- Dark themed professional design
- DAX measures for dynamic KPI calculations
- Tile slicers for severity and attack category filtering
- Date range slicer for incident log
- Page navigator for seamless navigation

---

## 🔍 Key Findings

- **46.13%** of all network traffic is malicious
- **DDoS attacks** are the most dominant threat — 36.1% of total traffic
- **Critical severity** attacks account for 79,329 events
- Attack patterns show variation across different hours and days of the week
- Port scanning is the second most common reconnaissance technique

---

## 🔗 Related Project

This dashboard connects directly to my Federated Learning Intrusion Detection System:
> [federated-learning-intrusion-detection](https://github.com/Hrshni/federated-learning-intrusion-detection)

That project achieved **96.7% detection accuracy** on similar network traffic data.

---

## 👤 About

Built by **Harshini S R** — Aspiring Data Analyst skilled in Python, SQL, and Power BI.

🔗 [LinkedIn](https://www.linkedin.com/in/harshinisr/)
🔗 [GitHub](https://github.com/Hrshni)
