# Website Summarizer with LLM

This project is a Jupyter Notebook that extracts the text from a given website and summarizes it using a large language model (LLM) via the `ollama` library. The summary is presented in clean Markdown format, excluding navigation and non-relevant content.

---

## 📌 Features

- Scrapes website content using `requests` and `BeautifulSoup`
- Cleans the text (removes scripts, images, styles, inputs)
- Uses LLaMA 3.2 model via `ollama` to generate summaries
- Displays result in Markdown format within the notebook

---

## 🚀 How It Works

1. **Input a website URL**
2. The notebook:
   - Fetches and parses the HTML
   - Extracts the main textual content
   - Sends the cleaned text to an LLM
   - Displays a readable Markdown summary

---

## 🛠️ Requirements

You’ll need these Python packages installed:

```bash
requests
beautifulsoup4
ollama
IPython
