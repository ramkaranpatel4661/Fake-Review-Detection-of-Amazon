
# 🕵️‍♂️ Fake Review Detection for Amazon

This project is a Flask web application that detects fake (computer-generated) reviews for Amazon products. It uses machine learning models (Word2Vec and SVM) to classify reviews as real or fake based on their text and rating.

<span style="color:darkblue; font-weight:bold;">Check out a demo on</span>  
[![YouTube](https://img.shields.io/badge/Watch%20on-YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=gNCwOYrvG_U)

## 🚀 Features
- Scrapes reviews from a given Amazon product URL
- Preprocesses review text (cleaning, lemmatization, stemming)
- Classifies reviews using pre-trained Word2Vec and SVM models
- Displays results in a user-friendly web interface

## 📁 Project Structure
```
app.py                # Main Flask application
model.py              # Model loading and classification logic
preprocessing.py      # Text preprocessing functions
scraper.py            # Scrapes reviews from Amazon
requirements.txt      # Python dependencies
row_data.csv          # Sample data
Data/                 # Data folder
statics/              # Static files (CSS, JS)
templates/            # HTML templates
```

## 🛠️ Installation
1. Clone the repository:
   ```sh
git clone https://github.com/ramkaranpatel4661/Fake-Review-Detection-of-Amazon.git
cd Fake-Review-Detection-of-Amazon
   ```
2. Install Python dependencies:
   ```sh
pip install -r requirements.txt
   ```
3. Download NLTK data (required for text preprocessing):
   ```python
import nltk
nltk.download('punkt')
   ```
   Or run:
   ```sh
python -c "import nltk; nltk.download('punkt')"
   ```

## ▶️ Usage
1. Start the Flask server:
   ```sh
python app.py
   ```
2. Open your browser and go to `http://localhost:5000`
3. Enter an Amazon product URL to analyze reviews

## 📝 Notes
- Make sure you have the pre-trained models (`word2vec_model.model`, `SVM_model.pkl`) in the correct location if required by your code.
- Static files are served from the `statics/` folder.
- HTML templates are in the `templates/` folder.

## 📄 License
This project is for educational purposes.
