# Tweet Sentiment's Impact on Stock Returns Analysis

## Overview
This repository contains a comprehensive data science project analyzing the relationship between Twitter sentiment and stock returns. The project includes a Jupyter notebook with data cleaning, exploratory analysis, feature engineering, and machine learning model building, along with a Streamlit dashboard for interactive visualization. The dataset, sourced from Kaggle, comprises approximately 1.4 million tweets linked to stock performance metrics.

## Project Details
- **Dataset**: [Tweet Sentiment's Impact on Stock Returns](https://www.kaggle.com/datasets/thedevastator/tweet-sentiment-s-impact-on-stock-returns)
  - Shape: (1,395,450, 14)
  - Key Columns: TWEET, STOCK, DATE, LAST_PRICE, 1_DAY_RETURN, 2_DAY_RETURN, 3_DAY_RETURN, 7_DAY_RETURN, PX_VOLUME, VOLATILITY_10D, VOLATILITY_30D, LSTM_POLARITY, TEXTBLOB_POLARITY
- **Tools**: Python, Jupyter Notebook, Streamlit, pandas, sklearn, matplotlib, seaborn, plotly
- **Models**: Regression (Linear, SVM, DT, RF, AB, ANN) and Classification (Logistic, SVM, DT, RF, AB, ANN)

## Hosting
- **Google Colab**: Interactive version of the notebook is available [here](https://colab.research.google.com/drive/1YsgBPirhSuGO4mXYXK6x-2MtqZW7_T1Y#scrollTo=cbf17cb6-5f25-4bb7-bce4-866d28f4c662). Run cells to explore the analysis live.
- **Streamlit Dashboard**: Hosted version will be available [here](https://tweet-sentiment-impact-on-stock-returns-dashboard-7mbtw9qmw8xh.streamlit.app/) once deployed.

## Insights
- Weak but positive correlation between tweet sentiment and short-term stock returns (1-3 days).
- LSTM and TextBlob sentiments complement each other; averaging improves signals.
- Market factors (volatility, volume) are more influential than sentiment.
- Random Forest models outperform others for both regression and classification.

## Acknowledgments
- Dataset from Kaggle user "thedevastator".