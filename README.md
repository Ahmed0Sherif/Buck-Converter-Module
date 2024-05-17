# Intro
- For graduation project, it was required to build a BMS system, capable of measuring battery pack capablilites.
- It was preferable to obtain 5V from the 12V pack efficiently, to conseve pack's capacity.
- Therefore, a small buck converter was in need.
- These designs are made on Altium 22'

# A: MC33063
## Schematics:
<p align="center">
<img src="https://github.com/Ahmed0Sherif/Buck-Converter-Module/assets/93788514/816c4937-f3c6-4938-befb-865f69dcee55" width="500" height="auto">
</p>

The used component values are displayed in the LTspice simulation:
<p align="center">
<img src="https://github.com/Ahmed0Sherif/Buck-Converter-Module/assets/93788514/ca29dc5f-ac91-4994-8444-9e060c6eaa63" width="700" height="auto">
</p>

The results: 
<p align="center">
<img src="https://github.com/Ahmed0Sherif/Buck-Converter-Module/assets/93788514/b69b9d88-35c5-4726-a916-4b84cc92649e" width="500" height="auto">
</p>

## PCB:
<p align="center">
<img src="https://github.com/Ahmed0Sherif/Buck-Converter-Module/assets/93788514/27407164-ddf5-4644-a0dd-28b27454bd2f" width="500" height="auto">
</p>

<p align="center">
<img src="https://github.com/Ahmed0Sherif/Buck-Converter-Module/assets/93788514/c1f579e6-60fc-4960-beb5-6bbfba628bc5" width="500" height="auto">
</p>

## N.B.
- MC33063 has a maximum current capabilities of 250mA @ 5V output, with temperature of 70 degree Celsius.
- Therefoe, this IC was not suitable for the application.

# B: MT2492
## Schematics:
<p align="center">
<img src="https://github.com/Ahmed0Sherif/Buck-Converter-Module/assets/93788514/334619b9-c617-4daf-bab5-07cbfb3a0ad6" width="700" height="auto">
</p>

## PCB:

<p align="center">
<img src="https://github.com/Ahmed0Sherif/Buck-Converter-Module/assets/93788514/c8583913-f26d-4cc6-94ad-6f8bf81c21dd" width="500" height="auto">
</p>

<p align="center">
<img src="" width="500" height="auto">
</p>

