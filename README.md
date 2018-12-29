In this project a DFPLAYER is used to play mp3 and wav sound files to a speaker/headphones/line out. An Aruino Nano is the microcontroller utilizing serial communication with the DFPLAYER.  A rotary endcoder is read by the Nano to select a previous or next file from the SD card on the DFPLAYER.  The push button on the rotary encoder starts the play function.  Pushbuttons on the IO1 and IO2 inputs to the DFPLAYER can also be used to select audio files with a short push or volume up or down with a long push. A 128x64 oled displays the present file number.  The files on the SDPLAYER SD memory card have a specific file name sequence. For example. if the first filname was sound.mp3, the first file would be named 0001sound.mp3. The next file name would be 0002filename.mp3.  Due to the fact that the Nano uses serial communication with the DFPLAYER, you have to disconnect the RX TX from the DFPLAYER for programming the Nano.