# Mostaql Projects Scraper

An n8n workflow that scrapes new freelance projects from [Mostaql.com](https://mostaql.com/projects) every hour, filters them by keywords, and sends notifications to Telegram.

### Features

- Hourly scraping using Cron trigger
- Extracts Job Title, Post Time, and Link
- Filters projects based on your keywords
- Sends clean formatted messages to Telegram (with clickable links)
- Automatically splits long messages

### Workflow Structure

- Cron Trigger (every hour)
- HTTP Request → Get projects
- HTML Extract → Extract data
- Code Node → Filter by keywords
- Code Node → Format message
- Telegram → Send notification

### How to Use

1. Import the workflow into n8n
2. Set up your Telegram credentials
3. Update the keywords in the Filter Code node
4. Activate the workflow

### Screenshot

_(You can add a screenshot here later)_

### License

Free to use and modify.
