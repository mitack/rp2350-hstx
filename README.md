# rp2350-hstx

Permanent hardware graphics mode: 800x600, split into:
* User text mode- all modes up to 68/0044h/100×60/8×8/800×480 - see https://en.wikipedia.org/wiki/VGA_text_mode#PC_common_text_modes
* Permanent lower 120 pixels = 15 lines reserved for system stats(cpu load etc), help/keys etc.

Text format is 2 bytes per character- see https://en.wikipedia.org/wiki/VGA_text_mode#Text_buffer

Memory usage:
* Graphics mode: 800\*600 = 480,000
* Text mode: 100\*75\*2 =  15,000
* Total buffers: 495,000
* Memory left on the device: 25,000


## Links, Pinouts and Schematics:
​
​https://learn.adafruit.com/adafruit-rp2350-22-pin-fpc-hstx-to-dvi-adapter

https://learn.adafruit.com/adafruit-rp2350-22-pin-fpc-hstx-to-dvi-adapter/pinouts

https://learn.adafruit.com/adafruit-rp2350-22-pin-fpc-hstx-to-dvi-adapter/overview

​https://learn.adafruit.com/adafruit-rp2350-22-pin-fpc-hstx-to-dvi-adapter/downloads

http://www.alciro.org/alciro/conectores_26/patillas-cable-HDMI-a-DVI-D_274_en.htm

https://www.fountainware.com/EXPL/video_modes.htm

https://en.wikipedia.org/wiki/List_of_common_display_resolutions

https://en.wikipedia.org/wiki/VGA_text_mode

