These are some 7400-series like logic devices. I'll build the devices necessary to make a shift register, and then create a sim showing SPI control of a 32-bit serial to parallel converter. This type of device is useful when you need a large number of digital outputs and have limited I/O.

Devices modeled:
- 74AC00 - NAND gate
- 74AC04 - Inverter
- 74AC74 - D-type flip flop with set and reset
- 74HC540  - Tri-state inverter
- 74AC595 - 8-bit shift register with tri-state outputs

- LMC555 - 555 timer, reverse engineered from die photos
