# chatbot-sentiment-analysis


This is an end-to-end chatbot project that performs **sentiment analysis** on user messages. It uses NLP techniques to classify user input as positive, negative, or neutral and respond accordingly.

## 🚀 Features
- Sentiment classification (positive, negative, neutral)
- Real-time chatbot responses
- Trained using NLP libraries like NLTK / TextBlob / Transformers
- Web interface (Streamlit or Flask-based)

## 🛠️ Technologies
- Python
- NLTK / TextBlob / Hugging Face Transformers
- Streamlit or Flask (frontend)
- Scikit-learn (for model building)

## 🖥️ Run Locally

```bash
git clone https://github.com/your-username/chatbot-sentiment-analysis.git
cd chatbot-sentiment-analysis
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py  # or python app.py if using Flask



chatbot-sentiment-analysis/
│
├── app.py              # Main application
├── model/              # Pre-trained model or training code
├── templates/          # HTML files (Flask)
├── static/             # CSS/JS files
├── requirements.txt    # Python dependencies
└── README.md
