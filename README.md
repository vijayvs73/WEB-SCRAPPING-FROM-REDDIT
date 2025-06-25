# WEB-SCRAPPING-FROM-REDDIT
📄 Reddit NLP Subreddit Scraper
This Python script uses the Reddit API via the praw library to scrape the top 20 hot posts from the r/NLP subreddit and saves the results to a CSV file.

**✅ Features**
- Connects to Reddit using Reddit API credentials
- Fetches post data from the r/NLP subreddit
- Saves the following fields to a CSV file:
- Post Title
- Author
- Score (upvotes)
- Number of Comments
- URL to the post

**📦 Requirements**
Make sure you have Python 3 installed. Then install the required library:
- bash
- Copy
- Edit
- pip install praw

🔑 Reddit API Setup
- Go to https://www.reddit.com/prefs/apps
- Click "Create App"
- Select script as app type
** Fill out:**
- Name: anything (e.g., RedditScraper)
- Redirect URI: http://localhost:8080
- Click Create App
** Copy your:**
- client_id → shown under the app name
- client_secret → shown as “secret”

