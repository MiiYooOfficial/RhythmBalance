# RhythmBalancePro
A music theory homework solver for Windows

RhythmBalancePro is a terminal-based, Windows application, that solves what we call "Rest Insertion Problems," a common type of question found in rudimentary music theory. The application can either be used as a standalone, or in conjunction with both Audiveris (an OMR engine) and Musescore (a music notation program).

## RhythmBalancePro as a standalone
To use RhythmBalancePro as a standalone application, problems MUST be entered as a text file and answers will correspondingly also be returned as a text flie. However, given that the application is meant to solve music theory questions, the user will first have to translate the problem from music notation to an ASCII-based notation system unique to the program (see Instruction Manual under Releases to learn more).

## RhythmBalancePro in conjunction with Audiveris and Musescore
The alternative to having to translate every question into the program's own ASCII-based notation system is to use the application in combination with Audiveris, an optical music recognition (OMR) engine and Musescore, a music notation software. 
Audiveris will be used to digitially scan and interpret the homework directly from an image or a PDF scan of the questions. Musescore will then be used to make minor tweaks and edits before the user can feed the resulting file into RhyhtmBalancePro. The solutions, outputted as a MusicXML file, can then be opened via Musescore to reveal the answers in music notation.
