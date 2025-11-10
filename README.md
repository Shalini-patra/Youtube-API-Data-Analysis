# 📊 YouTube Data Analytics using YouTube API  
A complete end-to-end data analytics project where I extracted YouTube video data using the YouTube Data API, cleaned and processed it using Python, analyzed trends and engagement metrics, and finally visualized the insights through an interactive Power BI dashboard.

---

## 🚀 1. Project Overview  
YouTube is the world’s second-largest search engine, yet the factors that drive video performance are still widely debated. This project aims to understand how video characteristics—such as duration, tags, title length, and publishing time—affect engagement (views, likes, comments).

Using data from top data-science YouTube channels, this project answers key questions content creators care about:
- What makes a video get more views?
- Does duration matter?
- Do likes and comments correlate with views?
- What topics are trending?
- How often should creators upload?

---

## 🎯 2. Aim & Objectives  

### **Aim**
To analyze YouTube video performance using YouTube API data and uncover patterns that influence viewer engagement.

### **Objectives**
- Understand and use the YouTube Data API to extract video metadata  
- Clean, preprocess, and engineer features for analysis  
- Explore patterns related to:
  - Views vs likes/comments
  - Video duration performance
  - Title length and tags  
  - Upload frequency and timing  
- Analyze trending topics using text analysis  
- Build a Power BI dashboard to visually communicate insights  

---

## 🗂️ 3. Dataset  
Data was collected from **10–15 top Data Science channels**, including:  
- Video metadata  
- Channel details  
- Tags  
- Comments  
- Engagement metrics (views, likes, comments)

### **Key Fields**
- `video_id`, `title`, `description`
- `duration`
- `tags`
- `publish_time`
- `view_count`, `like_count`, `comment_count`
- `topic_categories`

---

## 🛠️ 4. Tools & Technologies  

| Area | Tools |
|------|-------|
| Data Extraction | YouTube Data API, Python (requests) |
| Data Cleaning & EDA | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Text Analysis | NLTK, WordCloud |
| Data Storage | CSV & local storage |
| Dashboard | Power BI |
| Transformations | DAX Measures & Calculated Columns |

---

## 🔍 5. Project Steps  

### **5.1 Data Extraction using YouTube API**
- Created API key  
- Built functions to fetch playlists, videos, comments  
- Handled pagination using `nextPageToken`  
- Stored extracted metadata into structured CSV files  

### **5.2 Data Cleaning & Feature Engineering (Python)**
- Converted ISO-8601 duration into seconds  
- Cleaned tags, removed stopwords  
- Created new columns:
  - `title_length`
  - `tag_count`
  - `duration_minutes`
  - `publish_day`, `publish_hour`
- Processed missing values and normalized numeric fields  

### **5.3 Exploratory Data Analysis (EDA)**
Key insights explored:
- Correlation between view count & user interaction  
- Optimal video duration range  
- Impact of title length  
- Upload frequency of top creators  
- Topic trends via NLP  
  - WordClouds for titles  
  - Most common tags  
  - Comment themes  

### **5.4 Power BI Data Model**
Connected the cleaned dataset into Power BI and created:

#### **Calculated Columns**
- **Engagement Score**
- **Performance Category**
- **Upload Time Band (e.g., 12–3 PM)**  
- **Channel-wise Category**

#### **DAX Measures**
- `Total Views`
- `Total Likes`
- `Like-to-View Ratio`
- `Average Duration`
- `Top Performing Tags`
- `Views per Minute`

### **5.5 Dashboard Development**
Power BI dashboard includes:
- 📌 **Overview Page** – Summary KPIs  
- 📊 **Channel Comparison** – Engagement, upload trends  
- ⏱️ **Duration Analysis** – Ideal video length  
- 🔥 **Trending Topics** – Word clouds & tag frequency  
- 📅 **Publishing Patterns** – Optimal upload time  
- 🎯 **Video Performance Insight** – Scatter & bar charts  

---

## 📌 6. Key Insights  

- Videos between **8–12 minutes** showed the highest engagement  
- Strong positive correlation between **likes**, **comments**, and **views**  
- Uploading consistently boosts overall channel traction  
- Titles with **medium length (6–10 words)** performed best  
- Specific keywords in titles appear more often in high-performing videos  
- Peak publishing window found between **6 PM – 10 PM**  
- NLP shows trending topics like *Python, ML, Roadmap, Projects*  

---

## 🧠 7. Skills Demonstrated  
- API integration & JSON handling  
- Data cleaning and transformation  
- Text & engagement analytics  
- Python scripting for automation  
- Power BI data modeling & DAX  
- Dashboard storytelling  
- Analytical thinking & trend identification  

