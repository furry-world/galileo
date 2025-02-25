# Galileo Gamma (1989)

Seeing the success of Delta in creative markets, Galileo decided to lean heavily into said markets and design a successor that is a true generational upgrade over Delta. It keeps the simple design and great expandability of the Delta, but with more memory and a real 16-bit processor.

## Specs

**CPU**: 65C816 @ somewhere between 10-14 MHz, depending on available crystal oscillators that match up with NTSC/PAL line rates

**RAM**: 2MB + VRAM

**VIDEO**: custom video system
    - NEEDS RETHINKING! Too similar to IBM PC!
    
<details>
    <summary>Old ideas</summary>
    - **Option 1:**
        - 320x240 bitmap display, uses a color palette (max 256 colors, 15-bit definition, so 5 bits per color channel)
        - composite, S-Video and RGB output (possibly via SCART)
        - supports PAL and NTSC
    - **Option 2:**
        - 640x480 bitmap display, uses a color palette (max 16 colors, 15-bit definition, so 5 bits per color channel)
        - VGA output (or some other RGB standard, it would require a monitor however)
    - **Option 3:**
        - combine the first two options
        - 640x480 would be displayed as interlaced on the TV, while 320x240 would be scan doubled on a monitor if VGA is used
</details>

**SOUND**:
    - Yamaha YM3812 (OPL2)
    - some 8-bit PCM playback system idk (prob similar to Sound Blaster), TBD

**OTHER**:
    - backwards compatible with Delta software
    - includes a custom graphical OS
    - scanline counter and an option to trigger an interrupt on a specific scanline
    - NES/SNES controller compatibility
    - cartridge connector
    - floppy drive connector (floppy drives are daisy-chainable)
    - several isa-like expansion slots (they expose the full system bus)