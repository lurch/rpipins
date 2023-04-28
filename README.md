# Raspberry Pi Pico GPIO Pinout

A beautiful GPIO pinout and pin function guide for the Raspberry Pi Pico.

[![Build Status](https://img.shields.io/github/actions/workflow/status/pinout-xyz/picopins/build.yml?branch=main)](https://github.com/pinout-xyz/picopins/actions/workflows/build.yml)
[![PyPi Package](https://img.shields.io/pypi/v/picopins.svg)](https://pypi.python.org/pypi/picopins)
[![Python Versions](https://img.shields.io/pypi/pyversions/picopins.svg)](https://pypi.python.org/pypi/picopins)

Generated from [the Pimoroni Python Boilerplate](https://github.com/pimoroni/boilerplate-python).

# Usage

```
usage: picopins [--pins] [--all] or {spi,i2c,uart,pwm}
       --pins - show physical pin numbers
       --all or {spi,i2c,uart,pwm} - pick list of interfaces to show
       --hide-gpio - hide GPIO pins
       --find "<text>" - highlight pins matching <text>

eg:    picopins i2c  - show GPIO and I2C labels
       picopins      - basic GPIO pinout
```

# Installing

* Just run `python3 -m pip install picopins`