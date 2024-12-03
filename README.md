# Automated Web Scraping and Newsletter Project
## Description
This project performs web scraping on relevant websites in the payments, fintech, security and cryptocurrency industries. The extracted data is processed to generate a weekly newsletter with summaries of the most important articles, translated into Spanish, and presented in HTML format.
## Features
1. **Automated Extraction**:
- News scraping on key sites such as:
- Finextra (Payments and Security)
- PYMNTS (Fintech, Cryptocurrencies, B2B and Retail)
- The Paypers (Fraud)
- Payments Journal
- Data includes the title, content and link to each article.
1. **Automated Summary**:
- Generation of clear and concise summaries using AI models.
- Automatic translation into Spanish for better accessibility.
1. **Newsletter Generation**:
- Creation of a weekly newsletter in HTML format.
- Beautiful layout with well-defined categories.
1. **Production-ready integration**:
- Modular functions to add new sources or customize the layout.
- Newsletter.html file ready to be sent or published.
-----
## **Requirements**
- Python 3.9 or higher.
- Dependencies:
  - selenium
  - webdriver\_manager
  - openai
  - deep-translator
-----
## **Usage**
1. **Setup**:
- Make sure you have a virtual environment set up and the dependencies installed.
- Verify that you have access to an OpenAI model and your API key set up.
1. **Execution**:

Run the main script:
` `python newsletter\_generator.py

1. The script will perform the scraping, process the data, and generate the newsletter.html file.
1. **Customization**:
- To add more sources, simply create a new scraping function following the outline of the existing functions.
- You can modify the HTML structure in the summarize\_and\_create\_newsletter function.
-----
## **Project Structure**
├── newsletter\_generator.py # Main Script

├── requirements.txt # Project Dependencies

├── README.md # Project Documentation

├── newsletter.html # Generated Output

## **Limitations and Future Improvements**
1. **Limitations**:
- Depends on the HTML structure of the target websites, so changes to these may require adjustments.
- Site loading time may vary, affecting performance.
1. **Future Improvements**:
- Add more relevant industry sources.
- Support for export in other formats such as PDF or Markdown.
- Automation of sending newsletters by email.
-----
## **Contributions**
Feel free to propose improvements, report bugs or contribute new features through **pull requests** or **issues**.
