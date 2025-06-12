# Fake-News_Detection
# 📰 Fake News Detection using Machine Learning

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify news articles as either **fake** or **real**. It helps reduce misinformation spread by providing a quick and reliable way to verify the authenticity of online news content.

##🚀 Project Features
Clean and process news text
TF-IDF for feature extraction
Fast ML model (PassiveAggressiveClassifier)
Shows accuracy, precision, recall, F1-score
Real-time fake news prediction
Ready for Streamlit/Flask
Easy to expand to images, languages, and mobile
Can be used in browser or app

## 📁 Project Structure
```
📄 fake_news_detection.py              # Core ML pipeline
📄 fake_news_app.py                   # Streamlit Web App
📊 Detailed_AI_Project_Fake_News_Detection.pptx  # Project Presentation
📄 README.md                          # Project Overview (this file)
📄 LICENSE                            # Open source license
```

## 📌 Technologies Used
- Python
- Pandas, Numpy, Scikit-learn, NLTK
- PassiveAggressiveClassifier
- Streamlit / Flask (for deployment)

## 🧪 Model Performance
- **Accuracy:** 95.6%
- **Precision:** 95.1%
- **Recall:** 94.3%
- **F1-Score:** 94.8%

## 🧠 Example Usage
```python
sample = "The government passed a new education bill today."
predict_news(sample)  # Output: 'REAL'
```

## 📊 Dataset
Kaggle: [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

## 🛠️ Future Improvements
Support for multiple languages
Detect fake images and videos
Browser plugin for live news checks
Mobile app with real-time alerts
User feedback to improve accuracy
Social media fake news detection
Explainable results for each prediction

## 📎 License
This project is open-source and free to use under the MIT License.
