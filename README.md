<p align="center">
  <img src="https://github.com/Flamingo-tech/INA700/blob/main/Pictures/2024-06-29T09_58_00.211Z-Screenshot%202024-06-29%20115822.png"/>
</p>

### What is it?

The INA700 is a digital power monitor that includes an integrated shunt resistor and a 16-bit delta-sigma ADC, specifically designed for current sensing applications. It can measure currents up to ±15.728 A with a full-scale range, operating over a common-mode voltage range of –0.3 V to +40 V.

This device provides precise reporting of current, bus voltage, die temperature, power, energy, and charge accumulation, utilizing a ±0.5% integrated oscillator for accuracy, while performing calculations in the background. The integrated temperature sensor maintains ±3°C accuracy across the junction temperature range.

With low offset and gain error drift, the INA700 can be employed in systems without requiring temperature calibration during manufacturing. It offers selectable ADC conversion times ranging from 50 μs to 4.12 ms and supports sample averaging from 1x to 1024x. These features effectively reduce data noise and allow for customization of overcurrent detection windows.
Why did you make it?

The INA700 is really really really cool! But it is very hard to use as a tinkerer because of the component size. This is why I build an opensource DEV board that people can use ^^.

### What makes it special?

The INA700DEV is compatible with:
- TI-SCB.
- Breadboard Friendly!
- Easy test points for logic analysers.
- Arduino Library is comming :)

<p align="center">
  <img src="https://github.com/Flamingo-tech/INA700/blob/main/Pictures/INA-1.gif"/>
</p>


### IC specifications:

## Low loss integrated shunt resistor

– Internal resistance: 2 mΩ at TA = 25°C

– Current rating: ±15 A at TA = 25°C

## High-resolution, 16-bit delta-sigma ADC

– Wide common-mode range: –0.3 V to +40 V

– Reports current, bus voltage, power, internal temperature, energy, and charge.

– Programmable conversion time and averaging

## Current monitoring accuracy:

– Total Measurement Error: ±0.5% at 5 A

– Offset current: ±1.5 mA (maximum)

– Gain error: ±0.5% (maximum at 5 A)

– Gain error drift: ±50 ppm/°C (maximum)

## Power monitoring accuracy:

– 0.85% accuracy at 5 A

## Energy and Charge accuracy:

– 1.35% accuracy at 5 A

## Others

Internal monitoring and fault detection

Precision oscillator: ±0.5% (maximum)

2.94-MHz High-Speed I2C interface with 4 pin- selectable addresses

Operates from a 2.7-V to 5.5-V supply

– Operational current: 640 μA (typical)

– Shutdown current: 5 μA (maximum)


#### You can buy one here : https://www.tindie.com/products/theflamingo/ina700-dev/
