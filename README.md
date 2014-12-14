arduino-etch-a-sketch
=====================

An Arduino Etch-A-Sketch project

This is a pretty simple sketch that builds an Etch a Sketch with electronics.
I used a monochrome 128x64 pixel OLED display from ebay, you can find them
by searching:
  "I2C IIC SPI Serial 128X64 OLED LCD LED Display Module for Arduino"

Additional hardware required:
- two pushbuttons
- two rotary potentiometers (I used 10K Ohm)
- a breadboard
- a bunch of wires

The OLED display I bought was based on the SH1103 chip, which is slightly
different to the SSD1306 chip which for example Adafruit sells. I found
a library for the SH1103 display on the Arduino forum:
  http://forum.arduino.cc/index.php?topic=242880.0

I included a Fritzing schematic (See the .fzz and .png files in this directory).
Enjoy!
