# Brainwave-QA
Python tool with Streamlit interface that automatically generates a question and answer (Q&amp;A) dataset from the textual content of a website. Uses Web Scraping for extraction and the OpenAI API to create customizable Q&amp;As by tokens, style and quantity. Exports the result in CSV.

---

# 🧠 Brainwave QA

This project is an automated Python tool with a **Streamlit** interface that:

- Accepts a **website URL** as input;
- Crawls all pages within the domain and extracts **relevant textual content**;
- Uses the **OpenAI API** to automatically generate a **question-and-answer (Q&A) dataset** based on the extracted content;
- Allows configuration, via a chat with the model, of parameters like:
  - Maximum tokens per answer;
  - Style of questions;
  - Number of Q&As per section;
- Exports the results as a **CSV file**, ready for NLP or Machine Learning tasks.

---

## 🚀 Features

- ✅ Automated content extraction via Web Scraping
- ✅ Q&A generation using OpenAI GPT models
- ✅ Interactive configuration using Streamlit
- ✅ Dataset export in `.csv` format

---

## 📦 Requirements

- Python 3.9+
- `openai` library
- `beautifulsoup4`, `requests`
- `pandas`, `dotenv`
- `streamlit`

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/brainwave-qa.git
cd brainwave-qa
pip install -r requirements.txt
```

---

## 🔑 Configuration

Create a `.env` file with your OpenAI API key:

```env
OPENAI_API_KEY=sk-...
```

---

## 🧪 Usage Example

Run the Streamlit interface:

```bash
streamlit run main.py
```

After entering a URL, the system will:
- Extract the content;
- Ask your preferences for Q&A generation;
- Automatically generate and save the dataset.

---

## 📁 CSV Structure

| context | question | answer |
|---------|----------|--------|
| Text extracted from the site | Generated question | Generated answer |

---

## 🛠️ In Development

- [ ] Interactive prompt configuration
- [ ] Support for multiple export formats
- [ ] Automatic internal link crawling

---

## 👨‍💻 Author

Project developed by **Lucas Almeida** with support from ChatGPT for intelligent automation.

