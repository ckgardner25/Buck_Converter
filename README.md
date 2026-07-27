# Buck_Converter
Designed and built a custom synchronous buck converter capable of operating from a 5–20 V input using a PIC16F18313 microcontroller for digital PWM control. The project combines embedded firmware, power electronics, and PCB design to create a programmable DC-DC converter suitable for experimentation with closed-loop voltage regulation.

## Features
Custom synchronous buck converter power stage using N-channel MOSFETs
PIC16F18313 generates complementary PWM with programmable dead time
Input voltage sensing (5–20 V) using the MCU's ADC
On-board 5 V linear regulator to power the microcontroller
Test points for PWM signals, output voltage, and power rails for debugging
four-layer PCB designed in KiCad

## Renderings
<br><p float="left">
<img width="400" height="350" alt="DMM example" src="Renderings/Overview.png" />
<img width="400" height="350" alt="DMM example" src="Renderings/Bottom.png" />
</p>
