# Racism Sentiment Analysis on Twitter (X)

![Python](https://img.shields.io/badge/Python-3.12-blue)
![NLP](https://img.shields.io/badge/NLP-VADER%20%7C%20TextBlob-orange)
![Data Science](https://img.shields.io/badge/Data%20Science-Pandas%20%7C%20Scikit--Learn-green)

## 📌 Project Overview
Traditional, off-the-shelf sentiment analysis tools frequently fail to detect the complex, highly contextual nuances of modern digital hate speech and racism. This project develops a heavily domain-adapted, culturally aware sentiment analysis pipeline specifically targeted at analyzing racist discourse directed towards the Indian and Asian communities on Twitter (X). 

By extending standard Natural Language Processing (NLP) lexicons and introducing a hybrid emotion detection framework, this project successfully maps the emotional texture, thematic categories, and platform engagement mechanics of digital xenophobia.

## 🚀 Key Features & Methodology
This project processes data through a custom 3-phase NLP pipeline:

1. **Domain-Adapted Sentiment Classification (Phase 1)**
   * Engineered a custom VADER sentiment lexicon, extending the baseline dictionary with 70+ racism-specific terms, slurs, and microaggressions.
   * Accurately classified text into Positive, Negative, and Neutral landscapes where generic NLP models failed.
2. **Granular Discourse Categorization (Phase 2)**
   * Built a multi-pass, keyword-based categorization engine that sorts discourse into **16 distinct thematic categories** (e.g., *Workplace Discrimination, Microaggressions, Solidarity & Allyship*).
3. **Deep Text Analytics & Emotion Mapping (Phase 3)**
   * **Hybrid Emotion Detection:** Implemented a strict 40/60 weighted model combining NRCLex with custom heuristics to map discourse across an 8-axis emotional profile.
   * **Subjectivity Analysis:** Utilized TextBlob to determine if hate speech is linguistically framed as factual statements or subjective opinions.
   * **TF-IDF Vectorization:** Extracted distinctive vocabulary fingerprints for different types of discourse, visualized via WordClouds.

## 📊 Critical Findings
* **The Engagement Paradox:** Through statistical correlation of platform metrics (likes, retweets, replies), we empirically proved that highly toxic, controversial content receives disproportionately higher algorithmic amplification (replies/retweets) compared to positive solidarity discourse, which primarily accumulates passive "likes".
* **Target Group Disparities:** The analysis revealed that anti-Indian racism is heavily concentrated in workplace discrimination and tech-industry stereotypes, while anti-Asian racism is more closely associated with physical violence and cultural erasure narratives.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **NLP & Text Mining:** NLTK (VADER), TextBlob, NRCLex, Regular Expressions (RegEx)
* **Machine Learning & Analytics:** Scikit-Learn (TF-IDF Vectorizer), Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, WordCloud
* **Reporting:** ReportLab, python-docx

## 👥 Contributors
* **Mannem Sri Harshitha** (23BCB7177)
* **Manasa Santosh** (23BCB7139)
* **K Vijay** (23BCB7243)
* **University:** VIT-AP University
