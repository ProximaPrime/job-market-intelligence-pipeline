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
## 🔐 Environment Variables

Create a `.env` file in the root directory and add your API keys:

```text
ADZUNA_APP_ID=your_app_id
ADZUNA_APP_KEY=your_app_key
```

---

## 🚀 How to Run

```bash
git clone https://github.com/ProximaPrime/job-market-intelligence-pipeline.git
cd job-market-intelligence-pipeline
pip install -r requirements.txt
jupyter notebook job_market_intelligence_pipeline.ipynb
```
## 📊 Outputs Generated

After running the pipeline, the system generates:

- `jobs_cleaned.csv` → cleaned and processed dataset  
- `scraper.log` → logs for debugging and tracking execution  
- Console insights:
  - Top companies
  - Top skills
  - Jobs by country
  - Top regions  
- Visualizations:
  - Bar charts for companies, skills, countries, and regions  

---

## 📌 Notes

- Ensure your Adzuna API keys are valid  
- Do NOT upload `.env` file to GitHub  
- Run notebook cells in order to avoid errors  
- Internet connection is required for API calls  

---

## 📌 Future Improvements

- Streamlit dashboard for interactive analytics  
- Real-time job scraping automation  
- Salary prediction module  
- Geographic heatmaps  

---

## 📄 License

This project is for educational and portfolio purposes only.

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
