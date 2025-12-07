# Rythm Report

A simple notebook that pulls my Spotify playlists using the Spotipy API and does a bit of analysis. Mostly a learning project for working with APIs and Jupyter workflows.

## -- What's inside --

* A Jupyter notebook (`rythm-report-init.ipynb`)
* Spotify API authentication using a `.env` file
* Basic playlist retrieval with Spotipy
* Some early data exploration

## -- How to run it --

1. Clone the repo
2. Create a `.env` file in the project folder with your Spotify API keys:

   ```
   SPOTIPY_CLIENT_ID=your_id_here
   SPOTIPY_CLIENT_SECRET=your_secret_here
   USER_ID=your_spotify_username
   ```
3. Install dependencies:

   ```
   pip install spotipy python-dotenv
   ```
4. Open the notebook and run it.

## -- Notes --

* `.env` and a few other local files are intentionally ignored.
* This is very much a work in progress.