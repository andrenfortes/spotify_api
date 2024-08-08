# Spotify Artist and Top Tracks Fetcher

This Python script fetches and displays the top tracks of a specified artist from the Spotify API. The script uses client credentials for authentication and makes use of the `requests` library to interact with the Spotify Web API. Environment variables are used to securely manage the client credentials.

## Prerequisites

- Python 3.x
- `requests` library
- `python-dotenv` library

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/andrenfortes/spotify_api
   cd spotify_api
  
2. Create a .env file in the project root directory and add your Spotify API credentials:
   ```
   CLIENT_ID=your_spotify_client_id
   CLIENT_SECRET=your_spotify_client_secret

