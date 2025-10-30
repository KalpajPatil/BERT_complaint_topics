# 📊 Scalable Capital Google Play Review Analysis

This project scrapes **user reviews** from the Scalable Capital Android app on the Google Play Store, cleans and processes them, then performs **topic modeling**, **sentiment grouping**, and **visualization** to identify the most common user pain points, especially among reviews rated ≤ 3 stars.

---

## ✅ Features

- 🔎 Scrapes Google Play Store reviews using `google-play-scraper`
- 🌍 Collects reviews across **multiple languages** and **regions**
- 🏷️ Automatically tags each review with language & country
- ⚙️ Cleans & normalizes text for NLP tasks
- 📉 Filters negative reviews (3★ or below)
- 🧠 Applies **BERTopic** to discover complaint clusters
- 🌐 Translates German reviews into English using Deep-Translator
- 📊 Generates charts for topic frequencies
- 💬 Extracts representative example comments per topic


