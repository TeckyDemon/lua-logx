# Lua-LogX

## Description

**Lua-LogX** is simple library for calculating logarithms of any base in Lua.

## Prerequisites

### Windows

Install Lua: https://sourceforge.net/projects/luabinaries/files/5.3.5/Tools%20Executables/lua-5.3.5_Win32_bin.zip/download

### Linux

```
$ sudo apt update && sudo apt upgrade -y
$ sudo apt install lua5.3 -y
```

### MacOS

```
$ brew update && brew upgrade
$ brew install lua
```

## Installation

Clone this repository:

`$ git clone "https://github.com/DeBos99/lua-logx.git"`

Move the file **logx.lua** to your project directory and include it:

`require 'logx'`

## Methods

| Method         | Description                               |
| :---           | :---                                      |
| math.log2(n)   | Returns the base **2** logarithm of **n** |
| math.logx(n,b) | Returns the base **b** logarithm of **n** |

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos99](https://github.com/DeBos99)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
