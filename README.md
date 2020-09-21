# UPLPlayer


The **UPL96ETL** by ECDesigns is a high fidelity audio source that plays music files stored on USB keys.

https://www.ecdesigns.nl/en/blog/upl96etl

**UPLPlayer** is an alternative application to control playback of the UPL96ETL, with the following features:


(1) simple interface (folder based) to browse albums and control playback of the UPL

(2) tags and images stored in music files are not used
This may limit the appeal for some, but may simplify the preparation of music files for others, as the UPL requires specific tag formats (ID3V2). 

(3) ability to use single wav files containing multiple tracks with cue sheets
- more files can be stored on a USB drive and played on the UPL (max: 98000 albums)
- tracks contained in the single-file wav are displayed and can be played individually
- albums can be played gaplessely (provided the tracks are gapless)
- albums can be grouped in folders 

## Cue sheets

Use of single-file albums with cue sheets is possible with the following restrictions:

- a single wav file cannot be larger than 4GB (FAT32 restriction)
- a single wav file cannot contain more than 99 tracks per album
- a wav file cannot have a duration longer than approximately 2 hours and 45 minutes (9999 seconds to be exact)

## Using large USB drives

## Installation

## Preparing Files

## Renaming files

Music files must be copied onto the USB drive in folders numbered 001 to 999.
The music files must be numbered wih a two digit prefix 01 to 99
The corresponding cue files must have the same prefix as the wav files, with an additional prefix "__" (two underscore)


- Example - folder contains one album 

**Folder "001 Muddy Waters - Live"**

01 Mannish Boy.wav    
02 Shes Nineteen Years Old.wav    
03 Nine Below Zero.wav    
...

- Example - folder contains multiple albums saved as single files (wav) with cue sheets (cue)

**Folder "001 Blues"**

01 B.B. King - Live At The Regal.wav    
__01 B.B. King - Live At The Regal.cue    
02 Muddy Waters - Mississippi Live.wav    
__02 Muddy Waters - Mississippi Live.cue    


## Scanning the files

## Playing music
