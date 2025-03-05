# AI Crawler
Get data from the internet with the power of AI using Crawl4AI and Chromium 


# Setup 

Install Dependencies
```
pip install -r requirements.txt
```

Create a .env file in the root directory with content similar to:
```
GROQ_API_KEY=your_groq_api_key_here
```

# Usage
To start the crawler, run:
```
python main.py
```
The script will crawl the specified website, extract data page by page, and save the complete venues to a complete_venues.csv file in the project directory. Additionally, usage statistics for the LLM strategy will be displayed after crawling.

### Author 
Eric Michel
