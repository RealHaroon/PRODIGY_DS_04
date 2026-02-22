
# 📊 Task 4 – Sentiment Analysis & Visualization of Social Media Data

## 📌 Objective

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes toward different gaming topics and brands.

---

## 📂 Dataset Overview

* Total records: After cleaning
* Columns:

  * `id` – Unique identifier
  * `topic` – Brand/Game name
  * `sentiment` – Sentiment label (Positive, Negative, Neutral, Irrelevant)
  * `text` – Raw social media post

---

## 🧹 Data Cleaning

* Removed **686 null values** from the text column.
* Removed **2,340 duplicate rows** to ensure data quality.
* Converted text to lowercase.
* Removed:

  * URLs
  * Mentions (@)
  * Hashtags (#)
  * Numbers
  * Punctuation
  * Extra whitespaces
* Removed stopwords.
* Applied **lemmatization** to normalize words.
* Created a new column: `clean_text` for processed data.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Sentiment Distribution

* 30% Negative
* 26% Positive
* 24% Neutral
* 17% Irrelevant

The dataset is moderately balanced, with a slight dominance of negative sentiment.

---

### 🔹 Text Length Analysis

* Most posts contain **5–25 words**, typical for social media content.
* Users tend to express opinions in short and concise formats.

---

### 🔹 Topic Analysis

* The most frequently discussed word across the dataset is **"game"**, confirming the gaming-focused nature of discussions.

#### 📌 Sentiment by Topic:

* Topic with most Negative reactions: **MaddenNFL**
* Topic with most Positive reactions: **AssassinsCreed**

This indicates stronger dissatisfaction around MaddenNFL-related discussions, while Assassin’s Creed receives comparatively more positive engagement.

---

## 💬 Emotional Vocabulary Analysis

### 🔹 Positive Sentiment

Common words:

* game
* love
* good
* best
* play
* thank

Positive posts reflect appreciation, enjoyment, and satisfaction.

---

### 🔹 Negative Sentiment

Common words:

* shit
* fuck
* cant
* fix
* play

Negative sentiment is strongly associated with frustration and complaints.

---

### 🔹 Neutral Sentiment

Common words:

* game
* new
* one
* amazon

Neutral posts tend to be informational or general discussion-based.

---

### 🔹 Irrelevant Sentiment

Common words:

* player
* people
* see
* ban

These posts do not strongly reflect emotional opinions about the topic.

---

## 📈 Visualizations Created

* Sentiment distribution bar chart
* Text length histogram
* Top 20 most frequent words
* WordCloud (overall)
* WordCloud per sentiment
* Sentiment distribution by topic (stacked bar chart)

---

## 🎯 Key Insights

1. Negative sentiment slightly dominates the dataset.
2. Gaming-related discussions are the primary focus.
3. Emotional vocabulary clearly differentiates positive and negative posts.
4. MaddenNFL receives the highest negative sentiment volume.
5. AssassinsCreed shows the strongest positive engagement.
6. Social media posts are generally short and direct.

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* Matplotlib / Seaborn
* NLTK
* WordCloud

---

## 📌 Conclusion

This project demonstrates how sentiment analysis and text visualization techniques can reveal public opinion patterns across brands and topics. The findings highlight sentiment trends, emotional vocabulary, and brand-specific public reactions in gaming discussions.

---