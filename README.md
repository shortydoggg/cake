# cake
Mirror of Martin Fierz's endgame database generator, compressor and access code for his checkers program Cake

The original builddb4 and compressdb3 code were cleaned up for building 8-man databases.  This code can be modified for building different size databases (4-man, 5-man, etc..) by simply changing the value for MAXPIECES or MAXPIECE in the checkers.h file for each program.  The code can also be modified to build suicide checkers (up to 7 pieces) databases by editing the checkers.h, dbmain.c, and lookup.c files for builddb8; and the checkers.h and compressmain.c program for compressdb8.  To run the compiled executables, you must place both the builddb8 (or renamed) and compressdb8 (or renamed) executables in the same directory and make a new directory called "raw" inside the same folder as the compiled executables for them to build the databases.

Please note that the 8-man databases are large, about 34.5GB uncompressed, and about 4.3GB after compression; however, lower values of MAXPIECES in the code produce much smaller sized databases.  Note that MAXPIECES>4 could take a very long time to build the databases, depending on your computer.

For the releases, place the builddb8.exe (or builddbx.exe) and the compressdb8.exe (or compressdbx.exe) files in a folder called db, preferably with this same dbgen.bat file either inside or just outside of the db folder.

