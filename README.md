
# 🕵️‍♂️ Fake Review Detection for Amazon

This project is a Flask web application that detects fake (computer-generated) reviews for Amazon products. It uses machine learning models (Word2Vec and SVM) to classify reviews as real or fake based on their text and rating.

<span style="color:darkblue; font-weight:bold;">Check out a demo on</span>  
[![YouTube](https://img.shields.io/badge/Watch%20on-YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=gNCwOYrvG_U)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![Gensim](https://img.shields.io/badge/Gensim-00A86B?logo=gensim&logoColor=white)

---

## 🚀 Features
- 🔎 **Detect Fake Reviews**: Classifies Amazon reviews as Real or Fake  
- 🤖 **AI-Powered Summaries**: Generates concise summaries using Gemini API  
- 🌐 **Web Scraping**: Fetches reviews directly from Amazon product pages  
- 💡 **User-Friendly Interface**: Modern design with Tailwind CSS  
- 🔒 **Enhances Shopping Trust**: Makes online shopping safer and smarter

## 🛠️ Built With
- **Python** (Flask, Scikit-learn, Gensim)  
- **HTML / JavaScript** (Tailwind CSS)  
- **Gemini API** (AI summarization)  
- **Web Scraping tools**
  
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

## 🚚 Getting Started

### Prerequisites
- Python 3.x  
- pip (Python package manager)  

### Installation
```bash
git clone https://github.com/ramkaranpatel4661/Fake-Review-Detection-of-Amazon.git
cd Fake-Review-Detection
pip install -r requirements.txt

### Run the App

```bash
python app.py

Open your browser and go to:
http://localhost:5000
```

## 🎯 Usage
- Enter or paste an Amazon product URL.
- The app scrapes and analyzes reviews.
- Results show which reviews are **Real** or **Fake**.
- Get AI-powered summaries for quick insights.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
Feel free to check the **issues** page.

---

## 📄 License
This project is licensed under the **MIT License**.

---

## 🙏 Acknowledgements
- Scikit-learn  
- Gensim  
- Flask  
- Tailwind CSS  
- Gemini API  
- Inspired by the need for trustworthy online shopping!
