## Bash script for selecting/adding a song in/to the current mpv playlist

### Usage

Make sure the mpv ipc server is running on `/tmp/mpvsocket` or edit the script to change the socket.

```
plplay [<file> | <name> | <url>]

Examples:
	plplay song.flac
	plplay "select song title (case insensitive)"
	plplay part of title
	plplay part of file name
	plplay "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
	plplay "https://www.youtube.com/playlist?list=PLjwyVt8z03-GKz1XgYfF-XhmkQk2Y8GSk"
	pladd addonly.flac
```
