# dj_suggest
ML tools to suggest tracks for DJ playlist based on spotify track features. Connects to Spotify API from Python script using Spotipy library.

For Oath2 authentication, need to add the following lines to .bash_profile:

  # Spotipy python library for connecting to Spotify API from python. Authorisation variables:
  export SPOTIPY_CLIENT_ID='your-client-id'
  export SPOTIPY_CLIENT_SECRET='your-secret-id'
  export SPOTIPY_REDIRECT_URI='your-redirect-URL'
