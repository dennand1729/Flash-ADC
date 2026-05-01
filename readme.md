# 2 Bit Flash ADC Project  

## Table of Contents

- [Summary](#summary)
- [Design Specifications](#design-specifications)
- [Demo](#demo)

## Summary  

As of April 2026, I have taken both analog and digital circuits classes. I wanted to build project that took theory from both and applied it toward a useful end-goal. I decided to build a flash analog to digital converter.

For those who don't know-- an analog to digital converter uses a reference-voltage resistor ladder to establish threshold voltages. These references voltages can be compared to some input using comparator IC or a rail to rail op-amp-- I use the latter. If the input is higher than the reference the op-amp lights up an LED corresponding to the threshold voltage it surpassed. This is what is known as thermometer code.

[COMING SOON] Next steps for the project are using digital logic to convert this working thermometer code to binary using an ESP32 microcontrolller. Stay tuned!

## Design Specifications

## Demo

Here is a picture of the breadboard circuit so far. As of May 1, 2026 it is able to convert an input signal to Thermometer code.

![ADC Graphic 1](ADC.jpg)

