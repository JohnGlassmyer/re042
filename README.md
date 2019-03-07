# re042

Replace the 8042 keyboard controller on vintage (286/386/486) PC-AT motherboards and interface with various (USB, serial, PS/2) keyboards and mice not natively supported on such systems.

- a device taking the place of the (40-pin DIP) 8042 on the motherboard, acting as master on a new I2C bus
  - PCB
  - firmware
- one or more devices acting as slaves on the same I2C bus, interfacing with various keyboards and mice
  - PCB
  - firmware
