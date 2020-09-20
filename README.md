# UPLPlayer


The **UPL96ETL** by ECDesigns is a high fidelity audio source that plays music files stored on USB keys.

https://www.ecdesigns.nl/en/blog/upl96etl

**UPLPlayer** is an alternative application to control playback of the UPL96ETL, with the following features:


(1) very simple interface (folder based) to browse albums and control playback of the UPL

(2) does not use nor require tags and images to be stored in music files
This may limit the appeal for some, but may simplify the preparation of music files for others, as the UPL requires specific tag formats (ID3V2). 

(3) ability to use single wav files containing multiple tracks withcue sheets
- more files can be stored on a USB drive and played on the UPL (max: 98000 albums)
- tracks contained in the single-file wav,are displayed and can be played individually
- albums can be played gaplessely (provided the tracks are gapless)
- albums can be grouped in folders 

## Cue sheets

Use of single-file albums with cue sheets is possible with the following restrictions:

- a single wav file cannot be larger than 4GB (FAT32 restriction)
- a single wav file cannot contain more than 99 tracks per album
- a wav file cannot have a duration longer than approximately 2 hours and 45 minutes (9999 seconds to be exact)

Cue sheets need to be stored alongside each corresponding wav file, with the following naming convention:

"__NN wavfilename.cue"

Example:
- music file for a complete album is "01Muddy Waters - Live.wav"
- cue sheet should be named "__01Muddy Waters - Live.cue"


## Using large USB drives