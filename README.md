# HV UPDI programmer
This project constitutes the hardware needed to program UPDI capable microcontrollers from Atmel/Microchip.

# Features
- cheap and easy to build
- PCHV - HV UPDI programming with target powercycle
- HV - HV UPDI programming
- UPDI - simple UPDI programming

It uses a 12V type A23 battery for the 12V HV source.
Can itself be programmed by UPDI or serial bootloader.
Uses the classic Arduino serial connection with DTR reset.

It is based on and inspired from:<br>
<a href="https://github.com/Dlloydev/jtag2updi">Dlloydev jtag2updi</a><br>
<a href="https://github.com/SpenceKonde/jtag2updi">SpenceKonde jtag2updi</a><br>
<a href="https://github.com/ElTangas/jtag2updi">ElTangas jtag2updi</a><br>


# Firmware
Download, build and flash the <a href="https://github.com/Dlloydev/jtag2updi/releases">latest release</a> by Dlloydev.


# Example
<img src="https://github.com/cctweaker/HV-UPDI-programmer/blob/main/example top.jpg?raw=true">
<img src="https://github.com/cctweaker/HV-UPDI-programmer/blob/main/example bottom.jpg?raw=true">

The battery holder stl file (as pictured above) is included and can be printed at 0.3mm height with a 0.4mm nozzle.