Resize
-----------

- Resize will fit the image into the requested size. 

```bash
magick large.png -resize 64x64 resized.png
```

- Ignore Aspect Ratio

```bash
magick original.png -resize 64x64\! resized.png
```