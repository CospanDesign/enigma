Use Adafruit_RA8875 as a basis for configuring the LCD Panel Controller.

This is probably similar to the SSD1963. There is probably a sequence of commands that must be sent down to the LCD Controller so that it must be set up.

Quickly looking over the documentation it looks like the controller supports a mode where the user can write commands liek 'draw line' or 'draw circle' in order to support simple drawing tools. There also looks like a mode where you'll treat the display like a normal monitor. There is something to do with CACB H/W Enable [1:0]