```

ffmpeg -i 01_720.mp4 -codec copy -vbsf h264_mp4toannexb -map 0 -f segment -segment_list 720/index.m3u8 -segment_time 30 720/%03d.ts

https://cdn.jsdelivr.net/gh/ncc0706/30eryi@latest/01/720/index.m3u8


ffmplay https://cdn.jsdelivr.net/gh/ncc0706/30eryi@latest/01/720/index.m3u8
```

