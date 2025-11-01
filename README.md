# Sentimental-Analysis-Of-Twitter-Data-Using-RNN
A deep learning project for tweet sentiment &amp; emotion classification using Recurrent Neural Networks. Includes text preprocessing, emotion mapping, confidence-based rule correction, and CSV output generation.

 🧠 Tweet Sentiment & Emotion Analysis using RNN

This project performs sentiment and emotion classification on tweets using a Recurrent Neural Network (RNN).
The model identifies emotions like Happy, Sad, Angry, Relaxed, Excited, Fearful, etc., and converts them into Positive / Negative / Neutral sentiment.

The project includes automatic text cleaning, emotion mapping, deep learning-based sentiment detection, and a rule-based fallback system for better accuracy.

📂 Features

Automatic text cleaning & preprocessing

Auto-detect tweet & label columns

RNN-based deep learning model

Rule-based logic for low-confidence predictions

Emotion category + Sentiment label

Confidence score for each prediction

Saves final results as CSV

🧪 Tech Stack
Category	Tools
Language	Python
Framework	TensorFlow / Keras
Tools	Google Colab
Libraries	Pandas, NumPy, Scikit-Learn
🚀 How to Run

Clone or download this repository

Open the notebook in Google Colab

Upload your dataset (Tweets.csv)

Run the notebook cells

Get sentiment results in CSV output

📁 File Structure
📦 sentiment-analysis-rnn
 ┣ 📓 sentiment_analysis_rnn.ipynb
 ┣ 📄 requirements.txt
 ┣ 📂 results/ (optional screenshots & output)
 ┗ 📄 README.md

📊 Output Example
Tweet	Emotion	Sentiment	Confidence
Feeling great today!	Happy	Positive	0.92
I am so frustrated	Angry	Negative	0.88
Nothing special	Neutral	Neutral	0.64
📌 Future Enhancements

Streamlit/Flask web UI

FastAPI model deployment

Upgrade to LSTM / GRU / Transformer / BERT

Real-time sentiment dashboard

👥 Team Members
Name	Roll Number
A.V.M. Vijay Sagar	2310030152
Neelakantam Akhil	2310030159
Ejaz Ahmed	2310030167
S. V. Ruchitha	2310030166
✨ Acknowledgment

This project was developed as part of an academic learning initiative in Deep Learning and Natural Language Processing.
