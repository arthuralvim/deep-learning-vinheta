
BAIXANDO VÍDEOS DO YOUTUBE

```bash
$ youtube-dl https://www.youtube.com/watch\?v\=<youtube-video-id>
```

CONVERTENDO PARA IMAGENS

```bash
$ ffmpeg -i 1077807330.mp4 output-images/recnplay-%d.png
```

CONVERTENDO PARA IMAGENS PARA VIDEO

```bash
$ ffmpeg -start_number 1 -r 24 -i ./processed-images/recnplay-%d.png -vcodec libx264 output-video/output.mp4
```
