# Spotify_songs_Genius_lyrics
Code which uses the Spotify API to obtain Metadata for Spotify songs and Genius API to obtain lyrics for those songs.

Use function `get_playlist_songs` to obtain data for a Spotify Playlist. This function takes a list of Spotify Playlist URLs as its input and returns a pandas dataframe of spotify songs along with their metadata (from Spotify API) and their lyrics (from Genius API).

Note that the Genius API does not always contain or find the lyrics for the requested Spotify song. Where the Genius API cannot find the correct lyrics, it will return a None value for the lyrics.
