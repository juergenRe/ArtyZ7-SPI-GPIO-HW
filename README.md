Arty Z7-20 hardware definition including:
- Zynq
- 4 buttons / 4 LEDS via GPIO instance 1, using interrupts
- SPI & IIC interface from Zynq enabled
- 2nd GPIO component linked to ChipKit IOs. This block does not use interrupts.

This hardware definition is used with the ArtyZ7-SPI-GPIO-SW project. Any change on hardware needs to be reimported there.

