# 🌐 Global Cyber Security Dashboard (2015–2024)

An interactive Tableau dashboard built to analyze global cybersecurity incidents using data from international threat reports, monitoring tools, and cybersecurity agencies. This project uncovers regional vulnerabilities, common attack types, industry impact, and evolving threat patterns over a decade.

---

## ❓ Problem Statement

The rising frequency and sophistication of cyberattacks across the world pose a growing threat to national security, business continuity, and user privacy. However, organizations struggle to gain a consolidated view of where, how, and why these threats emerge.  
The objective of this project is to transform raw incident-level data into a meaningful and interactive dashboard that helps stakeholders proactively respond to global cyber risks.

---

## 🖼️ Dashboard Preview

![Dashboard Preview](Tableau%20Cyber%20Threats%20Dashboard/Screenshots/Dashboard.png)

---

## 📊 Objective

To build a dynamic Tableau dashboard that provides insights into:
- Regional and country-level cyber threats
- Top attack types and their evolution over time
- Most targeted industries
- Economic impact of cyberattacks by region
- Annual trends in incident volume from 2015–2024

---

## 🛠 Tools & Features Used

| Tool / Feature        | Purpose                                              |
|-----------------------|------------------------------------------------------|
| **Tableau Public**     | Dashboard creation and data visualization           |
| **Excel / CSV**        | Source dataset formatting and pre-processing        |
| **Calculated Fields**  | Deriving KPIs and time-based metrics                |
| **Filters & Actions**  | Enable dashboard interactivity                      |
| **Maps, Area Charts, Bubbles** | Display regional density, trend evolution, and losses |

---

## 🧩 Project Workflow

### 1. Data Collection & Cleaning
- Combined data from multiple cybersecurity sources (reports, monitoring tools, threat intelligence)
- Fields included:
  - `Country`, `Year`, `Attack Type`, `Target Industry`
  - `Financial Loss (Million $)`, `Users Affected`, `Resolution Time (hrs)`, etc.
- Cleaned inconsistent records, handled nulls, and standardized naming conventions

### 2. Dashboard Components
Built the following visuals in Tableau:
- **Global Threat Map**: Choropleth map showing incidents by country
- **Threat Evolution Over Time**: Stacked area chart showing trends for attack types like Malware, Phishing, Ransomware, etc.
- **Incidents Over the Years**: Line graph showing total threats from 2014–2024
- **Top Countries in 2024**: Bar chart highlighting leading countries by incident count
- **Incidents by Industry**: Pie chart showing distribution across sectors
- **Economic Impact**: Bubble chart visualizing financial losses per country

### 3. Interactivity
- Clicking on any country, industry, or attack type filters all other views
- Dashboard allows multi-layer analysis through action filters and legends
- Hover tooltips show detailed incident data

---

## 📈 Dashboard Features

| Feature                    | Description                                                              |
|----------------------------|--------------------------------------------------------------------------|
| **Global Threat Map**      | Color-coded view of cyber incidents per country                          |
| **Top Countries in 2024**  | Compare nation-wise incidents in a specific year                         |
| **Threat Evolution**       | Visualize trends in Malware, Ransomware, Phishing, etc. (2014–2024)     |
| **Yearly Trends**          | Line graph showing rise in incidents and pandemic-related spikes         |
| **Industry Breakdown**     | Pie chart showing most targeted sectors (IT, Banking, Healthcare, etc.) |
| **Economic Loss Chart**    | Bubble chart comparing financial impact across countries                |

---

## 📂 Folder Structure

Tableau Cyber Threats Dashboard/
├── Data/
│ └── Global_Cybersecurity_Threats_2015_2024.csv
├── Dashboard/
│ └── Cyber_Threat_Dashboard.twb
├── Screenshots/
│ └── Dashboard.png
├── Documentation/
│ └── Readme.md


---

## ▶️ How to Use

1. Download or open the Tableau `.twb` file from the `Dashboard/` folder  
2. Use Tableau Desktop or Tableau Public to view  
3. Click on any map region, industry slice, or attack type to filter other charts  
4. Use legends and filters to explore threats over time and across regions  

---

## 💡 Insights Gained

- The **UK** had the highest cumulative number of incidents from 2015–2024
- **China**, **Brazil**, and **Australia** led the 2024 incident rankings
- **Malware** and **Phishing** are the most persistent global threats
- **Ransomware** attacks sharply rose post-2020 during the remote work boom
- **IT, Banking, and Healthcare** are the most targeted sectors
- Countries with **advanced economies** suffer the **highest financial losses**

---

## 📧 Author

**Shubham Bogal**  
📫 Email: shubhambogal10@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/your-linkedin)

---

## 📜 Note

This project is for educational and portfolio purposes. All data used is either simulated or sourced from public/global threat reports. The dashboard is built using **Tableau** with no custom code or third-party extensions.
