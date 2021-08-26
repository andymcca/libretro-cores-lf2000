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
  
- lr_gpsp
  - The Libretro version of GPSP has been significantly improved over the last few years. Many games now going further in=game and less crashing.
  - In the last month, contributor davidgfnet has made several commits including some interpreter fixes, hence I have compiled another snapshot this month.
  - Tested with Mario Golf Advance Tour, which had a restart bug with the original gpSP.  This now goes in-game and hasn't crashed yet.
  - Last month's snapshot would crash when putting on Hole 1, but this appears to now be fixed!
  - Undoubtedly many other games have benefited from the recent work on this core, so many thanks to davidfgnet!!
  
  lr_vice_x64 (Commodore 64 Emulator)
  - Had a bit of trouble getting this to compile as it's not on the Retroleap Buildroot tree.
  - Finally realised I just hadn't specified the correct C++ compiler location - once fixed it went through and compiled ok.
  - Initial test (with R-Type) went ok, went in-game but seems quite slow.
  - Looking online this is a common issue with this emulator, and there are a myriad of Quick Menu options to play with to improve it.
  - This is a Git snapshot, but identifies as version 3.5.
  - There are many machine options during compilation (e.g. C128, Commodore Plus 4 etc), but this is the standard C64 build.
  
  
