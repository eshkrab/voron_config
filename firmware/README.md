Klipper firmware build configs (copied from ~/klipper, which is upstream Klipper and not tracked).
Use: cp firmware/<file> ~/klipper/.config && cd ~/klipper && make olddefconfig && make
- config.sb2040v2: SB2040 toolhead (RP2040, CAN 1Mbit, GPIO 4/5, bootloader offset 0x4000)
- config.skr13: mcu and z boards (LPC1769, USB serial, bootloader offset 0x4000)
- config.rpi: RP2040 CAN, same options as sb2040v2 (purpose unconfirmed)
- *.old: earlier versions
