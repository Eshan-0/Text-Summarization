✅ COPY EVERYTHING BELOW INTO README.md
# 📄 PDF Summarizer & Question Answering App using NLP

A Streamlit-based Natural Language Processing application that extracts text from PDF documents, generates concise summaries, and allows users to ask intelligent questions based on the document content.

This project demonstrates practical NLP techniques such as TF-IDF scoring, sentence ranking, and semantic similarity.

---

## 📸 Application Preview

![PDF Summarizer Interface]

---

## 🚀 Key Features

- Upload PDF documents (up to 100 pages processed)
- Automatic text extraction from PDF
- NLP-based text summarization
- TF-IDF sentence importance scoring
- Word-limit controlled summaries
- Question Answering using semantic similarity
- Interactive Streamlit web interface

---

## 🧠 NLP Techniques Implemented

- Sentence tokenization  
- Word frequency analysis  
- TF-IDF vectorization  
- Feature-based ranking  
- Stopword removal  
- spaCy semantic similarity for QnA  
- POS tagging and linguistic processing  

---

## 🛠 Technology Stack

| Category | Tools |
|---------|------|
| Language | Python |
| Frontend | Streamlit |
| NLP | NLTK, spaCy |
| ML | Scikit-learn |
| PDF Handling | PyPDF2 |
| Data | Pandas |

---

## ⚙ Installation & Running the App

### Step 1: Install dependencies

```bash
pip install streamlit nltk spacy scikit-learn PyPDF2 pandas threadpoolctl

Step 2: Download spaCy model
python -m spacy download en_core_web_sm

Step 3: Run the application
streamlit run Text\ summarization.py

📊 Project Workflow

User uploads a PDF

Text is extracted using PyPDF2

Sentences are processed and cleaned

Important sentences are scored using TF-IDF and statistical features

Top-ranked sentences form the summary

User questions are matched using semantic similarity

📈 Use Cases

Research papers summarization

Business document analysis

Study material review

Legal and technical document understanding

🔮 Future Improvements

Deep learning summarization models (BERT, T5)

Multi-document summarization

Highlight key phrases

Export summary as PDF/Word

Advanced QnA with transformers

👨‍💻 Author

Eshan Chaudhari
Final-Year B.Tech AI Student
Aspiring Data Analyst & NLP Engineer

⭐ If you like this project, consider starring the repository!


---<img width="1897" height="855" alt="streem lite app screen shot" src="https://github.com/user-attachments/assets/a2cff22c-60e8-48e3-bdfb-4e0adea71819" />


