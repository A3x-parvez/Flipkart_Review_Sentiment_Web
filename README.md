<div align="center">
  <img src="https://github.com/a3x-parvez/flipkart_review_sentiment_web/raw/main/Product_Analysis_Frontend/img_vid_gifs/logo1.jpg" alt="Project Logo" width="80" style="border-radius:50%;"/>

  <h1 style="font-weight: 900; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #1e90ff; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">
    Flipkart Product Review Analyzer AI 
  </h1>
  <p>
    <strong>Tired of scrolling through endless product reviews? This tool does the heavy lifting for you! The Flipkart Product Review Analyzer is a web application that scrapes product reviews from Flipkart, analyzes the sentiment behind them, and presents a clear, visual summary.</strong>
  </p>

  <!-- Badges -->
  <p>
    <a href="https://github.com/a3x-parvez/flipkart_review_sentiment_web/blob/main/LICENSE"><img src="https://img.shields.io/github/license/a3x-parvez/flipkart_review_sentiment_web?style=for-the-badge" alt="License"></a>
    <a href="https://github.com/a3x-parvez/flipkart_review_sentiment_web/issues"><img src="https://img.shields.io/github/issues/a3x-parvez/flipkart_review_sentiment_web?style=for-the-badge" alt="Issues"></a>
    <a href="https://github.com/a3x-parvez/flipkart_review_sentiment_web/stargazers"><img src="https://img.shields.io/github/stars/a3x-parvez/flipkart_review_sentiment_web?style=for-the-badge" alt="Stargazers"></a>
  </p>
</div>

## 👤 Author
<!-- Add this in your HTML <head> to load the font -->
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<div align="center">
  <h2 style="font-family: 'Pacifico', cursive; font-size: 2.2em; color: #ff6d1eff; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">
  Rijwanool Karim
</h2>
  <p style ="font-weight: 900; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #651effff; text-shadow: 2px 2px 4px rgba(0,0,0,0.2); font-size: 1.2em">AIML Developer & AI Enthusiast</p>
  <p align="center" style="margin-top: 10px;">
  <a href="https://github.com/a3x-parvez" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/github/followers/a3x-parvez?style=social&label=GitHub" alt="GitHub Followers" height="30"/>
  </a>
  <a href="https://www.linkedin.com/in/rijwanool-karim" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=social&logo=linkedin" alt="LinkedIn" height="30"/>
  </a>
  <a href="https://my-portfolio-2-alpha-sandy.vercel.app/" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/Website-Visit-orange?style=social&logo=google-chrome" alt="Website" height="30"/>
  </a>
</p>

</div>


---

## 🌊 Workflow

This diagram illustrates the flow of data from the user to the final analysis:

<div align="center">
<img src="Product_Analysis_Frontend/img_vid_gifs/sentiment_analysis_project_flow.jpeg" alt="Workflow Diagram" width="700"/>
</div>

---

## ✨ Features

<details>
  <summary><strong>Click to expand features</strong></summary>

- 🌐 **Real-time Web Scraping**: Fetches the latest reviews for any Flipkart product in real-time.
- 🧠 **Advanced Sentiment Analysis**: Utilizes a powerful, pre-trained BERT model to accurately classify reviews as **positive**, **negative**, or **neutral**.
- 💻 **Interactive Frontend**: A user-friendly interface to input product URLs and view the analysis.
- 📊 **Data Visualization**: Displays a **pie chart** for an at-a-glance understanding of the overall sentiment.
- 📂 **Categorized Reviews**: Neatly organizes comments into **positive**, **neutral**, and **negative** sections for easy reading.
- 🌙 **Dark Mode**: A sleek dark mode for comfortable viewing.
</details>

---

## 🛠️ Tech Stack

<details>
  <summary><strong>Frontend</strong></summary>

- **HTML**: Structure of the web pages
- **CSS**: Styling and layout
- **JavaScript**: Interactivity and dynamic content
</details>

<details>
  <summary><strong>Backend</strong></summary>

- **Python**: Core programming language
- **Flask**: Lightweight web framework
- **Gunicorn**: WSGI server for deploying Flask apps
</details>

<details>
  <summary><strong>Libraries</strong></summary>

- **BeautifulSoup4 & Requests**: Web scraping
- **Pandas**: Data manipulation and analysis
- **NLTK**: Natural language processing
- **TensorFlow & Transformers**: Sentiment analysis model (BERT-based)
</details>

<br>

---

## 🗂️ Project Structure

```
.
├── Backend_API
│   ├── 3_epoch_sentiment_model
│   ├── 8_epoch_sentiment_model
│   ├── Main_functions.py
│   ├── requirements.txt
│   ├── Sentiment_API.py
│   └── s_models.py
├── Product_Analysis_Frontend
│   ├── img_vid_gifs
│   ├── index.html
│   ├── main.js
│   ├── script.js
│   └── style.css
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🤖 Model Details

**The sentiment analysis is powered by a BERT (Bidirectional Encoder Representations from Transformers) model. Specifically, this project uses a pre-trained `bert-base-uncased` model that has been fine-tuned for sequence classification. The model has been trained for 8 epochs to achieve higher accuracy in classifying sentiment.**

---

## 🏁 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Python 3.x
- pip

### Installation

1.  **Clone the repo**
    ```sh
    git clone https://github.com/A3x-parvez/Flipkart_Review_Sentiment_Web.git
    ```
2.  **Navigate to the Backend_API directory**
    ```sh
    cd Flipkart_Review_Sentiment_Web/Backend_API
    ```
3.  **Install Python packages**
    ```sh
    pip install -r requirements.txt
    ```
4.  **Run the Flask API**
    ```sh
    python Sentiment_API.py
    ```
5.  **Open the frontend**
    - Navigate to the `Product_Analysis_Frontend` directory.
    - Open the `index.html` file in your browser.

---

## 🎈 Usage

1.  Find a product on Flipkart and go to its reviews page.
2.  Copy the URL.
3.  Paste the URL into the input box in the web app.
4.  Select whether the page contains single or multiple reviews.
5.  Click "Analyze" and watch the magic happen!

---

## 🤝 Contributing

 - **Chayan Ghosh – Model Engineer**
 - **Rijwanool Karim – Backend & API Integration**
 - **Shouryadip Bera – Backend & Frontend Developer**
 - **Sk Mahiduzzaman – Data Cleaning & Research**
 - **Sayantan Saha – Data Cleaning & Research**
   
---
## 🧩 References

- Adarsh Kumar, K N Ganesh – Sentiment Analysis on Flipkart
- Medium, Arsha – NLP Preprocessing
- TechTarget – BERT Language Model
- PapersWithCode – Bidirectional LSTM

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more information.


<div align="center">
  Built with ❤️ by Rijwanool Karim <span style="margin: 0 5px;">in collaboration with</span> Chayan Ghosh
</div>

