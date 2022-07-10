# Pac-Unpacker-Repacker
The code is mostly just a python translation of the Pac unpacking/repacking code used in the YGO NDS Randomizer, found at https://github.com/mSpoeth/YgoNdsRandomizer.

# Usage
This utility is command-line only. If you came here expecting a nice UI like the program I got this from, fughetaboutit. To prepare, install python (no other dependencies are needed AFAIK), and then place main.py and the pac you want to use in the same directory. CD there, and then type either:

``` python "main.py" "Name-Of-Pac" -u ```

to unpack the pac file into its constituents in a folder named "output," OR

``` python "main.py" "Name-Of-Pac" -r ```

to repack all files listed in that pac and found in a folder in the CD'd directory named "output" into a new pac file.

WARNING: the program will always name the new pac file "repackedOutput.pac," and it always creates it in append mode. So please, *please* move that file to a different directory before doing another repacking.

# Limitations
I made a point of getting it to let you change file sizes. However, you cannot change the amount of files nor their names. If someone ever actually sees this and is interested in that, I can make it happen, but I see no point presently.
