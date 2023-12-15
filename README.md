# Spotify with Langchain

## Introduction

Welcome to the Spotify with Langchain project! This Jupyter notebook-based application leverages the power of the Spotify Web API and Spotipy SDK to respond to natural language inputs. By integrating Langchain's advanced PALChain (Program-Aided Language) prompting technology, this project offers an intuitive way to interact with Spotify's vast music database. The project features a Gradio chat interface, providing a seamless user experience for querying and receiving information in natural language.

## Features

- **Natural Language Processing**: Interact with Spotify using everyday language.
- **Spotipy SDK Integration**: Access Spotify's comprehensive API for detailed data retrieval.
- **PALChain Technology**: Leverage advanced language model prompting for accurate responses.
- **Gradio Chat Interface**: Enjoy an interactive, user-friendly chat interface for queries.
- **Environment-Friendly Setup**: Easy setup with environment variable management.

## Setup Instructions

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook
- Basic knowledge of Python and Jupyter environments

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone [repository URL]
   cd [repository name]
   ```

2. **Create Environment File**
   - In the repository's root folder, create a `.env` file and include the following keys:
     ```
     OPENAI_API_KEY=sk-redacted
     SPOTIFY_CLIENT_ID=redacted
     SPOTIFY_CLIENT_SECRET=redacted
     PINECONE_API_KEY=redacted
     PINECONE_ENVIRONMENT=gcp-starter
     ```
   - Replace `redacted` with your actual API keys.

3. **Set Up Virtual Environment (Optional)**
   - It's recommended to create a virtual environment to avoid conflicts with existing Python packages.
     ```bash
     python -m venv .venv
     source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
     ```

4. **Open and Configure Jupyter Notebook**
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `main.ipynb`.
   - Replace `reload_ext` with `load` only for the first time you run this notebook.

## Usage

1. **Run the Notebook**
   - Execute the cells in `main.ipynb` as needed.
   - Interact with the Gradio chat interface to send queries and receive responses.

2. **Query Examples**
   - Ask for song recommendations based on genre, mood, or artist.
   - Retrieve song details or artist information.
   - Explore playlists or albums.

## Acknowledgments

- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- [Spotipy SDK](https://spotipy.readthedocs.io/)
- [Langchain](https://langchain.dev/)
- [Gradio](https://gradio.app/)