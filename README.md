# Spotify Playlist Downloader With Windows GUI

Download an entire spotify playlist (160kbps mp3's) to your local machine with a simple interface

When it starts downloading it checks if you already downloaded the song if so it skips it.
When done downloading it also writes the ID3 data to the file.

###To install:
Install nodejs if you haven't already. ([NodeJS Downloads](http://nodejs.org/download/))  
Then download this repository (*"Download ZIP"* button on this page)  
Unpack the repository and run the .exe (source code can be found here https://github.com/dekiller82/Spotify-Playlist-Downloader-GUI)

###First Time Setup (Only needs to be done right after downloading)

Step 1: Enter Spotify Login Credentials (WARNING CREDENTIALS ARE STORED IN PLANE TEXT)

Step 2: Click the "npm install" button and wait for it to put some shit in the window.

###How To Get Playlist URL

Go to the Spotify Webplayer and Navigate to the Playlist you want to download.
Your URL should look something like this:

https://play.spotify.com/user/spotify/playlist/6RsopNg2yrLjKiu00jaCyi

Paste that in to the Spotify Playlist URL Textbox

###TO-DO

Add option to download all mp3's to a single folder

Add option to set download folder (For now songs will be saved to: C:\Users\youruser\spotify-mp3s)

###Additional Comments

Free Accounts get limited after a while though, but starts downloading again afterwards
