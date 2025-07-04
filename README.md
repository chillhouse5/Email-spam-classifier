# Email-spam-classifier
![image](https://github.com/user-attachments/assets/0b8281bb-9335-4b33-a2b0-5a11e0a9250b)

In today’s digital age, users receive countless messages via SMS and email — many of which are spam. Manually sorting these is inefficient and risky. Spam classification systems use machine learning and NLP techniques to automatically detect and block unwanted or malicious content, improving user safety and experience.

# How It Works
The system first preprocesses input text by lowercasing, tokenizing, removing stopwords and punctuation, and applying stemming. The cleaned message is then vectorized using TF-IDF, which weighs words based on their importance. A trained Multinomial Naive Bayes model uses these vectors to classify the message as spam or not. Both the model and vectorizer are stored with pickle and integrated into a lightweight, real-time Streamlit app where users can input a message and instantly see the prediction.

