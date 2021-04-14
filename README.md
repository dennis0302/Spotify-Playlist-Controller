# Spotify-Playlist-Controller

# Usage

1. Install requirements and Node.js


```
pip install django djangorestframework
```

2. Spotify API configuration


```
Create a Spotify account if you do not already have one.
Go to https://developer.spotify.com/ and log in with your Spotify credentials.
Go to Dashboard and Click "CREATE AN APP"
Fill out the forms and agree to the terms
Click "EDIT SETTINGS" and paste "http://127.0.0.1:8000/spotify/redirect" in Redirect URLs
Copy client ID and client secret
```

Fill credentials in music_controller/spotify/credentials.py


3. Run the program 


```
cd music_controller
python manage.py runserver
```

```
cd music_controller
cd frontend
npm run dev
```

or

```
cd music_controller
cd frontend
npm run build
```
