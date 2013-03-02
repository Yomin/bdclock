# Bulbdial Clock Board

Board for the bulbdial clock developed at
[Evil Mad Scientist Laboratories](http://www.evilmadscientist.com/2009/a-bulbdial-clock/).
Due to current availability of only attiny45's the multiplexing is partly outsourced with
one 7bit binary counter and two 8bit addressable latches.

For synchronization the board is equipped with a socket for a pollin DCF77 module (810 054).

## License

MIT

## Parts

count|name|info
---|---|---|---
1x|attiny 25/45/85|
1x|HEF4024B|7 bit binary counter
1x|HCF4724B|8 bit addressable latch
2x|BC547B|
1x|red diffuse led|
1x|4pin socket|
1x|10pin isp socket|
1x|powerjack|
1x|2pin clamp|power
1x|3pin clamp|led gnd
1x|12pin clamp|led vcc
2x|1N4004|
1x|300nF|
1x|100nF|
1x|1uF pol|
1x|7805|
6x|10k|
1x|1k|
4x|250|
1x|pollin dcf77 module|
36x|white point leds|for the actual clock
