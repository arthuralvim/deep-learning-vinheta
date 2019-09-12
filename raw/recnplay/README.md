CONVERTENDO PARA IMAGENS

```bash
$ ffmpeg -i 1077807330.mp4 output-images/recnplay-%d.png
```

CONVERTENDO PARA IMAGENS PARA VIDEO

```bash
$ ffmpeg -start_number 1 -r 24 -i "processed-images/recnplay-%d.png" -pix_fmt yuv420p -vcodec libx264 output-video/output.mp4
```
