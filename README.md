# Web Scraping & Sentiment Analysis of Business Standard Economic News

## 1. Project Overview
This project focuses on scraping economic news articles from Business Standard and performing sentiment analysis to classify news as **positive, negative, or neutral**. The goal is to analyze market sentiment trends and extract insights from economic news, which can be useful for financial analysis, research, and decision-making.

---

## 2. Objective
- Scrape economic news articles from Business Standard efficiently using Python.
- Perform sentiment analysis to classify each article into positive, negative, or neutral sentiment.
- Generate a dataset for further analysis and visualization of market trends.
- Create a reproducible workflow that can be extended for daily updates or advanced NLP models.

---

## 3. Data Source
- **Source:** Business Standard
- **Data Collected:** Economic news headlines
- **Output:** `sample_output.csv` containing:
  - `Title` – News headline   
  - `Sentiment` – Classified sentiment score (Positive, Negative, Neutral)

> Note: Only a small sample of the dataset is included in the repository (`sample_output.csv`) due to copyright considerations.

---

## 4. Tools & Technologies
- **Python** – Programming language  
- **Pandas** – Data manipulation and cleaning  
- **Selenium** – Automated web browsing and scraping   
- **BeautifulSoup** – Parsing and extracting HTML content  
- **TextBlob** – Sentiment analysis  

---

## 5. Methodology
1. **Web Scraping**  
   - Use Selenium to navigate Business Standard’s website and extract news headlines and content.  
   - BeautifulSoup parses the HTML to retrieve article text.

2. **Data Cleaning & Preparation**  
   - Clean extracted text using Pandas (remove unnecessary whitespace, special characters).  
   - Structure data into a CSV for analysis.

3. **Sentiment Analysis**  
   - Use TextBlob to analyze the polarity of each article.  
   - Classify sentiment as:
     - Positive (polarity > 0)  
     - Negative (polarity < 0)  
     - Neutral (polarity = 0)

4. **Output**  
   - Save processed data with sentiment scores in `sample_output.csv`.

---

## 📊 Data Source & Attribution

This project involves web scraping of publicly available news headlines for **educational purposes only**.

### 🔎 Source of Data

* News headlines are collected from publicly accessible websites.
* All rights to the content belong to their respective owners/publishers.

### ⚠️ Disclaimer

* This project does **not claim ownership** of any scraped content.
* The data is used strictly for **learning, analysis, and demonstration purposes**.
* No copyrighted content (such as full articles) is stored or redistributed in this repository.

### 📜 Compliance

* Users of this project are responsible for ensuring compliance with:

  * The respective website’s **Terms of Service**
  * Applicable **copyright laws and regulations**

### 🙏 Acknowledgment

* I acknowledge and respect the work of all news publishers and content creators.

---

> ⚡ Note: If you are a content owner and would like your data removed, please feel free to raise an issue in this repository.

