# sync-youtube-playlist

I use youtube for music a lot. Putting together playlists, then using youtube-dl to download and extract mp3 files.
Sometimes these playlists change. This script syncs local files. Deleting locally stored items removed from the youtube playlist, and downloading any new items.

Modified to sync all playlist based the Youtube channel id.

## .env file

  * API_KEY
  * CHANNEL_ID
  * ROOT_MUSIC_PATH 
  * MAX_PLAYLIST_RESULT (max number of playlist)
  * MAX_PLAYLIST_ITEMS_RESULT (max number of songs)
  
## usage

`npm start`

## license
[MIT](/LICENSE)

