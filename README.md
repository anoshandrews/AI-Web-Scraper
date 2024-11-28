AI Web Scraper
An AI-powered web scraper designed to extract and parse specific information from websites. This project utilizes Langchain, Selenium, and BeautifulSoup to scrape, clean, and process web content. You can input a website URL, scrape its content, and use AI to extract relevant information based on your query.

Table of Contents
Project Overview
Installation Instructions
Usage
Features
Technologies Used
Contributing
License
Acknowledgements
Project Overview
This project is an AI web scraper that allows users to input a website URL, scrape its DOM content, clean it, and use AI models to extract information based on a user’s query. The AI model (via Langchain and Ollama) allows for advanced parsing and understanding of web content, making it highly versatile for different types of data extraction.

Installation Instructions
Follow these steps to set up the project on your local machine.

Clone the repository
bash
Copy code
git clone https://github.com/your-username/ai-web-scraper.git
Navigate to the project directory
bash
Copy code
cd ai-web-scraper
Install dependencies
Make sure to have pip installed, then install all the required packages via:

bash
Copy code
pip install -r requirements.txt
Usage
Running the Web Scraper
First, run the main.py file using Streamlit to start the web interface:

bash
Copy code
streamlit run main.py
The app will prompt you for a website URL. Enter a valid website URL in the text input box.

Click the "Scrape Site" button to fetch the website content.

After scraping the site, the raw and cleaned DOM content will be displayed in an expandable text area.

If you want to extract specific information, enter a description of what you want to extract in the text area provided under the "Parse Content" section, and click the "Parse Content" button.

The AI will process your query and return the extracted content.

Features
Web Scraping: Uses Selenium to load dynamic websites and extract the entire HTML DOM.
Content Cleaning: Cleans the body content of the website by removing scripts, styles, and unnecessary whitespace.
AI Parsing: The Langchain-powered Ollama model helps parse the DOM content based on user-provided descriptions and extract relevant data.
Easy Web Interface: Simple user interface built with Streamlit to allow users to interact with the scraper and query the AI for data extraction.
Technologies Used
Python 3.x
Streamlit: Web framework for building the UI.
Langchain: Framework for AI-driven content parsing.
Langchain Ollama: LLM-based model for parsing and extracting relevant information.
Selenium: For web scraping and handling dynamic content.
BeautifulSoup4: For HTML parsing and cleaning.
lxml: For parsing XML/HTML content.
html5lib: HTML parser.
python-dotenv: To handle environment variables securely.
Contributing
If you'd like to contribute to the development of this project, follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-name).
Make your changes and commit them (git commit -am 'Add feature').
Push to your branch (git push origin feature-name).
Create a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Selenium: For automating web scraping and handling JavaScript-heavy websites.
BeautifulSoup: For parsing and extracting web data.
Langchain: For creating flexible and scalable AI models for text processing.
Ollama: For providing an LLM-based solution for parsing and extracting data from web content.
Feel free to modify the instructions to match the specifics of your project, especially in areas like the Technologies Used and Features. Let me know if you need further adjustments!






