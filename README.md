# Lua-LogX

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Lua-LogX** is simple library for calculating logarithms of any base in Lua.

## Content

- [Content](#content)
- [Prerequisites](#prerequisites)
  - [Windows](#windows)
  - [Linux](#linux)
    - [APT](#apt)
    - [Pacman](#pacman)
  - [MacOS](#macos)
- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
  - [Methods](#methods)
- [Authors](#authors)
- [Contact](#contact)
- [License](#license)

## Prerequisites

### Windows

Install Lua: https://sourceforge.net/projects/luabinaries/files/5.3.5/Tools%20Executables/lua-5.3.5_Win32_bin.zip/download

### Linux

#### APT

```
sudo apt update && sudo apt upgrade -y
sudo apt install lua5.3 -y
```

#### Pacman

```
sudo pacman -Syu --noconfirm
sudo pacman -S lua --noconfirm
```

### MacOS

```
brew update && brew upgrade
brew install lua
```

## Installation

Clone this repository:

`git clone "https://github.com/DeBos99/lua-logx.git"`

## Usage

Move the file **logx.lua** to your project directory and include it:

`require 'logx'`

## Documentation

### Methods

| Method         | Description                                |
| :---           | :---                                       |
| math.log2(n)   | Returns the base **2** logarithm of **n**. |
| math.logx(n,b) | Returns the base **b** logarithm of **n**. |

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos99](https://github.com/DeBos99)

## Contact

Discord: DeBos#3292

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
