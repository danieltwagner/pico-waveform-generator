# Arbitrary Waveform Generator for Raspberry Pi Pico

![AWG3](https://github.com/favict/pico-waveform-generator/assets/45994341/4bb95f53-b20d-49c1-be59-70a8377965b7)

Modified to support SSD1306 display + rotary knob. The original author hasn't yet merged these changes so I'm keeping them up here.

## Known issues
[Waveform stops and turns into noise after a few minutes](https://github.com/favict/pico-waveform-generator/issues/2)

## Setup

Start with the micropython uf2, then use [mpremote](https://docs.micropython.org/en/latest/reference/mpremote.html):
```
mpremote cp -r utils generation display control :
mpremote cp main.py :
```
