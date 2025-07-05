# AI Web Scraper

An AI-powered web scraper designed to extract and parse specific information from websites. This project utilizes **Langchain**, **Selenium**, and **BeautifulSoup** to scrape, clean, and process web content. Users can input a website URL, scrape its content, and use AI to extract relevant information based on their query.

---

## 🚀 Project Overview

This AI web scraper allows you to:

✅ Input a website URL  
✅ Scrape its DOM content  
✅ Clean the HTML data  
✅ Use AI models to extract specific information based on your query  

The integration with Langchain and Ollama enables advanced parsing and understanding of web content, making this scraper highly versatile for diverse data extraction needs.

---

## 🛠️ Technologies Used

- **Python 3.13.0**
- **Streamlit** — UI for the web app
- **Langchain** — Framework for AI-driven parsing
- **Ollama (Langchain model)** — LLM-based data extraction
- **Selenium** — Scraping dynamic web pages
- **BeautifulSoup4** — HTML parsing & cleanup
- **lxml** — Fast XML/HTML parsing
- **html5lib** — Alternative HTML parser
- **python-dotenv** — Manage environment variables

---

## 💻 Installation Instructions

Follow these steps to set up the project locally:

1. **Clone the repository**

    ```bash
    git clone https://github.com/anoshandrews/AI-Web-Scraper.git
    ```

2. **Navigate into the project directory**

    ```bash
    cd ai-web-scraper
    ```

3. **Install dependencies**

    Ensure you have `pip` installed, then run:

    ```bash
    pip install -r requirements.txt
    ```

---

## 🧑‍💻 Usage

### Running the Web Scraper

Start the web app using Streamlit:

```bash
streamlit run main.py
```

Then:

1. Enter a website URL in the text input field.
2. Click **Scrape Site** to fetch the website content.
3. View raw and cleaned DOM content displayed in expandable text boxes.
4. To extract specific data:
   - Enter a description of what you want to extract in the "Parse Content" section.
   - Click **Parse Content**.
5. The AI model will process your request and return the extracted information.

---

## ✨ Features

- **Web Scraping:** Uses Selenium to load dynamic sites and extract complete HTML DOMs.
- **Content Cleaning:** Strips scripts, styles, and excessive whitespace.
- **AI Parsing:** Langchain + Ollama enables context-aware content parsing based on user queries.
- **User Interface:** Clean, simple UI built with Streamlit.

---

## 🤝 Contributing

Contributions are welcome!

To contribute:

1. Fork the repo.
2. Create a new branch:

    ```bash
    git checkout -b feature-name
    ```

3. Make your changes and commit:

    ```bash
    git commit -am 'Add new feature'
    ```

4. Push your changes:

    ```bash
    git push origin feature-name
    ```

5. Submit a pull request.

---

## 🙏 Acknowledgements

- **Selenium** — Automating browsers for complex scraping.
- **BeautifulSoup** — Parsing HTML content.
- **Langchain** — Powerful tools for LLM-driven text parsing.
- **Ollama** — LLMs for extracting structured info from web pages.

---

Feel free to customize any section to fit your project better!
