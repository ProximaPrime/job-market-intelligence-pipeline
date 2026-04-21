# 🚀 Job Market Intelligence Pipeline (Adzuna API)

## 👤 Author
ABIODUN ADETEYE

---

## 📌 Project Overview

This project is an end-to-end **data engineering and analytics pipeline** that extracts global job listings from the Adzuna API, cleans and normalizes the data, and generates insights on job market trends across countries, companies, skills, and regions.

The system transforms raw job postings into structured, analyzable data suitable for recruitment intelligence and market research.

---

## ⚙️ Features

- 🔗 Job scraping from Adzuna API (multi-country support)
- 🧹 Data cleaning and normalization
- 🌍 Country standardization
- 🏙️ Region extraction and filtering
- 💻 Skill extraction using keyword matching
- 📊 Aggregated analytics (companies, skills, geography)
- 📈 Data visualization with matplotlib
- 💾 CSV export of cleaned dataset
- 🪵 Logging system for debugging and monitoring

---

## 📊 Key Insights

- **Total Jobs Processed:** 3,000+ listings  
- **Top Companies:** Lockheed Martin, Targeted Talent, Insight Global, ITOL Recruit  
- **Top Skills:** Python, Java, AWS, Docker, Linux  
- **Top Countries:** United States, France, United Kingdom, Germany, Canada  
- **Top Regions:** London, Paris, Toronto, Berlin, Vancouver, Montreal  

---

## 🛠️ Tech Stack

- Python
- Pandas
- Requests
- Matplotlib
- Regex
- Dotenv
- Adzuna API
## 📂 Project Structure

```text
job-market-intelligence-pipeline/
│
├── job_market_intelligence_pipeline.ipynb   # Main pipeline notebook
├── jobs_cleaned.csv                         # Final cleaned dataset
├── scraper.log                              # Logging output
├── .env                                     # API keys (not pushed to GitHub)
├── requirements.txt                         # Dependencies
└── README.md                                # Project documentation
├── requirements.txt                         # Dependencies
└── README.md                                # Project documentation
