# memeow

**memeow** is an AI-powered meme generator that fetches trending memes and allows users to create personalized memes by adding their own captions or topics. The project uses Reddit's API to scrape top memes and lets users interact with the memes in a fun, creative way.

## Features

- **Trending Memes**: Fetches and displays trending memes from Reddit’s r/memes subreddit.
- **AI Meme Generation**: Allows users to add captions and create personalized memes.
- **Dynamic Meme Templates**: Meme templates are fetched and updated regularly.
- **Cool UI/UX**: Features loading animations, meme creation interface, and social sharing options.
- **Social Media Integration**: Share your meme creations across social media platforms.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (for creating the meme creation interface)
- **Backend**: Python, Flask (for handling meme data fetching and meme generation)
- **Database**: MongoDB Atlas (for storing meme data and user-generated memes)
- **Meme API**: Reddit API (to fetch trending meme content)
- **AI Integration**: For meme caption generation (using open-source AI models or custom implementations)
  
## Requirements

- Python 3.8 or higher
- Flask (`pip install Flask`)
- PRAW (Python Reddit API Wrapper, install with `pip install praw`)
- MongoDB Atlas account (for database storage)

## Installation

### Clone the repository:

```bash
git clone https://github.com/muhhnehh/memeow.git
cd memeow
