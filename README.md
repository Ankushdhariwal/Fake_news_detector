Fake News Detection System 🔍
A machine learning model to classify news articles as real or fake using NLP techniques.

Screenshot 2025-05-14 040727

Screenshot 2025-05-14 040702

📥 Download Links
Pre-trained Models:

[Model (Pickle)]

((https://drive.google.com/file/d/1ZW2MI_4XIZe8bMqO5q_SB4X-LpxsUWDr/view?usp=sharing)) - (Name it as fake_news_model.pkl)

[TF-IDF Vectorizer]

((https://drive.google.com/file/d/10GcHo64vqYjtNXGT3fSOLwiwwGxT_CoT/view?usp=sharing)) - (Name it as tfidf_vectorizer.pkl)

Dataset: https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset?select=Fake.csv (True and Fake both datasets)

🛠️ Setup
Conda Environment Setup!
conda env create -f environment.yml
conda activate fake_news_detection
python -m nltk.downloader punkt stopwords wordnet!
Other Resources
(https://drive.google.com/file/d/10GcHo64vqYjtNXGT3fSOLwiwwGxT_CoT/view?usp=sharing)

To run
Download the model and vectorizer files and then you can upload it to the running streamlit app and you're done
