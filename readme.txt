Shield: Corne (aka crkbd aka heliodox) 
Board: Nice!Nano V2
Keymap: Qwerty
OLED: Yes
RGB: So far Underglow only -- per Key RGB not working -- could be soldering not sure. 
KeyMap: RGB Keys not working. Might reverse Shift and control. all layers work well
Bluetooth: Yes -- display name is in corne.conf

NiceNanos are soldered face down (showing black silk screen up and led under)

SDA  - 17
SCC  - 20
ROW0 - 22
ROW1 - 24
ROW2 - 32 // (p01.00) = p(01)*32 + 00
ROW3 - 11


MOSI - 06
trrsDATA? - 08
COL1 - 31
COL2 - 29
COL3 - 47
COL4 - 45
BLED - 15

corne.conf - basic config settings - name, led, oled
corne.keymap - keylayout
nice_nano_v2.overlay - define spi for rgb underglow
oled.dtsi - define OLED display

