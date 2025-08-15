# ARISE Congress 2.0 Data Analysis Project

## 📌 Project Overview
This project focuses on analyzing registration and participation trends for the forthcoming **Arise Congress 2.0** of the Nigeria Baptist Convention.  
The goal was to provide a clear, interactive, and data-driven dashboard to assist organizers in understanding attendee demographics, payment preferences, and conference distribution.

---

## 📂 Data Source & Collection
The dataset was sourced from the official Arise Congress registration platform (**reg.ariseforimpact.org**) using **[Apify](https://apify.com/)** for web scraping.  
This enabled extraction of structured and up-to-date information while ensuring completeness and accuracy.

---

## 🛠 Data Cleaning & Preparation
The raw scraped data contained inconsistencies and redundancies, which were addressed using **Power Query** in Microsoft Excel.

### Key Cleaning Steps:
- Removed duplicates and handled missing values.
- Standardized location names, payment methods, and registration types.
- Converted dates, numeric fields, and categorical values into analysis-ready formats.

---

## 📊 Data Analysis Process
Data summarization was done with **Pivot Tables** to:
- Categorize registrants by **gender**.
- Group registrations by **type** (Bulk vs. Personal).
- Break down **payment methods** (Bank Transfer vs. Card).
- Rank top conferences by number of registrants.
- Analyze participation history in **Arise Congress 1.0**.

---

## 📈 Dashboard Development
An **Excel Dashboard** was created to visualize the findings.

**Dashboard Highlights:**
- **Key Metrics:**  
  - Total registrants: **3,534**  
  - Males: **1,797** | Females: **1,737**
- **Registration Type:** 53.88% Personal | 46.12% Bulk
- **Payment Methods:** 51.39% Bank Transfer | 48.61% Card
- **Top 10 Conferences by Registrations:** Lagos leads, followed by Ibadan, Ondo, Osun, and Edo.
- **Participation History:** 63.78% of current registrants attended Arise 1.0.
- **Registrant Distribution:** Lagos (1,208) had the highest count.

---

## 💡 Key Insights
1. **High Lagos Engagement** – Lagos dominates in both conference registration and total attendees.
2. **Balanced Gender Representation** – Nearly equal split between male and female participants.
3. **Payment Preference Split** – Slight preference for Bank Transfers over Card payments.
4. **Returning Attendees** – Two-thirds are returning participants from Arise 1.0.
5. **Diverse Conference Reach** – Registrants span multiple conferences, with a few dominating numbers.

---

## ✅ Conclusion
This project showcases how **web scraping (Apify)**, **data cleaning (Power Query)**, **data summarization (Pivot Tables)**, and **Excel visualization** can turn raw data into actionable insights.  
The resulting dashboard equips event organizers with a powerful tool for planning and resource allocation ahead of **Arise Congress 2.0**.

---

## 🖼 Dashboard Preview
![Arise Congress Dashboard](https://github.com/EjiroGee/Arise-Congress-Registration-Analysis/blob/main/Arise%20Dashboard.jpg)

---

**Author:** Ekiugbo Ejiroghene  
**Tools Used:** Apify, Microsoft Excel, Power Query, Pivot Tables  
**Tags:** `#DataAnalysis` `#WebScraping` `#Excel` `#PowerQuery` `#Apify`
