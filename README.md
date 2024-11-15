# Mycodeproject_song

## Introduction
An original composition by me. For this assessment I decided to choose the creative route and composed a song on the program Tunepad. This tested my limited and evolving coding abilites while also utilising the musical skills I have grown up with.  
### Technologies
My song was composed with a 3 instruments on the music programing software Tunepad. The language used trhoughout the entire project is Python.
#### Features
- Axix Chord proression in D major on Piano
- Basic pop drum beat
- Bass guitar for rhthym
##### Usage

Piano (Chords)

def majorChord(baseNote):
    chord = [baseNote, baseNote + 4, baseNote + 7]
    print(chord)
    return chord

def minorChord(baseNote):
    chord = [baseNote, baseNote + 3, baseNote + 7]
    print(chord)
    return chord


playNote(majorChord(38), beats=2),  # D Major (D F# A)
playNote(majorChord(38))

playNote(majorChord(33), beats=2) #A major (A C# E)
playNote(majorChord(33))

playNote (minorChord(35), beats=2) #B minor (B D F#)
playNote (minorChord(35))

playNote(majorChord(43), beats=2) #g major(G B D)
playNote(majorChord(43))

Piano (Melody)

#Melody

playNote(62)
playNote(57, beats=2)
playNote(67)
playNote(67, beats=2)
playNote(60)
playNote(64, beats=2)
playNote(62)

Bass Guitar

playNote(21, beats = 3)
playNote(23, beats = 1)
playNote(16, beats = 3)
playNote(16, beats = 1)

Drums

playNote(0, beats = 0.5)
playNote(4, beats = 0.5)
playNote(2, beats = 0.5)
playNote(4, beats = 0.5)
playNote(0, beats = 0.5)
playNote([0, 4], beats = 0.5)   # play kick and hat together
playNote(2, beats = 0.5)
playNote(4, beats = 0.5)

###### Acknowledgments

TunePad. (n.d.). Beatmaking: Day 4. Retrieved October 27, 2024, from https://learn.tunepad.com/curriculum/activities/beatm-day4/

TunePad. (n.d.). Chords tutorial. Retrieved October 27, 2024, from https://learn.tunepad.com/tutorials/chords/

TunePad. (n.d.). Still D.R.E. Retrieved October 27, 2024, from https://learn.tunepad.com/tutorials/still-dre/
