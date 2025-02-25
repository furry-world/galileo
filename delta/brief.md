# Galileo Delta (1983)

Galileo's first ever computer. Initially intended as a general-purpose high-end computer, because of its simple design, great expandability and advanced graphics capabilities it found a niche in creative workloads like pixel art, music production and even development. This prompted Galileo to release a number of expansion cards and peripherals catered to said workloads, like a MIDI card, a mouse and serial controller, as well as RAM expansion cards.

## Specs

**CPU**: some 6502 variant @ prob 3.4 MHz or ideally a multiple

**RAM**: 64KB (bank-switched) + VRAM

**VIDEO**: custom video system
    - 256x240 bitmap display with 2-bit graphics, uses a color palette (max 4 colors, 12-bit definition, so 4 bits per color channel)
    - composite, S-Video and RGB output (possibly via SCART)
    - supports PAL and NTSC

**SOUND**: custom sound system
    - 4 8x1-bit waveform channels
    - 1 noise channel
    - 4-bit volume control on all channels
    - 16-bit pitch control on all channels
    - would allow for PCM playback by setting a channel's waveform to 0xFF and manipulating the volume control

**OTHER**:
    - includes a custom version of BASIC
    - scanline counter and an option to trigger an interrupt on a specific scanline
    - NES/SNES controller compatibility
    - cartridge connector
    - floppy drive connector (floppy drives are daisy-chainable)
    - several isa-like expansion slots (they expose the full system bus)
