# 📞 Call Quality Analyzer – Quick Start Guide

Easily analyze any sales call recording for **talk-time ratio, questions asked, monologue duration, sentiment, and actionable insights** — all in under **30 seconds** on Google Colab (free CPU tier).  

---

## 🚀 How to Run the Notebook

### 1. Open Google Colab  
👉 Visit [Google Colab](https://colab.research.google.com/)

### 2. Upload the Notebook  
- Go to **File > Upload notebook**  
- Select **`Call_Quality_Analyzer_Final.ipynb`** from your local system  

### 3. Install Dependencies  
- Run the **first code cell** to install required packages:  
  - `yt-dlp`  
  - `faster-whisper`  
  - `vaderSentiment`  
  - `textblob`  

### 4. Run All Cells Sequentially  
- Click **Runtime > Run all**  
- The notebook will automatically:  
  1. **Download YouTube audio** (preset test file URL, or your custom link)  
  2. **Transcribe audio** using the *faster-whisper tiny model*  
  3. **Detect speakers** & calculate **talk-time ratios**  
  4. **Identify all questions asked** with high accuracy  
  5. **Analyze call sentiment**  
  6. **Generate actionable insights**  
  7. **Display comprehensive results** for full transparency  

### 5. View Results  
- Results appear directly inside the notebook:  
  - ✅ Total number of questions detected  
  - ✅ Numbered list of all questions (easy validation)  
  - ✅ Sentiment scores, talk-time ratio, and insights  

---

## ⚡ Performance  
- Designed for **Google Colab (Free CPU)**  
- Typical call analysis completes in **15–25 seconds**  

---

✨ Just follow these steps for a **fast, transparent, and detailed call quality analysis**!
