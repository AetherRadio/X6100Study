# Aether's Xiegu X6100 notes [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A repository dedicated to annotate the findings when hacking the
[Xiegu X6100 HF+6m transceiver](https://www.radioddity.com/products/xiegu-x6100).

## Architecture

The radio has been described as a "tablet on top of a radio". Such isn't far
from the truth. The radio is composed by two separate parts:

- An STM32 microcontroller connected to all the radio bits.
- An AllWinner SoC running a Linux operating system.

These two systems use a set of commands to communicate.

----

## TODO list

## Technical

- [ ] Add the model of the STM32 microcontroller.
  - [ ] Link the datasheet.
- [ ] Add the model of the AllWinner SoC.
  - [ ] Add
    [this link](https://www.agipcb.com/products-category/allwinner-r16-quad-core-cortex-a7-linux-android-smart-home/)
    to it.
  - [ ] Link the datasheet if one is available.
- [ ] Draw a nice diagram of the base architecure.
- [ ] Gather all scattered knowledge.
- [ ] Add information about how the base firmware is like the Xiegu X90.
- [ ] Add information about how the base firmware is based on
  [UHSDR](https://df8oe.github.io/UHSDR/).
- [ ] Add that libraries like [liquid-dsp](https://github.com/jgaeddert/liquid-dsp)
  are used in the frontend firmware.
- [ ] Add the information about the private key of the base firmware **without
  publishing it**.
- [ ] Add info about SSH/TTY into the **stock** firmware, and the root access.

## Formatting

- [ ] Separate the different sections into different directories and `readme.md`
  files as they get larger.
