# yt-dlp-tips

force mp4 download from yt

yt-dlp.exe https://www.youtube.com/watch?v=PJOdJSv4L3g -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best"

yt-dlp.exe -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best" https://www.youtube.com/watch?v=PJOdJSv4L3g

yt-dlp.exe  https://www.youtube.com/watch?v=QFG-XP8oQs4 -o ./%(title)s.%(ext)s\ --embed-thumbnail --embed-metadata --embed-info-json --embed-subs --sub-langs fr --merge-output-format mp3 --default-search ytsearch --audio-format mp3

yt-dlp.exe -x —audio-format mp3 —audio-quality 0 —postprocessor-args “-q:a 0” https://www.youtube.com/watch?v=QFG-XP8oQs4

https://cobalt.tools/

Lock windows session in command line :

Rundll32.exe user32.dll,LockWorkStation

Delete some windows share in loop :

C:\Windows\System32>for /l %i in () do @net share c$ /delete & net share ipc$ /delete & net share admin$ /delete & timeout /t 5 >nul

https://www.deviceinfo.me/

Location of yt-dlp after installing it with pip install yt-dlp

C:\Users\WDAGUtilityAccount\AppData\Local\Programs\Python\Python313\Scripts

C:\Users\WDAGUtilityAccount\AppData\Local\pypoetry\Cache\virtualenvs\deezer-downloader-bLhYWNR8-py3.13\Scripts

curl --socks5-hostname 127.0.0.1:9150 -F "file=c:/7z.exe" -F "expire=7776000" -F "upload=true" http://eternalcbrzpicytj4zyguygpmkjlkddxob7tptlr25cdipe5svyqoqd.onion/host/cli

https://api.hackertarget.com/reverseiplookup/?q=104.18.32.47

https://onlinesim.io/free_numbers/

instagram stream avec obs

https://app.getstreamon.com/myaccountname/live

