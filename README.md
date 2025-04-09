# Download with custom output filename
yt-dlp -x --audio-format mp3 --audio-quality 0 -o "%(title)s.%(ext)s" "URL"

# Download with custom output directory
yt-dlp -x --audio-format mp3 --audio-quality 0 -o "/path/to/directory/%(title)s.%(ext)s" "URL"

# Download a playlist
yt-dlp -x --audio-format mp3 --audio-quality 0 -o "%(playlist_index)s-%(title)s.%(ext)s" "PLAYLIST_URL"

# Add metadata from YouTube to the MP3 file
yt-dlp -x --audio-format mp3 --audio-quality 0 --embed-metadata "URL"

# Add thumbnail as album art
yt-dlp -x --audio-format mp3 --audio-quality 0 --embed-thumbnail "URL"