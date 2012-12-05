# imgreorder

Order images (and movies) to YY/MM/DD/filename.ext scheme. Date/Time
information is taken from EXIF if possible, otherwise using stat
information (mtime).

## Usage
imgreorder reorders images (.jpg or .JPG) and movies (.mov or .MOV)
into a YY/MM/DD structure from the current directory.

`imgreorder.py PATH [--verbose]`
