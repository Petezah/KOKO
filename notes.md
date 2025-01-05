avrdude -p t85 -c stk500v1 -P /dev/ttyS3 -b 115200 -U flash:w:firmware.hex:i

Fuses:
Low:
0xE2

High:
0xDF

Extended:
0xFF

avrdude -p t85 -c stk500v1 -P /dev/ttyS4 -b 115200 -U lfuse:w:0xE2:m
