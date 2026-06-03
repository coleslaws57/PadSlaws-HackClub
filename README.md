# PadSlaws-HackClub
My real attempt at making/designing a hackpad

PadSlaws
My PadSlaws is a 4 key macropad with a rotary encoder, an OLED Display, has 4 LEDs under each bey, and uses QMK firmware.

Features:
Dual layer plastic case with an extra acrylic piece to protect the inside.
128x32 OLED Display.
EC11 Rotary encoder.
4 RGB LEDs.
4 Keys.

<img width="1075" height="574" alt="Screenshot 2026-06-02 183146" src="https://github.com/user-attachments/assets/07315b8f-3d49-439c-b20b-01ae2ab89083" />
Made in Fusion360.
CAD Model: 

Everything fits together using 4 M3 Bolts that hold it all together.

It has 3 separate printed pieces. The base where the PCB sits, and the top cover and one acrylic plate. One to cover the electronics, so that you can see all the cool stuff on the inside.

<img width="914" height="594" alt="Screenshot 2026-06-02 183122" src="https://github.com/user-attachments/assets/937a2e44-b717-42bc-9651-1b64ef4a7534" />
Schematic

PCB
Here's my PCB! It was made in KiCad.

<img width="1005" height="745" alt="Screenshot 2026-06-02 183103" src="https://github.com/user-attachments/assets/218fff5e-09d5-4d0d-be3b-39b065dac786" />
PCB Schematic

Firmware Overview
This hackpad uses QMK firmware for everything.

Right now all the keys just do basic stuff (typing letters), but I probably change them later.

BOM:
Here should be everything you need to make this hackpad

Qty	Part
1	  Seeed Studio XIAO RP2040
4	  Cherry MX compatible switches
4	  1u keycaps
4	  SK6812MINI-E RGB LEDs
1	  EC11 rotary encoder with push switch
1	  Encoder knob
1	  0.91" I2C OLED display
1	  1x04 2.54mm pin header for OLED
1	  Custom PCB
1	  3D printed top case
1	  3D printed bottom case
4	  Screws
4	  Heat-set inserts or nuts
