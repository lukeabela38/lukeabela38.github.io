# MISC

Convert videos to uploadable format
```bash
ffmpeg -i input.mov -acodec libfaac -ab 96k -vcodec libx264 -level 21 -refs 2 -b 345k -bt 345k -threads 0 output.mp4
```