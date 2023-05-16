# pfFPGATools

[![GPL-v3.0](https://img.shields.io/github/license/DidierMalenfant/pfFPGATools)](https://spdx.org/licenses/GPL-3.0-or-later.html) [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pfFPGATools.svg)](https://python.org) [![PyPI - Version](https://img.shields.io/pypi/v/pfFPGATools.svg)](https://pypi.org/project/pfFPGATools)

A set of tools for building and installing [**openFPGA**](https://www.analogue.co/developer) cores for the [**Analog Pocket**](https://www.analogue.co/pocket).

Copyright (c) 2023-present Didier Malenfant.

openFPGA is a registered trademark of [**Analogue**](https://analogue.co).

-----

### Installation

**pfFPGATools** requires at least [Python](https://python.org) 3.7. Make sure you have a [supported version](http://didier.malenfant.net/blog/nerdy/2022/08/17/installing-python.html) of **Python** before proceeding.

You can then install **pfFPGATools** by typing the following in a terminal window:
```console
pip install pf-fpga-tools
```

### Installation (macOS)

Also install the following tool dependencies via [brew](https://brew.sh):
```console
brew install imagemagick
```

### Installation (Ubuntu Linux)

Also install the following tool dependencies:
```
sudo apt install imagemagick
```

### Usage

**pfFPGATools** provides the follow commands commands, sometimes with one or two extra arguments:

- `pfBuildCore` - Build a core according to a `toml` config file.

- `pfInstallCore` - Install a zipped up core file onto a given volume.

- `pfConvertImage` - Convert an image for to the binary format used by the **Analog Pocket** for its cores and platform lists.

- `pfReverseBitstream` - Converts an `rbf` bitstream file into an `rbf_r` reversed bitstream.

- `pfCloneCoreTemplate` - Clone the core dev template from Github.

- `pfQuartusEdit` - Edit Quartus project files.

You can use the `--help` argument to get some usage info for each command.

### License

**pfFPGATools** is distributed under the terms of the [GPLv3.0](https://spdx.org/licenses/GPL-3.0-or-later.html) or later license.
