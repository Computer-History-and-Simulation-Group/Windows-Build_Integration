Files that have been modified for SIMH:

 The entire .\PCRE\pcre-vsbuild directory is unique for SIMH.
 Edit the .vsproj files in .\PCRE\pcre-vsbuild\build\vc2008 to point to a new version if necessary.

 The .\PCRE\pcre-8.45 directory is unmofified from the .zip file (distribution).


There is a bug in v8.45 pcregrep.c, you need to reolace it with the v8.43 version and the Visual C++ 2008 builds will complete without errors.

config.h (based on config.h.generic) updated to reflect version change.
pcre.h (based on pcre.h.generic) updated to reflect version change.

