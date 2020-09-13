# ETKRes-SNES
Resources for Emuteca: Nintendo SNES

Icons, images, texts, videos, etc. for use with [Emuteca](https://github.com/Chixpy/Emuteca).

## About Images

### Screenshot, Titles

Rule #1: No filters to screenshots.

All images in .png format at original resolution: *256×224*, *512×448* (NTSC), *256×240*, *512×480* (PAL)

### Front, Back, Spine, Ads, Reviews, Media, Other

Escaned .jpg; with a maximum of 2048x2048, don't enlarge artificially (if larger, we can resize it to 2048 the larger side, keeping aspect ratio and a quality of 90%). Trying not to do transformations and resave it. Lossless rotation or cropping allowed.

### Icons, Logos

Rule #1: Only 1 image for group or game. No folders with multiple images.

Icons are mainly extracted from game screenshots at original resolution. Usually they are protagonist frames or lives icons (if they are similar to protagonist).

All images are .png format. Width and Height are variable, using it's original size without resizing to a fixed size or adding more border to make it square. Emuteca handle they automatically.

The only time that the image will be scaled is when all 'icon pixels' are 2x2, 3x3, etc. pixels.

After extracting the icon image with transparent background, a border is added: Middle grey, half transparency (128, 128, 128, 128). Emuteca has a GIMP's script in its distribution, that can add the border automatically after transparent background is created.

## Download

Use GIT to clone the repository or download it in zip:

https://github.com/Chixpy/ETKRes-SNES/archive/master.zip