# Playlist Swiper: Discover and Curate Your Music

**Playlist Swiper** is an interactive Python-based app that allows users to go through a Spotify playlist, deciding whether to "keep" or "remove" songs from their curated playlist. This app integrates with the Spotify API to fetch playlist data and offers a randomized way to discover and curate your music preferences.

## Features:
- Fetch songs from any public Spotify playlist by entering the playlist URL.
- Shuffle the playlist for a random order of songs.
- Keep (add to your favorites) or remove songs from your playlist using simple input commands.
- Display a summary of all songs kept after swiping through the playlist.

## Tech Stack:
- Python
- Spotipy (Spotify API wrapper)
- Spotify Web API

## How to Use:
1. Clone the repository and install dependencies (`spotipy`).
2. Get your Spotify API credentials (Client ID and Secret) from the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).
3. Run the app, input a Spotify playlist URL, and start discovering and curating your playlist!
4. At the end, you'll receive a list of all the songs you've kept.

## Installation:
```bash
pip install spotipy
