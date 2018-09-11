# Arduino Robotic Glockenspiel
![Client Photo](https://github.com/bonnette/AutoGlockenspiel/blob/master/photos/ful_pic3.jpg)
<br/>
An automated Glockenspiel Arduino Project
Inspired by an Instructable
</br>
https://www.instructables.com/id/Making-the-Spielatron-Robotic-Glockenspiel/
</br>
This is my interpertation with modifications
</br></br>
This project uses a Raspberry Pi 3 B+ with Raspberian Stretch as its operating system. The Pi is used to run applications spelled out by this instructable (https://www.instructables.com/id/How-to-Send-MIDI-Music-to-the-Spielatron/). The applications are installed onto the Pi and I use Windows RDP to connect to and operate these applications.
</br></br>
The MIDI control of the hammers is controlled by an Arduino Pro Mini. the serial connetion between the Pi and the Arduino is accomplished through an FTDI interface. This interface allows music that has been converted to a MIDI file to be played on the Glockenspiel.
</br></br>
The Glockenspiel is a Pearl 32 note that I purchased off of Ebay for $45
</br></br>
There are two Arduino programs.</br>
The Soielatron_V2.ino file is the origional application off of Instructables</br>
The Spielatron_mod.ino file has modifications of the rotation table for the hammers. This was necessary because my Glockenspiel is a different physical size. 
