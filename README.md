# bar-hackathon

Hardware part of the identification system

## Connection and data flow

`Tag`
 ***
`RC522` reader -> `NodeMCU v3` -> wifi -> Server (gets `Tag` id)

SDA ------------- D4
SCK ------------- D5
MOSI ------------ D7
MISO ------------ D6
IRQ (not connected)
RST ------------- D3
3V3 ------------- 3V3
GND ------------- GND