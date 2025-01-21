# JKT48 New Era Special Performance Video – Benang Sari, Putik, dan Kupu-Kupu Malam

# Sentiment Analysis

This project conducts sentiment analysis on the comments from the YouTube video "[JKT48 New Era Special Performance Video – Benang Sari, Putik, dan Kupu-Kupu Malam](https://www.youtube.com/watch?v=UUGY64rPLxo)." The analysis categorizes sentiments into three classes: positive, neutral, and negative, assessing audience reactions to this specific performance. Utilizing both pre-trained BERT model and lexicon-based approaches for data labelling, providing insights into viewer engagement with the video. The project also involves building machine learning models to predict comment sentiments.

# Machine Learning Models
To enhance sentiment classification, I built various models using a combination of algorithms, including Support Vector Machines (SVM), Random Forest (RF), and deep learning. Feature extraction techniques employed include TF-IDF, Bag of Words (BoW), and tokenization. The dataset was split using proportions of 80/20 and 70/30 for training and testing. My target accuracy was 92%, and I achieved 93% with the deep learning model, while the other models reached at least 88%.

# Notebooks

1.  `1_get_youtube_comments.ipynb`: Retrieve a specific YouTube comments dataset via YouTube API call.
2.  `2_sentiment_labelling_bert.ipynb`: Label the dataset using a pre-trained BERT model for sentiment analysis in Bahasa Indonesia (results are not as expected)
3.  `3_sentiment_analysis_bert.ipynb`: Conduct a comprehensive sentiment analysis on the labeled dataset using a pre-trained BERT model.
4.  `4_sentiment_classification_bert.ipynb`: Build ML models to predict comment sentiments using the labeled dataset trained by a pre-trained BERT model (low performance observed).
5.  `2_sentiment_labelling_lexicon.ipynb`: Label the dataset using positive and negative lexicons for Bahasa Indonesia and some English words.
6.  `3_sentiment_analysis_lexicon.ipynb`: Perform comprehensive sentiment analysis on the labeled dataset using a lexicon approach.
7.  `4_sentiment_classification_bert.ipynb`: Build ML models to predict comment sentiments using the labeled dataset trained by the lexicon approach (high performance observed).

# Note for Dicoding Reviewer

Please note that my final submission that meets the criteria includes notebooks number 1, 5, 6, 7. The other notebooks are included as documentation of the entire process to meet the criteria.

## Installation

This project requires **Python 3.11**. Please ensure you have Python 3.11 installed.
1.  Clone the repository.
2.  Create a virtual environment with Python 3.11.
3.  Install the dependencies:  
    ```bash  
    pip install -r requirements.txt