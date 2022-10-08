#Music/Lyrics Generation using LSTM

![into](https://theinnerdetail.com/wp-content/uploads/2021/07/aisong5.jpg)


Few notes from the notebook:

Now retrieve the components of the MIDI files, it can be either chords or notes.

MIDI file format in brief:
The Standard MIDI File (SMF) is a file format that provides a standardized way for music sequences to be saved, transported, and opened in other systems.

MID or. MIDI file extension is the Musical Instrument Digital (MID) Interface file. It is the difference from ordinary audio files such as WAVs or MP3s in that it doesn't carry the actual audio content; hence, is quite smaller in size.

For more details: https://docs.fileformat.com/audio/mid/


**Note:** The musical notes are the building blocks of the music. It pertains to a pitch associated with a specific audio vibration. Western music utilizes twelve musical notes. 

**Chord:** A group of notes that sound good together is a chord.

The music21 stream that was created in the above cell contains both, chords and notes, we will extract them in the form of notes and obtain a series of notes in the musical composition.

#-----------------------------------------------------

The main take away is the music21 package that helps us to convert the mid format music files to our regular numerical values and then reframe it into LSTM input shape.
This is a open source project any collab for further development is most welcome.












![](https://i.ytimg.com/vi/Emidxpkyk6o/maxresdefault.jpg)
