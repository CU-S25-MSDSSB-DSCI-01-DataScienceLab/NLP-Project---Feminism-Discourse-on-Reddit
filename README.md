# Natural Language Processing of Feminist Discourse on Reddit: Patterns, Sentiment, and Polarization

**Objective**: This report uses natural language processing (NLP) techniques to analyze the dynamics of feminist discourse in key Reddit communities. The goal is to map polarization and identify recurring themes.

**Methods**: 
We collected and analyzed thousands of posts and comments from pro-feminist (e.g., r/Feminism, r/TwoXChromosomes) and anti-feminist (e.g., r/MensRights) subreddits. Using automated sentiment analysis and topic modeling, we identified emotional tone (positive/negative/neutral) and key themes on both sides of the feminist ideological spectrum.

**Implications & Value**:
This study highlights how automated text analysis can paint a comprehensive picture of social online debates and inform educators, community moderators, and researchers about the nature and intensity of ideological divisions on social media.

# Project File

**Main Notebook** 'Feminism Reddit NLP.ipynb'
The core Jupyter Notebook that scrapes, processes, analyzes, and visualizes Reddit posts and comments. 

# Data Files

'feminism_praw_posts_comments.csv' 
Raw dataset of Reddit posts and associated comments retrieved via the praw API.

'feminism_posts_tagged_by_topic.csv'
Posts annotated with topic categories either manually or via keyword/topic modeling.

'feminism_posts_with_bert_sentiment.csv'
Original posts with BERT-derived sentiment scores.

'feminism_comments_as_posts.csv'
Reddit comments reformatted and analyzed as standalone "posts" for comparative sentiment/topic analysis.

feminism_comments_with_bert_sentiment.csv
Comments labeled with sentiment (positive, neutral, negative) using a BERT-based classifier.

