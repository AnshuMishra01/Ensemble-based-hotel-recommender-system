# Ensemble-based-hotel-recommender-system
An ensemble-based hotel recommender system using sentiment analysis and aspect categorization of hotel reviews Research Paper by Biswarup Ray, Avishek Garain, Ram Sarkar


The researcher in this study focused on developing a hotel recommendation system using sentiment analysis of online reviews and aspect-based review categorization. The key aspects of the research, techniques used, results, and dataset information are summarized as follows:

### Research Objective:

Develop a hotel recommendation system based on sentiment analysis and aspect categorization of online reviews.

Utilize BERT models for sentiment analysis and Random Forest classifier for classification tasks.

Categorize reviews based on aspects like cleanliness, service, location, etc.

### Techniques Used:

BERT Models: Leveraged Bidirectional Encoder Representations from Transformers for sentiment analysis of hotel reviews.

Random Forest Classifier: Employed for sentiment classification based on textual features and BERT embeddings.

Aspect Categorization: Utilized fuzzy string matching and cosine similarities for grouping reviews based on predefined aspects. Aspect Categorization is a crucial step in the hotel recommendation system as it involves grouping reviews based on specific aspects or features of the hotels that are frequently mentioned in the reviews. By categorizing reviews into aspects such as cleanliness, service, location, and amenities, the system can provide more detailed and targeted recommendations to users based on their preferences.

Ensemble Learning: Combined multiple models to enhance system accuracy and performance.

### Results:

Sentiment Analysis: Achieved a test accuracy of 92.36% using a combination of BERT and textual features.

Aspect Categorization: Formed compact clusters of categorized reviews based on aspects like cleanliness, service, and location.

Model Performance: Attained a Macro F1-score of 84%, outperforming state-of-the-art models in sentiment analysis and aspect categorization.

### Dataset:

Source: Online hotel reviews crawled from Tripadvisor.com.

Features: Included Word2Vec embeddings, TF-IDF values, subjectivity scores, and other textual features.

Preprocessing: Data cleaning, tokenization, and feature extraction performed on the review dataset.

Aspect Categories: Reviews categorized into predefined aspects like location, cleanliness, service, etc.

### Steps of Preprocessing

Data Cleaning:

Remove any irrelevant information such as special characters, URLs, and numbers.
Convert text to lowercase to ensure consistency.
Handle misspelled words and typographical errors if necessary.

Tokenization:

Tokenize the text data into individual words or tokens.
Consider using libraries like NLTK or spaCy for tokenization.

Stopword Removal:

Remove common stopwords (e.g., "and," "the," "is") that do not contribute significantly to aspect categorization.
Stemming or Lemmatization:

Reduce words to their base or root form to normalize the text data.
Stemming (e.g., converting "running" to "run") or lemmatization (e.g., converting "better" to "good").

Aspect Identification:

Identify key aspects or features relevant to hotel reviews, such as cleanliness, service, location, amenities, etc.
Create a list of aspect keywords or terms associated with each aspect.

Aspect Extraction:

Extract sentences or phrases from reviews that mention specific aspects.
Use keyword matching or NLP techniques to identify aspect-related content.
Aspect Categorization:

Group reviews into predefined categories based on the identified aspects.
Utilize fuzzy string matching or cosine similarities to calculate the similarity between reviews and aspect keywords.

Aspect Clustering:

Cluster reviews based on the similarity of aspect-related content.
Create compact clusters of reviews that share common aspects.

Overall, the researcher successfully implemented a hotel recommendation system that effectively analyzed sentiment, categorized reviews based on aspects, and provided personalized recommendations using advanced NLP techniques and machine learning models. The results demonstrated high accuracy and performance compared to existing models, showcasing the effectiveness of the proposed approach in the domain of hotel recommendation systems.

#### NOTE -  I will be deploying the model by the end of June, 2024
