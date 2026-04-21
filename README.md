Airline Sentiment Analysis — ACC102 Track 2

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-orange.svg)](https://matplotlib.org/)

## 1. Problem & Target Audience
Problem:
  Airline passengers frequently express complaints on social media, but airlines lack a structured way to identify which issues matter most and which carriers perform poorly in customer sentiment.
Target Audience:
  Airline customer experience teams and operations managers who need data-driven insights to prioritise service improvements, such as on-time performance, customer service, and baggage handling.

## 2. Data Source
- Dataset: Twitter US Airline Sentiment (Kaggle)
- Access Date: 7 April 2026
- Size: 14,640 tweets
- Key fields: airline, airline_sentiment (negative/neutral/positive), negative_reason, text, retweet_count
  The data were collected from Twitter in February 2015 and represent real customer feedback about major US airlines.

## 3. Methods & Tools
Data loading: Use pandas to read CSV and inspect data structure.
Data cleaning: Handle missing values and filter negative tweets for reason analysis.
Exploratory analysis: Analyse sentiment distribution and airline-wise performance.
Negative reason analysis: Count and rank complaint categories.
Visualisation: Use matplotlib to create pie charts, stacked bar charts, and bar charts.
 All analysis is performed in a single Jupyter Notebook.

## 4. Key Findings
- Overall sentiment is heavily negative. 62.7% of tweets are negative, and only 16.1% are positive.
- US Airways and United have the highest negative ratios, while Virgin America is the most balanced.
- The top 3 complaint reasons are Customer Service Issue, Late Flight, and Cancelled Flight.
- Improving on-time performance and customer service processes would significantly reduce complaints.
  
## 5. How to Run the Notebook
*Clone this repository**  
  git clone https://github.com/XuzhenLiu102/Acc102-Track2-Airline-Sentiment-Data-Analysis.git
   cd Acc102-Track2-Airline-Sentiment-Data-Analysis
*Install required packages
   pip install pandas matplotlib
*Launch Jupyter Notebook
   jupyter notebook "Acc102 Track2 2473732.ipynb"
*Run all cells – the notebook will automatically load Tweets.csv from the same folder.

## 6. Product Link / Demo Video
- GitHub Repository: https://github.com/XuzhenLiu102/Acc102-Track2-Airline-Sentiment-Data-Analysis
- Demo Video (1–3 min):[ACC102 Track Demo ((https://video.xjtlu.edu.cn/Mediasite/Play/0ae47c86b55d470a9b2b61c49b9bda5e1d)
- The video walks through the notebook, shows code execution, and explains key insights.

## 7. Limitations & Next Steps
### Limitations
1. Outdated data: The dataset is from 2015 and may not represent current airline service quality.
2. Limited analysis: No advanced text mining or natural language processing is used.
3. Descriptive only: The project does not include predictive modelling.
### Future Improvements
1. Use newer or real-time data from social media platforms.
2. Add text mining techniques such as word clouds and topic modelling.
3. Build a sentiment classification model to automate feedback analysis.

## 8. Author & Acknowledgements
- Author: Xuzhen Liu (ACC102, Track 2)
- Data source: Kaggle – Twitter US Airline Sentiment
- Tools: Python, pandas, matplotlib, Jupyter Notebook
