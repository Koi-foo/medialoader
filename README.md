# medialoader
Download and assemble video online from ts file segments.
**Source Code:** https://github.com/Koi-foo/medialoader.git

## Summary:
Script for downloading and merging online video clips from "ts" fragments.

## Description:
The python3 url string parser script is designed to download video fragments from sites and then combine them into an mp4 file.

## Requires:
* Python 3.7 or higher
* wget
* ffmpeg

Help for -h options
## Brief description of the -u, -s options.
-u 'http://download/video{4}.ts'
This parameter is the only required one. It is recommended to enclose the link in quotation marks. The changing number must be enclosed in brackets {}. Link example: http://load/video4.ts, where 4 is the number of the file being modified. Link passed correctly -u 'http://load/video{4}.ts'

-s 10-20,80-90
Specifies which segments to download. In this example, files from 10 to 20 will be downloaded, skipping everything up to 80 and downloading from 80 to 90. There can be as many fragments as you like, the record must be in pairs and not contain spaces.

The remaining options are obvious and are described in the script's help.
