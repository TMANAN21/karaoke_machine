As suggested in the name, this is a karaoke machine which currently only plays twinkle twinkle little star but could add other songs in it. The code is written in MIPS assembly language and performed in the Harvard Architeture style MIPS machine with added MIDI sound system. The actual assembly code is written on twinkle_twinkle.txt. 

Within the txt file, I use 32 bits for my instructions and within the 32 bits the first 8 bits are for the notes of the song, the next 7 bits are for the velocity of the song, the next 1 bit is to turn on/off the vibration of the sound, then the next 14 bits are for the timing of the chords and notes and the last 2 bits are for the instruction for either sending lyrics to the console, or sending lights to the console or sending notes/chords to the MIDI audio device.

The twinkle_twinkle_code.txt includes the machine language translation for the instructions and the twinkle_twinkle_data.txt include the machine language translation of the information needed to store in the data memory. Lastly, the mips_Twinkle.circ is the Harvard Architetural MIPS machine in logism.

Contirbutors: The Harvard Architeture style MIPS machine was provided to me by my professor, Kevin Walsh, and he helped me throughout the project in figuring out a succint way of using all the 32 bits to do a function. Furthermore, the MIDI sound was provided by kahdeg and Kevin Walsh. 

** Warning ** 
  For some reason, the MIDI audio device lags on mac, but works perfectly fine on windows.
  
The following link is a video of how the machine works: <iframe width="560" height="315" src="https://www.youtube.com/embed/w85w8RRLAOg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

