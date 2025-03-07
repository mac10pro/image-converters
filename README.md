# image-converters
Useful Image Conversion script. | E.g. webp to jpg or png. 

## WEBP to JPG
- Add FFMPEG to Directory.
- Open terminal in directory with FFMPEG and .webp Images.
- Enter the following code in the command line. ```for x in ls *.webp; do  ffmpeg -i $x ${x%.webp}.jpg; done```
