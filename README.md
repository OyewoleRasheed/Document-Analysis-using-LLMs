````markdown
# 📄 Document Analysis using LLMs with Python

This project replicates the tutorial from [AmanXAI](https://amanxai.com/2024/10/21/document-analysis-using-llms-with-python/), demonstrating how to build a simple document analysis pipeline using **Large Language Models (LLMs)** in Python.

The script allows you to upload any text-based document (PDF, TXT, DOCX), extract its content, and use an LLM (such as OpenAI's GPT models) to perform intelligent analysis — including summarization, keyword extraction, and question answering.

---

## 🧠 Features

- 📄 PDF, DOCX, and TXT file support
- 📚 Text extraction from documents
- 🤖 Natural Language Processing with LLMs
- 📝 Summarization, Q&A, and keyword extraction
- 💬 Conversational interaction with the document content

---

## 🛠 Requirements

- Python 3.8+
- OpenAI API key
- `openai`
- `PyMuPDF` (for PDFs)
- `python-docx` (for DOCX)
- `tkinter` (for file upload GUI)
- `tiktoken` (optional, for token management)

Install dependencies:

```bash
pip install openai python-docx pymupdf tiktoken
````

---

## 🚀 How to Run

1. **Add your OpenAI API key**
   Create a `.env` file or set the API key in the script:

   ```python
   openai.api_key = "your-api-key"
   ```

2. **Run the script**

   ```bash
   python document_analysis.py
   ```

3. **Choose a file** when prompted and select the type of analysis (summarize, extract keywords, ask questions, etc.).

---

## 📂 Project Structure

```
├── document-analysis-using-llms.ipynb     # Main script
├── google_terms_of_service_en_in                   # sample documents
├── README.md                # Project documentation
```

---

## 💡 Example Use Cases

* Summarize large PDFs in seconds
* Extract key topics from meeting notes
* Ask questions about legal documents or reports
* Use as a document chatbot interface

---

## ✅ Acknowledgments

Based on the tutorial by [AmanXAI](https://amanxai.com/2024/10/21/document-analysis-using-llms-with-python/). Built using OpenAI’s GPT API and Python’s file handling tools.

---

## 📝 License

This project is intended for educational and non-commercial use only.

```
