## What is sapl?
Sapl stands for "Stream and Play List".
It started as "sap" (for "Stream and Play"), as the function to create a playlist was added, the command was renamed to `sapl`.

## What are the prerequisites?

You need the [VLC Media Player by VideoLAN](http://www.videolan.org/vlc/) installed, especially the `cvlc` command is used here. Try `cvlc --version` to see if it is available on your system. You need [youtube-dl](http://ytdl-org.github.io/youtube-dl/) installed. Make sure you are running the latest version (`youtube-dl -u`), it's really important!

## How does it work?
1) `sapl add "<songname>"`
    **sapl** passes this command to **youtube-dl** which searches YouTube with this term.
    Then it adds *the* top result to the playlist.

2) `sapl` or `sapl start`
    Start playing the playlist, via **vlc media player**.

3) `sapl stop`
    Stop after the end of the currently playing song.

4) `sapl remove`
    Removes the last item of the playlist`

5) `sapl list`
    List the scheduled songs.

6) `sapl help`
    Get additional help and usage informations.
   

Run any of those commands in your console.


## How to install?
Just download the `sapl` file and put it in a folder included in your `PATH` and make it executable.
E.g.
```
mkdir ~/bin/
cd ~/bin/
curl -O "https://raw.githubusercontent.com/DasSkelett/sapl/master/sapl"
chmod +x "./sapl"
```
