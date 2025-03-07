# image-converters
Useful Image Conversion script. Bash scripts & other tools that convert images filetypes. E.g. WEBP to JPG

## WEBP to JPG
- Make new folder / directory.
- Add your .webp images to location.
- Add FFMPEG to your directory. ```https://ffmpeg.org/download.html```
- Open terminal in directory.
- Enter the following code in the command line. ```for x in ls *.webp; do  ffmpeg -i $x ${x%.webp}.jpg; done```
