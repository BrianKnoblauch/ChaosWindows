# ChaosWindows

Win32 API version of the old Chaos demonstration program I've frequently used as my introduction to graphics on new systems.  Was ported from (and replaces) the Java paint demonstration version.  Rather than buffer results and display instead has Windows handle the buffering to keep it simple.  That sets us up for using a simple timer to give the same experience as back when I first tried it on a PC XT with the slow BIOS graphics calls.  The LC PRNG is a quick hack that doesn't even have a truly proper modulus and will have a relatively short repetition.  However, for the conditions of this demonstration it is sufficient.  I left in the technically unused increment for possible future experimentation.

Targets XDS Modula-2 v2.60
