# Buck_Converter

## Overview
Designed and built a custom synchronous buck converter (5–20 V input, 3.3 V regulated output) using a PIC16F18313 microcontroller for digital PWM-based closed-loop voltage regulation. Developed embedded firmware with complementary PWM, programmable dead time, and ADC-based voltage sensing, achieving an ideal conversion efficiency of up to 95%, a 16.5% duty cycle for 20 V to 3.3 V conversion, and <1 ms settling time validated through PSpice simulation.

## Specifications
Input Voltage: 5–20 V

Output Voltage: 3.3 V

Switching Frequency: 100 kHz

Control: Closed-Loop PWM

Dead Time: Programmable

Efficiency: Up to 96%

Settling Time: <1 ms

Simulation Suite: PSpice

## Block Diagram
<img width="500" height="350" alt="schematic" src="Block_diagram/Block_diagram.png" />

## Control Strategy
The PIC microcontroller generates complementary 100 kHz PWM signals with programmable dead time. The input signal first passes through two capacitors for input filtering and current stabilization. It then drives a MOSFET whose gate is controlled by a PWM signal. The output subsequently splits into two paths: one through a second PWM-controlled MOSFET and the other through a 47 µH inductor, which helps regulate voltage and reduce ripple. Finally, the output passes through two additional capacitors to further smooth the current and improve output stability.

<img width="400" height="350" alt="schematic" src="Simulations/20V_input_3.3V_output.png" />

## PCB Design
<br><p float="left">
<img width="400" height="350" alt="DMM example" src="Renderings/Overview.png" />
<img width="400" height="350" alt="DMM example" src="Renderings/Bottom.png" />
</p>

## Simulation Results
<img width="500" height="350" alt="DMM example" src="Simulations/Screenshot 2026-07-29 225215.png" />


## Measured Results

