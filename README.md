# 🔥 Spotify with Langchain

This Jupyter notebook project queries the Spotify web API using the Spotipy SDK and responds to the natural language input. Uses Langchain's PALChain (Program-Aided Language) prompting technology. Responses are in natural language as well. Gradio chat interface makes the communication possible.

# Setup

- Clone repository
- In the repository folder, create a ".env" file with the below content
- Open `main.ipynb`
- Replace `reload_ext` with `load` (only for the first time you run this notebook)
- Choose to create a `.venv` Python environment on your VS Code/similar IDE.

```
OPENAI_API_KEY=sk-redacted
SPOTIFY_CLIENT_ID=redacted
SPOTIFY_CLIENT_SECRET=redacted
PINECONE_API_KEY=redacted
PINECONE_ENVIRONMENT=gcp-starter
```

# Run

- Run necessary cells in the notebook.