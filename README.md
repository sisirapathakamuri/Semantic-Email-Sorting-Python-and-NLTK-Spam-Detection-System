# email-spam-ham-classification
Email Spam/Ham Classification System
This Python-based email classification system is designed to effectively distinguish between spam and ham emails. It incorporates several advanced techniques and libraries, including Natural Language Toolkit (NLTK), to optimize its performance.

Key Technical Features:
Text Pre-processing:
Extensive text pre-processing is applied to the email content. This includes removing special characters, converting text to lowercase, and handling various forms of whitespace, ensuring consistent and clean data for classification.
Tokenization:
The NLTK library is utilized to tokenize the email content. Tokenization breaks down the text into individual words and phrases (tokens), a fundamental step in feature extraction for classification.
Parts-of-Speech Extraction:
The system employs NLTK's part-of-speech tagging to extract grammatical information from the text. This technique provides additional context for classification, aiding in the distinction between spam and ham.
Stop Word Filtering:
Common stop words are filtered out to eliminate noise and reduce feature dimensionality, which enhances the efficiency of the classification process.
Negation Representation:
The system takes into account negations in the text. Recognizing and representing negations is crucial for accurate classification, as it helps in capturing the shift in sentiment or intent in the email content.
Model Training and Evaluation:
To achieve commendable accuracy, extensive model training and evaluation were performed. The following steps were taken:

Classifier Selection: We experimented with various classifiers, but the Naïve Bayes classifier emerged as the top performer. Its simplicity and effectiveness in text classification make it an ideal choice.

Feature Sets: We carefully crafted comprehensive feature sets, incorporating tokenized text, parts-of-speech, and negation representation. These features were crucial in achieving a 93% accuracy rate.
![image](https://github.com/sisirapathakamuri/email-spam-ham-classification/assets/149529159/5c278789-5e49-465d-97ed-be6639207e7b)
