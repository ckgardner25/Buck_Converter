# Buck_Converter
Designed and built a custom synchronous buck converter (5–20 V input, 3.3 V regulated output) using a PIC16F18313 microcontroller for digital PWM-based closed-loop voltage regulation. Developed embedded firmware with complementary PWM, programmable dead time, and ADC-based voltage sensing, achieving an ideal conversion efficiency of up to 95%, a 16.5% duty cycle for 20 V to 3.3 V conversion, and <1 ms settling time validated through PSpice simulation.

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
