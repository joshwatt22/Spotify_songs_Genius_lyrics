# Spotify_songs_Genius_lyrics
Code which uses the Spotify API to obtain Metadata for Spotify songs and Genius API to obtain lyrics for those songs.

Use function `get_playlist_songs` to obtain data for a Playlist. This function takes a list of Spotify Playlist URLs as its input and returns a pandas dataframe of spotify songs along with their metadata (from Spotify API) and their lyrics (from Genius API).

Use function `get_list_songs` to obtain data for a list of songs. This function takes a list of Spotify Song URLs as its input and returns a pandas dataframe of spotify songs along with their metadata (from Spotify API) and their lyrics (from Genius API).
