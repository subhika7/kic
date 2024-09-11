# picoctf challenges

binary search

glory of the garden-extracting flag from an image metadata analysis(strings,exiftool,xxd,binwalk);strings <imagefilename.jpg> | grep pico

|(pipe) -sends ouput of a command: grep-searches for the word pico

information- exiftool <filename> | grep License | sed -e ‘s*. //’ | base64 -d

sed-stream editor  : removes punctuations

can you see- unzip and exiftool : cyberchef is a website it compress,decodes,encodes,from bas64 the attribution url is converted and flag is obtained