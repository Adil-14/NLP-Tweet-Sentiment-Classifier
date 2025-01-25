# NLP-Tweet-Sentiment-Classifier

This project is about classifying tweets as positive or negative using a Support Vector Machine (SVM). I focused on processing the text, extracting features, and training a model to predict sentiment.

## **What’s This About?**
The goal was to take a bunch of tweets, clean and process them, and then use an SVM model to figure out if they’re positive or negative. Here’s what I worked on:
- Preprocessing tweets to remove unnecessary stuff and turn them into clean text.
- Creating features from the text, like word frequencies (bag-of-words) and importance (TF-IDF).
- Training the SVM on the dataset and testing how well it works.
- Analyzing where the model got things wrong and trying to improve it.

## **Dataset**
The dataset contains tweets labeled as:
- **Positive**: Tweets with a positive sentiment.
- **Negative**: Tweets with a negative sentiment.

## **What I Did**
1. **Preprocessing**:
   - Cleaned the tweets by removing things like stopwords, special characters, and URLs.
   - Tokenized the text and normalized it (e.g., converting to lowercase).
2. **Feature Extraction**:
   - Used bag-of-words to turn text into numbers.
   - Tried out other techniques like TF-IDF and n-grams to see what worked best.
3. **Model Training**:
   - Ran 10-fold cross-validation with the SVM and measured performance with metrics like accuracy, precision, recall, and F1-score.
4. **Error Analysis**:
   - Looked at false positives and negatives to understand where the model struggled.
5. **Improving Performance**:
   - Made tweaks to preprocessing, feature selection, and SVM parameters to boost the model’s accuracy.

