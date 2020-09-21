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
- albums can be organized in folders

Use of single-file albums with cue sheets is possible with the following restrictions:

- a single wav file cannot be larger than 4GB (FAT32 restriction)
- a single wav file cannot contain more than 99 tracks per album
- a wav file cannot have a duration longer than approximately 2 hours and 45 minutes (9999 seconds to be exact)

## Using large USB drives

Drive must be formatted as **FAT32**. On Windows, we suggest using "Rufus" (https://rufus.ie/) to format USB drives, with the following settings:

![rufus](/Rufus.jpg)

Please note that the option "List Hard Drives" (under the "Show advanced drive properties" drop-down) has to be checked in order to format hard drives.

## Installation

## Preparing Files

1) WAV music files



2) CUE Sheets



## File naming conventions

- Music files must be copied onto the USB drive in folders numbered 001 to 999.
- Music files (wav) must be numbered wih a two digit prefix 01 to 99.
- The corresponding cue files must have the same prefix as the wav files, with an additional prefix "__" (two underscore)


Example - folder contains a single album with files corresponding to each track

**Folder "001 Muddy Waters - Live"** will contain the following files

01 Mannish Boy.wav    
02 Shes Nineteen Years Old.wav    
03 Nine Below Zero.wav    
...

Example - folder contains multiple albums, each saved as single files (wav) with cue sheets (cue)

**Folder "001 Blues"** will contain the following files

01 B.B. King - Live At The Regal.wav    
02 Muddy Waters - Mississippi Live.wav    
__01 B.B. King - Live At The Regal.cue    
__02 Muddy Waters - Mississippi Live.cue    

Renaming files can be automated by defining batch scripts, or using any of the many file renaming software available on Windows/Mac/Linux.

With the windows program "File Renamer Turbo" (http://www.kristanixsoftware.com/filerenamer/) scripts can be accessed from the Explorer.

## Scanning the files



## Playing music
