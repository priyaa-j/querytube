# QueryTube

A semantic YouTube search engine that lets users search videos using **natural language** instead of exact keywords. The application fetches video metadata and transcripts, generates vector embeddings, and returns the most relevant videos based on semantic similarity.

---

## Features

- Fetches video metadata using the YouTube Data API
- Extracts and cleans video transcripts
- Generates embeddings with Sentence Transformers
- Performs semantic search using cosine similarity
- Interactive Streamlit web interface

---

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Sentence Transformers
- YouTube Data API v3
- YouTube Transcript API
- Python Dotenv

---

## Project Structure

```text
QueryTube/
├── app.py
├── youtube-search.py
├── youtube-search03.py
├── youtube-search04.py
├── requirements.txt
├── README.md
├── .env
└── notebooks/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/querytube.git
cd querytube
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
YOUTUBE_API_KEY=YOUR_API_KEY
YOUTUBE_CHANNEL_ID=YOUR_CHANNEL_ID
```

---

## Usage

Build the search index

```bash
python youtube-search.py
python youtube-search03.py
python youtube-search04.py
```

Launch the application

```bash
streamlit run app.py
```

---

## How It Works

1. Fetch video metadata
2. Download transcripts
3. Clean transcript data
4. Generate sentence embeddings
5. Compare query and transcript embeddings
6. Return the most relevant videos

---

## Future Improvements

- Thumbnail previews
- Advanced search filters
- Better ranking models
- Streamlit Cloud deployment

---

## Author

**Priya Jaiswal**

Email: **priyajaiswal8775@gmail.com**

---