# ZX Spectrum 48k Issue 6A board replica




These are PCB replicas of the motherboard of a ZX Spectrum 48k 8-bit computer. They were created on the basis of the last version of the board - "ISSUE 6A" - which was mounted in both Spectrum 48k and Spectrum+. It differs from previous versions mainly by integrating the logic and memory multiplexers in one ZX8401 chip, as well as an improved (especially in comparison with the first versions) the power supply circuit.

## The purpose of the project

I created them as a tribute to this wonderful little computer for the 40th anniversary of its creation, which for many of us started the adventure in the world of IT technology. Thanks to this replica, you can repair your old ZX Spectrum in which the connector contacts have worn off, tracks and pads have torn off after numerous repairs or have simply been destroyed by rust. After transplanting components to a new board, your Spectrum will not only gain a new life, but also a great look.

The ISSUE 6A board requires the following components:

- Zilog Z80 processor
- ZX8401 / PCF1306P chip - or its cheap direct replacement built on SMD 74LS chips
- ULA in any version (originally on this board was Ferranti 6C001E-7) or a perfect, modern replacement vLA82
- original ZX Spectrum ROM or EPROM 27C256/27C512 with programmed BASIC binary (requires a slight modification or adapter, e.g. ZXROM 4-in-1)
- lower memory chips type 4116 (e.g. TMS4116-15NL, STC 4116-2N) or a modern SRAM replacement board
- upper memory chips type 4532 or compatible (e.g. TMS 4532-20NL4, OKI M3764-20RS) or modern SRAM module
- LM1889 video modulation chip
- UM1233 RF modulator or S-VIDEO mod board or simple composite output mod

## BOM:

https://docs.google.com/spreadsheets/d/1GlukvK-rJ6DSs6qOmtWpRyai1MQ1hy25GcS9ePSdg4E/edit?usp=sharing

## Alternative components:
- PCF1306P (ZX8401): https://trastero.speccy.org/cosas/JL/pcf1306p/PCF1306P.html
- S-Video Mod: https://github.com/redhawk668/ZX-Spectrum-S-Video
- Composite Mod: https://www.projectavr.com/esp-01-esp-03-flash-prototyping-board/

## Useful resources:
- Schematics: https://spectrumforeveryone.com/technical/zx-spectrum-pcb-schematics-layout/
- Service manual: https://spectrumforeveryone.com/wp-content/uploads/2017/08/ZX-Spectrum-Service-Manual.pdf
