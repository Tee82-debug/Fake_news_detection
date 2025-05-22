
# 📰 Fake News Detection App

A simple web application that detects whether a news article is **Real** or **Fake** using a machine learning model built with **Scikit-learn**, **Pandas**, and deployed via **Streamlit**.

---

## 🚀 Features

- Classifies news content as real or fake
- Interactive web interface built with Streamlit
- Uses a trained Logistic Regression model with TF-IDF vectorization

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas
- Joblib

---

## 📁 Project Structure

fake_news_detection/
│
├── app.py               # Streamlit application
├── model.pkl            # Trained ML model
├── vectorizer.jb        # TF-IDF vectorizer
├── requirements.txt     # Project dependencies
└── README.md            # Project documentation

---

## 🔧 Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/fake_news_detection.git
cd fake_news_detection

2.  Create a Virtual Environment (Optional)

    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate

3.	Install Dependencies

    pip install -r requirements.txt

4.	Run the App

    streamlit run app.py


⸻

 Model Info
	•	Vectorizer: TF-IDF
	•	Classifier: Logistic Regression (Scikit-learn)
	•	Serialized with Joblib

⸻

License

This project is licensed under the MIT License.

⸻

 Acknowledgments
	•	Dataset: Kaggle - Fake and Real News Dataset
	•	Streamlit for effortless UI
