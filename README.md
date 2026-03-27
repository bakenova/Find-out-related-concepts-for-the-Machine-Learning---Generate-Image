# Machine Learning Text Analysis & Visualization

This project is a simple, introductory implementation of text analysis techniques in Python. It is designed as a learning exercise to understand the core concepts of web scraping, text preprocessing, keyword extraction, and data visualization.

⚠️ Note: This is a primitive (basic-level) project intended for educational purposes.

**Purpose**
The main goal of this project is to:
	•	Understand how raw text data can be collected from the web
	•	Learn basic text cleaning techniques
	•	Explore keyword extraction using simple algorithms
	•	Practice visualizing textual data

**Overview**
The script fetches an article about Machine Learning from the IBM website and performs the following steps:
	1	Scrapes HTML content from the web page
	2	Removes unnecessary elements (navigation, sidebars, metadata)
	3	Extracts readable text
	4	Identifies key phrases using RAKE (Rapid Automatic Keyword Extraction)
	5	Visualizes results using charts and word clouds

**What was used?**
	•	requests — HTTP requests
	•	BeautifulSoup — HTML parsing
	•	nlp_rake — keyword extraction
	•	matplotlib — visualization
	•	wordcloud — text visualization

**How It Works**

_1. Data Collection_
The script downloads HTML content from the IBM Machine Learning page.

_2. Data Cleaning_
Basic cleaning is applied by removing irrelevant HTML blocks.
This step is simplified and does not cover advanced text preprocessing techniques.

_3. Keyword Extraction_
RAKE is used to extract keywords based on simple rules like frequency and word length.
This is a basic NLP approach and does not use machine learning models.

_4. Visualization_
The extracted keywords are visualized using:
	•	Bar charts
	•	Word clouds

**Results**
- Keyword Frequency Bar Chart:
<img width="1989" height="690" alt="word_scores_barchart" src="https://github.com/user-attachments/assets/8191b5e0-0d37-4b2d-8ba8-5fc68e5bc4aa" />

- Word Cloud (From Keywords):
<img width="636" height="482" alt="key_wordcloud" src="https://github.com/user-attachments/assets/3dfc2c31-b1c1-433d-9ab5-c7d45105bfa7" />

- Word Cloud (From Full Text):
<img width="738" height="559" alt="ml_wordcloud" src="https://github.com/user-attachments/assets/fc0f37a5-0e60-4e0f-baea-55d24059cb97" />
