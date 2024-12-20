# composition-maxpatch
This is a program created in Max Patcher that uses inputs from MIDI tools such as the KOMPLETE KONTROL keyboard and the nanoKONTROL tool as inputs to create notes and loop audio files, as well as a microphone to capture audio input that will be manipulated.

The tools that are used are:
1. Max Patcher (the programming interface)
2. Keyboard (for inputs)
3. KOMPLETE KONTROL (for note creation and manipulation)
4. nanoKONTROL (for inputs, looping, and volume control)
5. Microphone Input

### <ins>MIDI Keyboard<ins>
A MIDI keyboard is used to play notes, and the specific keyboard I used is a KOMPLETE KNOTROL. The program manipulates the notes using a triangle oscillator.

### <ins>Computer Keyboard<ins>
A computer keyboard is also used to play different MIDI drum beats that I created and recorded on a DAW (Digital Audio Workstation). The program can track key inputs from 1-5 and play the respective beats programmed to those keys, or track input 0 and stop playing beats altogether. I have looped the drum beats in the program so that they will keep looping and playing once they are inputted.

### <ins>nanoKONTROL<ins>
This is the tool that keeps everything together. This controls the volume input for every single instrument, including the MIDI keyboard. input microphone, and drums programmed to the computer keyboard. It also controls five other instruments, which includes a variety of string and pad loops, that will play on top of each other and loop or stop when certain inputs are pressed. The dials of the nanoKONTROL are also used, with some to control the panning and others to control the reverb. One dial is used to control the triangle oscillator for the MIDI keyboard notemaker, making it sound more aggressive if desired.

### <ins>Microphone Input<ins>
This tool captures the input of my voice. When sound is inputted into the microphone, the program recognizes the frequency that is being played and retunes it before outputting it into the output device, creating an autotune effect. This input is also constantly being panned left and right due to a part of the program that constantly moves the panning automatically.



A video demonstration is also in this repository demonstrating how this program works and how I used this program to play a composition of my own.
