![http://txt2mp3mac.googlecode.com/files/txt2mp3mac_v3.png](http://txt2mp3mac.googlecode.com/files/txt2mp3mac_v3.png)
## Requirements ##
  * Mac OS X 10.2.2 or newer
##  ##
## Purpose ##
This is an applescript application that converts a given text file to mp3. Useful for creating audiobooks from ebooks, listening to lecture notes on the go, etc. It employs the default Mac OS X speech synthesizer for text-to-speech and a bundled universal binary of LAME v3.98 for mp3 conversion.
##  ##
## Implementation ##
The default Mac OS X speech synthesizer will generate uncompressed AIFF files that can get rather large if the given text file is long (ex. a book). To avoid this, the applescript processes each paragraph in the text individually: reading a given paragraph to AIFF, immediately converting to a temporary mp3 file and deleting the AIFF file before moving on to reading the next paragraph. After all paragraphs are read, the temporary mp3 files are concatenated into a single final mp3 file and the temporary files are deleted.
##  ##
## Update ##
As of version 5, you can now select multiple text files for conversion (yields one mp3 file for each selected text file).
##  ##
[Note on first-run performance](FirstRunDelay.md) | [Tips for fine-tuning audio output](FineTuning.md) | [Remember play position in iTunes and iPods/iPhones](iTunesTricks.md) | [Other works included](OtherWorks.md)