# Tashtari's Miscellaneous Macintosh PCBs

All files created in Eagle CAD 6.5.0.  All boards believed but not guaranteed to be correct - **use at your own risk**.


## da15-to-de15-passive

A compact adapter board for passive conversion of Macintosh video to VGA video, with DIP switches to set the behavior of the ID lines and a guide on the back for how to do so.


## hdi20-floppy

An adapter board for use with a cable stolen or borrowed from a PowerBook 100 floppy drive, allowing the PowerBook 100 to be connected to a device such as a [TashTwenty](https://github.com/lampmerchant/tashtwenty) or Floppy Emu.

The mating connector for the PowerBook 100 cable is a [JAE LY20-20P-DT1-P1E-BR](https://www.digikey.com/en/products/detail/jae-electronics/LY20-20P-DT1-P1E-BR/5397746).


## mac-serial-interposer

An interposer for a Macintosh serial port which, combined with a standard crossover serial cable, can be used to probe the signals on the line.


## mac-serial-interposer-26ls32

Same deal as mac-serial-interposer above, but adds a 26LS32 RS422 receiver IC to convert the differential lines into standard logic level outputs.


## phonenet

A PhoneNet-compatible dongle for LocalTalk networking.  Provides pinholes for connecting a mini-DIN cable.


## phonenet-de9

Same deal as phonenet above but instead of pinholes for a mini-DIN cable, it provides a 2x10 header that can be connected to an IDC-to-DE9M serial ribbon cable wired using the Intel/DTK (not AT/Everex!) standard.
