# Comandos Útiles

## Markdown a PDF con pandoc

```
pandoc -V geometry:margin=2cm -o result.pdf input.md
```

## Concatenar videos

```
mencoder -idx -ovc copy -oac copy -o output.mp4 input_1.mp4 input_2.mp4
```

## Obtener audio de un video

```
ffmpeg -i input-video.mp4 output-audio.mp3
```
