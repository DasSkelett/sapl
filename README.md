## What is sapl?
Sapl stands for "Stream and play list".
It started as "sap", as the function to create a playlist was added, the command was renamed to `sapl`.

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
