# cake
Mirror of Martin Fierz's endgame database generator, compressor and access code for his checkers program Cake

The original builddb4 and compressdb3 code was cleaned up for building 8-man databases.  This code can be modified for building different size databases (4-man, 5-man, etc..) by simply changing the value for MAXPIECES or MAXPIECE in the checkers.h file for each program.  The code can also be modified to build suicide checkers (anti-checkers) databases by editing the dbmain.c and lookup.c files for builddb4, and the compressmain.c program for compressdb4.

Please note that the 8-man databases are large, about 34.5GB uncompressed, and about 4.3GB after compression; however, lower values of MAXPIECES in the code produce much smaller sized databases.
