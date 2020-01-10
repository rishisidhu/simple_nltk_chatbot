# simple_nltk_chatbot
A retrieval based chatbot based on NLTK library and trained using MaxEnt classifier

# Steps to run
1. Go to any FAQ website and copy all of the questions & answers there into a text file
2. Or use one of the files in the repo
3. Change the FILENAME constant to this file and run

# Code Flow
1. Subject a dataset (NPS Chats in our case) to NLP transformations like stemmatization, lemmatization, tokenization etc.
2. Use this to train a classifier (Try both Naive Bayes and MaxEnt)
3. Scrape Q&A text from the web and paste it into .txt file
4. Use the classifier to separate questions from the text 
5. Add questions into a dictionary as keys and their answers as values
6. Accept user input and apply the same transformations as in step 1 
7. Match user query with the question in the dictionary using TF-IDF
8. Display the corresponding answer
