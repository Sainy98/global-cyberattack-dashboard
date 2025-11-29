# Global Cyberattack Insights Dashboard (Power BI)
<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/0c8296b1-0d58-4a3a-9f49-072e5568c994" />

This project is a **Power BI dashboard** built from a CSV dataset of global cyberattacks from **2015–2025**.

It helps decision‑makers quickly see **financial loss, users affected, attack patterns, and defence performance** in one place.

## 1. Project Overview 🚀
I created a **Global Cyberattack Insights Dashboard** to turn a raw CSV file into clear visuals for business users.

The report shows high‑level KPIs at the top and then breaks down the data by country, attack type, industry, and defense mechanism.

The goal was to practice real‑world **data analytics + Power BI** skills and present them in a way that even non‑technical HR or managers can understand.

## 2. Problem Statement 🧩
Cybersecurity data is usually stored in tables and logs that are hard to read.

Managers often do not know which countries, industries, or attack types are causing the highest losses, or which defenses are most effective.

This project answers these questions with a single interactive dashboard.


## 3. Data & Tools Used 🛠️

- **Data source**:
    - CSV dataset of cyberattacks (2015–2025) with columns like: country, year, attack_type, target_industry, financial_loss, users_affected, resolution_time_hours, defense_mechanism, efficiency_score.
      
- **Tools**:
    - **Power BI Desktop** for data cleaning, modelling, and visualisation.
    - Basic **Power Query** steps for transforming the CSV file.
      
- **Data preparation steps**:
    - Removed blank or duplicate rows and standardised country/industry names.
    - Created aggregated tables for:
        - Total financial loss and total users affected
        - Loss by country and by industry
        - Attack count by attack type
        - Average efficiency score by defence mechanism
     

## 4. Dashboard Design 🧠
The layout follows common **executive dashboard** best practices so that key insights are visible in seconds.

- **Top KPIs (cards)**
    - Total Financial Loss (in million)
    - Total Users Affected
    - Total Cyberattacks
    - Average Resolution Time (hours)
      
- **Visuals used**:
    - Column chart: **Financial Loss by Country**
    - Bar chart: **Attack Count by Attack Type**
    - Column chart: **Financial Loss by Target Industry**
    - Bar chart: **Efficiency of Defense Mechanisms**
      
- **Design choices**:
    - Dark background with strong contrast, so charts are easy to read.
    - Consistent colours for related charts (e.g., all financial‑loss charts use similar blue tones) to help users connect information quickly.
    - Simple, clear titles and labels instead of technical jargon.
      

## 5. Key Insights 📊
Below are example insights you can keep or adjust based on your actual numbers:

- **High‑risk countries**
    - Countries like the **UK, Germany, and Brazil** show the highest financial loss, indicating heavy digital usage and strong attack activity.
    - Emerging markets such as **India and China** also show notable losses, which suggests fast digital growth and rising cyber risk.
      
- **Attack types**
    - **DDoS and phishing** are the most frequent attacks, followed by **SQL injection and ransomware**, so organisations must focus on network security, email security, and secure coding.
      
- **Target industries**
    - **Government, IT, and banking** suffer the highest loss, reflecting their sensitive data and high transaction volume.
    - **Healthcare, telecom, retail, and education** also face serious loss, proving that cyber risk exists in almost every industry.
      
- **Defense mechanisms**
    - **VPN, encryption, and AI‑based detection** receive higher efficiency scores compared to only traditional antivirus or firewall tools, supporting a layered security approach.

These insights demonstrate that the dashboard is not only visually appealing but also useful for real-world decision-making.


## 6. My Role and Workflow 🔁
- **Role**: End‑to‑end work – data cleaning, modelling, and dashboard design in Power BI.
- **Steps followed**:
    1. Understood the business questions: “Where are we losing money?” “Which attacks matter most?” “Are our defences working?”
    2. Imported the CSV into Power BI and cleaned the data using Power Query.
    3. Created calculated measures/aggregations for KPIs and charts.
    4. Designed the dashboard layout and iterated on colours and chart types for clarity.
       
 
## 7. How to View the Report 💻

- Download or clone this repository.
- Open the **`.pbix`** file in **Power BI Desktop**.
- If needed, point the report to the CSV file in the **`data/`** folder and click **Refresh**.

## 8. CTA
> 💡 *If this project matches what you’re looking for, I’d love to connect and discuss how I can add value to your team.*  
> 🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/harsh-pratap-singh-255568218/)  
> 📧 Or reach me directly at: **sainythakur@gmail.com**
