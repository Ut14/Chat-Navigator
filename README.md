
# WebScrape-Chatbot

A brief description of what this project does and who it's for

This project is an AI-powered chatbot that automates web scraping, text processing, and question-answering tasks. The chatbot is built using LangChain, HuggingFace, and Selenium, making it capable of extracting information from websites, processing the extracted text, and providing insightful answers to user queries.
## Features

- Web Scraping: Automatically scrape content from websites using Selenium and BeautifulSoup.
- Text Processing: Clean and process text content for better analysis.
- Question-Answering: Leverage the HuggingFace models to provide accurate answers to user questions.
- Interactive Chatbot: Engage in a conversational interface where users can ask questions related to the scraped data.


## Prerequisites

- Python 3.8+
- Install required Python packages listed in `requirements.txt`
## Installation

Clone the Repository

```bash
git clone https://github.com/your-username/Chatbot_Automation.git
cd Chatbot_Automation
```
Install Dependencies

```bash
pip install -r requirements.txt
```
Set Up Environment Variables

```bash
export HUGGINGFACEHUB_API_TOKEN=your_api_key
```
Run the Chatbot

```bash
python chatbot.py
```

    
## Usage

Starting the Chatbot

- After running the script, the chatbot greets you with:

```bash
Bot: Hello I am Bot. How can I help you? (type exit to quit)
```
You can ask questions related to the scraped content, like:

```vbnet
User: Why is BotPenguin good?
```
- The chatbot will provide an answer based on the processed data.

Exit the Chatbot

- Type `exit` to end the session:
```vbnet
User: exit
Bot: Bye Bye
```


## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.


## License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.