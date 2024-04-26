# Mistrum
Mistrum is a legendary czechoslovak functional clone of famous ZX-Spectrum, more details at [8bit-replicas.com](https://www.8bit-replicas.com)

![IMG_20210711_214109](https://user-images.githubusercontent.com/89099767/129786291-4849a68c-49f7-4a31-9ca0-8c69139bf45b.jpg)

# Repository content
Here you can find schematics, PCB, gerber files, BOMs, binary content for memories and some ideas for build a replica.

# Main parts
- Rerouted PCB for replica of Mistrum computer (less vias and no additional wiring)
- PCB with original routing (500+ vias and ca. 40 wires)**
- PCB for PAL color video generator replica
- PCB for EPROM card replica**
- PCB for newly designed keyboard (Cherry MX extended keyboard)
- PCB for newly designed adapter to analog RGBi SCART or VGA 15kHz color video output
- PCB for newly designed adapter to standard ZX Spectrum system connector**

** will come later

**All schematics and PCBs are made using KiCad.**

## Extended Cherry MX Keyboard

The newly designed extended Cherry MX Keyboard features:
- Mechanical Cherry MX switches
- ZX Spectrum compatibility
- Optional bus or external power supply (external is deafult for Mistrum)
- Extended to separate cursors keys, delete key and special Mistrum keys (key Mistrum, NMI and RESET), realized as logic switches
- Two LED indicators, optional (for example BOOT, DRIVE)
- Two PCBs - main board and mask
- Identical size and mounting holes as PMD-85 coputer keyboard
  
![Cherry MX Keyboard](https://raw.githubusercontent.com/72ka/Mistrum/main/Klavesnice/Mistrum_Klavesnice_ISO.jpg)

## Adapter to analog RGBi or VGA 15kHz video output

This adapter outputs an analog RGB signal or VGA signal (15kHz only). It is designed mainly for color video output to RGB SCART capable TV and provides the high quality color video output.
  
![Video adapter](https://raw.githubusercontent.com/72ka/Mistrum/main/Video_konvertor/Mistrum_VideoKonvertor.jpg)

