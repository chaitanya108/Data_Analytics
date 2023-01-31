# Scraping Top Repositories for Topics on GitHub

TODO (Intro):
•	Introduction about web scraping
•	Introduction about GitHub and the problem statement
•	Mention the tools you're using (Python, requests, Beautiful Soup, Pandas)

Here are the steps we'll follow:
•	We're going to scrape https://github.com/topics
•	We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description
•	For each topic, we'll get the top 25 repositories in the topic from the topic page
•	For each repository, we'll grab the repo name, username, stars and repo URL
•	For each topic we'll create a CSV file in the following format:

Scrape the list of topics from Github

Explain how you'll do it.
•	use requests to downlaod the page
•	user BS4 to parse and extract information
•	convert to a Pandas dataframe
