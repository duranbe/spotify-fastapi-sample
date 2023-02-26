# spotify-fastapi-sample
Spotify API Sample using FastApi

Spotify API Quickstart guide: https://developer.spotify.com/documentation/web-api/quick-start/

## How to Use

1. Clone repo & set up virtual environment

    ```bash
    git clone git@github.com:duranbe/spotify-fastapi-sample.git 
    cd spotify-fastapi-sample
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

2. Edit `example.env` with your Spotify API credentials
3. Load values into environment variables & run app

    ```bash
    source example.env
    cd src
    uvicorn main:app --reload
    ```
