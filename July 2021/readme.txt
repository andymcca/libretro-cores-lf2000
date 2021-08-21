July 2021 Cores

- Added a lr_PCSX_ReARMed git snapshot.  
  -  The default version in the Retroleap Buildroot doesn't compile due to a bug in one of the source files.
  -  Whilst this can be fixed and then compiled, the Buildroot version is several years old.
  -  Since then, several issues in PCSX_ReARMed have been fixed by developers on Github, including fixes to the Dynarec.
  -  Therefore, better to use this version!
  -  Playstation games can be very large, but can be shrunk using compression tools.  lr_PCSX_ReARMED now supports CHD file format in addition to PBP.
  -  Several methods can be employed to reduce ISOs (e.g. PocketISO, PSXtoPBP etc etc)
  
- Added a lr_gPSP snapshot.
  -  gPSP is nice and fast for Gameboy Advance games but the version included with Retroleap is now very old and susceptible to crashing.
  -  Major improvements to the Dynarec and other areas have been made since then, improving speed, reliability and compatibility.
  
- Added a lr_mgba release (0.9.2)
  -  mgba is another Gameboy Advance emulator, not as fast as gPSP but can be more compatible/accurate.
  -  Version included with Retroleap is 0.5.1!  So many changes and improvements since then.
