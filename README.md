# yt-dlp-tips

force mp4 download from yt

yt-dlp.exe https://www.youtube.com/watch?v=PJOdJSv4L3g -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best"

yt-dlp.exe -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best" https://www.youtube.com/watch?v=PJOdJSv4L3g

yt-dlp.exe  https://www.youtube.com/watch?v=QFG-XP8oQs4 -o ./%(title)s.%(ext)s\ --embed-thumbnail --embed-metadata --embed-info-json --embed-subs --sub-langs fr --merge-output-format mp3 --default-search ytsearch --audio-format mp3

yt-dlp.exe -x —audio-format mp3 —audio-quality 0 —postprocessor-args “-q:a 0” https://www.youtube.com/watch?v=QFG-XP8oQs4
