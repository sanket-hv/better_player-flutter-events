# better_player-flutter-events

Here, it's all events that are listening in better_player flutter event listener and it displays the small description about all of those events.

initialized → When the video will initialize in Better Player.
play → When the video will be played in the player
pause → When video will be paused in the player
seekTo → When the user will try to seek the video in specific seconds
openFullscreen → When the user will try to open the full-screen mode
hideFullscreen → When the user will close the full-screen mode
setVolume → When the user will try to up or down the volume
progress → When the video is currently playing and in progress
finished → When the current video is completed
exception → When a player throws any error
controlsVisible → When controls are visible fully
controlsHiddenStart → When control starts hiding
controlsHiddenEnd → When control is fully hidden from view
setSpeed → When the user set the playing speed of the video
changedSubtitles → When the user changes the subtitles of a video
changedTrack → When the user changes the audio track of a video
changedPlayerVisibility → When the video player visibility is changed - from appearing to disappearing or vice-versa
changedResolution → When the user changes the resolution of the video
pipStart → When PIP(Picture in Picture mode started) started
pipStop → When PIP(Picture in Picture mode stopped) stopped
setupDataSource → When the data source of the video is setup from memory
bufferingStart → When the player starts buffering any specific video
bufferingUpdate → When the player starts updating the buffer of a specific video
bufferingEnd → When full video buffered and ended buffering
changedPlaylistItem → When the video of the playlist has changed from one to another
