# SortMusic

# Overview

 This script was crafted with care to help you organize your music collection by album, making it easier to find and enjoy your favorite tunes. Whether your music folder is a well-curated library or a bit of a chaotic mess, this script will bring some order to the madness.

# Requirements

Python 3.x: The script is written in Python, so you'll need to have it installed on your machine. Mutagen Library: This script uses the mutagen library to peek into your music files and grab the album details.

# Installation

pip install mutagen

This will allow the script to work its magic on your music files.

# How to Use the Script

After you've got everything set up, it's time to run the script. When you start it, you'll be asked to enter the path to your music folder, this will help bring it all together by album.

Enter The Path To Your Music Folder: /path/to/your/music/folder

# What It Does: 

The script will dig through your music folder, checking out every song it finds. For each one, it'll look up the album name and then neatly place the file into a new folder named after that album. All these folders will be collected in a new directory called Sorted_By_Album, which will appear right inside your music folder.

Duplicate Handling: If you've got multiple copies of the same song with the same name, no problem. The script will add a little number at the end of the filename (like song_1.mp3) so nothing gets overwritten.

Completion: Once the script finishes its work, you'll find your music beautifully organized by album, all ready to be enjoyed. No more hunting through endless files—just click on an album and hit play!

# Example

Let's say your music is stored in C:\Users\YourName\Music. When prompted, you'd enter that path, and the script would go to work, organizing everything into a new Sorted_By_Album folder. Inside, you'd find all your albums, each in its own folder.

# Error Handling

If the script can't find album info for a file, it will skip that file and let you know. It also handles some other hiccups, like files that don't have the necessary metadata. If something unexpected happens, the script will try to keep going and process as much of your collection as possible.

# Contact

Let me know of any issues or improvements, thanks.







