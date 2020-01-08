# FFMPEG Resize Image

[**WEB**](https://tomashubelbauer.github.io/ffmpeg-resize-image)

- To fixed size: `.\ffmpeg.exe -i img.jpg -vf scale=320:240caled.jpg`
- To aspect ratio with fixed width: `.\ffmpeg.exe -i img.jpg -vf scale=320:-1 scaled.jpg`
- To aspect ratio with fixed height: `.\ffmpeg.exe -i img.jpg -vf scale=-1:240 scaled.jpg`
- To percentage: `.\ffmpeg.exe -i img.jpg -vf scale=iw/2:ih/2 scaled.jpg`

## To-Do
