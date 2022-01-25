# lavaplayer-natives
Native files compiled for use in https://github.com/sedmelluq/lavaplayer

This is a workaround for lavaplayer not working on aarch64 OS:
- open your archive folder (i.e .jar) with 7zip or some other tool
- find and enter into /natives directory
- copy linux-aarch64 folder from this repository and paste it into /natives
- make sure you have YOUR_ARCHIVE/natives/linux-aarch64 directory now
- optionally you can test the entire zip file for compatibility inside 7zip or such
- done,  you can run your program on 64-bit arm architecture now!

*DISCLAIMER*: There is a lib for 32-bit, but the sound quality will get affected by using it instead over 64 version.
