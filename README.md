# 📊 YouTube Analytics Dashboard using YouTube Data API  
An end-to-end data analytics project analyzing **13 Travel Vlogger YouTube channels** using **YouTube API, Python, and Power BI**.

---

## 🚀 Project Overview  
This project focuses on extracting **real-time YouTube video data** from 13 well-known travel vloggers using the **YouTube Data API**, followed by cleaning, wrangling, EDA, insight generation, and dashboard creation.

The goal was to understand **what drives video performance**—factors like duration, publishing trends, keywords, subscriber influence, and engagement behavior.

---

## 🧠 Key Objectives  
- Extract structured data using the **YouTube Data API**  
- Perform **data cleaning, transformation, and feature engineering**  
- Conduct **exploratory data analysis (EDA)** in Python  
- Visualize performance metrics using an **interactive Power BI dashboard**  
- Identify patterns behind **high-performing videos**  

---

## 📂 Dataset  
The dataset consists of API-extracted metadata from **13 travel vloggers**, including:

- Channel name  
- Video title & description  
- Published date  
- Duration (seconds)  
- Views, Likes, Comments  
- Subscriber count  
- Tags & keywords  
- Engagement ratio  
- Category & channel trends  

All data was fetched using Python scripts and stored as CSV for analysis.

---

## 🛠️ Tech Stack  
- **Python** (Requests, Pandas, NumPy)  
- **YouTube Data API v3**  
- **Power BI**  
- **Jupyter Notebook**  
- **GitHub**  

---

## 🧩 Project Workflow  

### **1️⃣ Data Extraction (API)**  
- Used `requests` to query the YouTube API  
- Collected metadata for 13 channels  
- Stored raw JSON responses → converted to CSV  

### **2️⃣ Data Cleaning & Transformation (Python)**  
- Removed duplicates and missing values  
- Created derived metrics:
  - Engagement Rate  
  - View-to-Subscriber Ratio  
  - Duration Bins  
  - Published Time Buckets  
- Standardized category and keyword fields  

### **3️⃣ Exploratory Data Analysis (Python)**  
Performed detailed EDA to uncover patterns:  
- Which travel vloggers get the highest engagement  
- Does video duration affect performance?  
- Do specific keywords (like “budget”, “adventure”, “solo trip”) attract more views?  
- Posting trends by weekday & hour  
- Correlation between subscribers & video performance  

### **4️⃣ Interactive Power BI Dashboard**  
Features include:  
- Channel Insights Overview  
- Top 10 Videos  
- Engagement Trends  
- Duration vs Views Scatter  
- Publishing Time Effect  
- Keyword/Tag Analysis  
- Subscriber Growth Indicators  

### **5️⃣ Insights Summary**  
Some highlights (based on your EDA steps):  
- Mid-duration videos (8–12 mins) had the highest views  
- Weekend uploads showed stronger engagement  
- Videos with destination-focused keywords performed better  
- High-subscription channels didn’t always guarantee high views → content relevance matters  
- Tags related to “travel tips”, “budget travel”, “vlog series” drove more engagement  

---

## 📁 Project Structure  

```
youtube-analytics-project/
│── assets/
│ ├── project_thumbnail.png
│
│── dashboard/
│ ├── YT analysis dashborad - (1000 rows sample).pbix
│ ├── report pages .pdf
│
│── data/
│ ├── channel_data.csv
| ├── video_stats.csv
│
│── python scripts/
│ ├── Youtube_API_data_Analysis.ipynb
│
│── README.md
```

---

## 🧪 How to Run This Project

```bash
# 1. Install Dependencies
pip install -r requirements.txt

# 2. Add your API key
# Open the extract script and set:
API_KEY = "YOUR_API_KEY"

# 3. Run the extraction script
python extract_youtube_data.py

# 4. Open Power BI Dashboard
# Open the file: youtube_analysis.pbix
```

---

## 🎯 What You Will Learn
- API-driven data collection  
- Real-world data cleaning & EDA  
- Insights storytelling  
- Dashboard development in Power BI  
- YouTube analytics fundamentals

---

## 🤝 Contact

**T Shalini Patra**  

📧 tshalinipatra@gmail.com
📱 +91 9348207149
🔗 GitHub: https://github.com/Shalini-patra
