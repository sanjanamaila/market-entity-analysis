# 📊 Market Entity Analysis Project
### Using LLMs to Analyze Financial News and Social Media Data

## 🚀 Project Overview
This project explores how Large Language Models (LLMs) can be applied to financial text data (news headlines and tweets) to extract **market entities**, evaluate **sentiment**, and visualize **trends**.  

By combining NLP with financial analytics, the project demonstrates how AI can provide insights into **which companies are being discussed**, **how positively or negatively**, and **what recommendations analysts are making**.

---

## 🎯 Goals
1. Analyze financial news headlines/tweets.  
2. Extract market entities (companies, stocks, tickers).  
3. Perform sentiment analysis around these entities.  
4. Visualize the most discussed, positive, negative, and controversial entities.  

---

## 🛠️ Methods
- **Data Source:** `market_headlines_1000.csv` (testing) and `market_headlines_full.csv` (full dataset).  
- **Entity & Sentiment Extraction:**  
  - LLM prompt design for structured JSON output  
  - Entities include: name, sentiment, and analyst recommendation  
- **Entity Consolidation:**  
  - Mapping of different representations (e.g., Microsoft/MSFT, Meta/Facebook)  
- **Analysis & Visualization:**  
  - Aggregated sentiment distribution per entity  
  - Visuals of entity mentions, sentiment polarity, and analyst recommendations  

---

## 🧰 Tools & Libraries
- **Google Colab** (development & testing)  
- **Python**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **LLMs**: Qwen 7B / Llama 3.1 8B instruct  

---

## 📈 Key Results
- Identified the **most frequently mentioned market entities**.  
- Classified **sentiment trends** (positive, negative, neutral).  
- Highlighted **analyst recommendations** (upgrade, downgrade, hold).  
- Produced **visual dashboards** summarizing sentiment around companies.

---
## 📓 Project Notebook
You can view the complete notebook with code, outputs, and visualizations here:  

👉 [Market Entity Analysis Notebook](bsan885_project.ipynb)

Or run it directly in Google Colab:  

[![Open In Colab](https://colab.research.google.com/github/sanjanaa31/market-entity-analysis/blob/main/bsan885_project.ipynb)





---

## 📂 Repository Structure
