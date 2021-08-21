August 2021

- lr_caprice32 (Amstrad CPC464/6128 Emulator) v4.2.0
  -  Couple of issues with compiling - one was a missing compiler option (std_c99), the other was a problem line of code which I amended.
  -  Not tested.
  
- lr_gambatte (Gameboy Emulator)
  -  Git snapshot.  Not Tested.
  
- lr_picodrive (Sega Master System / Megadrive)
  -  Issue with compiling this both on the Retroleap build and using the latest Git.  Couldn't find C header files even though they are there.
  -  Turns out that the search folders specified for 'include <xxxxx.h>' statements don't include the root folder of the source.
  -  Once corrected, this built ok.
  -  Git snapshot.  Not tested.
  
  
