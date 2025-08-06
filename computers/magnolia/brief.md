# Miatek Magnolia (1983-1989)

Miatek's first ever computer. Based on an early design of what would eventually become the Kepler Apollo, aimed at the high-end home user and born out of a desperate need for capital and market share. It ended up getting moderate success, mostly because of the fact Miatek is made up almost entirely of famous Kepler engineers.

## Specs

**CPU**: Kepler K8 @ 2.68 MHz

**RAM**: 64KB (bank-switched) + VRAM

**VIDEO**: custom video system (name TBD)
- RGBI color palette
- bitmap modes:
    - 256x192, 1-bit color
    - 128x192, 2-bit color
- tiled mode:
    - 256x192, 8x8 2-bit color tiles
- 16x 8x8 2-bit hardware sprites (available in any mode)
- adjustable scanline interrupt
- composite, S-Video and RGBI output

**SOUND**: custom sound system (name TBD)
- 4x 8x1-bit waveform channels
- 1x noise channel
- 4-bit volume control on all channels
- 16-bit pitch control on all channels (except noise which gets 8-bit pitch control)
- would allow for software-driven PCM playback by setting a channel's waveform to 0xFF and manipulating the volume control

**STORAGE**:
- cartridge
- tape (external drive)
- 5.25" floppy disk (external drive)

**OTHER HARDWARE**:
- adjustable hardware timer that triggers an interrupt in the specified number of cycles
- 2x joystick port
- built-in keyboard
- system expansion connector

**OPERATING SYSTEM**: Miatek BASIC
