# 11RaviChanchal-workflow11
my collection of  automation workflow built using n8n 

about new1
Instagram x AI Workflow – Chanchal Bose

 What This Does
- Scrapes 12 public Instagram posts (via Apify)
- Displays posts in a clean 3 × 4 image grid with captions, likes, and comments

 How It Works
1. Trigger— Executes manually when the button is clicked.
2. Edit Fields — Accepts Instagram username as input (e.g. `nike`).
3. INSTA Data Fetch (HTTP Request)— Pulls the latest 12 posts from a pre-scraped Apify dataset using API key.
4. Code — Builds an HTML table in a 3×4 layout with thumbnails, captions, likes, and comments.
5. Markdown  — Converts that HTML to Markdown format.
6. Grid Display — Converts back to HTML and renders the final 3×4 layout.

1. Import the  json file into your n8n instance
Created with 💡 by Chanchal Borse
