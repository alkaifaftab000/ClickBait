# YouTube Clickbait Detection 🎥🧐

## Project Overview 📜
This project focuses on detecting clickbait content in YouTube videos by analyzing metadata, sentiment, and thumbnails. By utilizing natural language processing and pretrained transformers, it aims to classify videos as clickbait or non-clickbait effectively.

---

## Workflow ⚙️
1. **Fetching data using YouTube API**:  
   - Retrieved metadata from **750 videos**, including comments, views, likes, thumbnails, and published dates.

2. **Analyzing sentiments**:  
   - Used tools like **Vader**, **TextBlob**, and **NLTK** for sentiment analysis.  
   - Implemented **majority voting** to determine the overall sentiment for each video.

3. **Clickbait evaluation**:  
   - Combined sentiment analysis results and thumbnail information to declare whether a video is clickbait or not.

---

## Progress 🚀
- Identifying sentiments using pretrained transformers like **DeepSeek** and **Llama** to enhance the analysis.

---

## Plugins and Libraries Used 🛠️
- `ollama`  
- `youtube-developer`  
- `nltk`  
- `vader`  
- `TextBlob`  

---
