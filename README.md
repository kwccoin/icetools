# IceTools

Open Source FPGA toolkit built around [IceStorm](http://www.clifford.at/icestorm/) and [Yosys](http://www.clifford.at/yosys/) by [Clifford Wolf](http://www.clifford.at/).

## Run with Docker

```
docker run dimdm/icetools icepack -h
```

## Install locally (Debian || OS X)

```
./icetools.sh
```

## Toolchain

| Component                                           | Function      | License                                            |
|-----------------------------------------------------|---------------|----------------------------------------------------|
| [Yosys](http://www.clifford.at/yosys/)              | Synthesis     | [ISC](https://opensource.org/licenses/ISC)         |
| [Icarus Verilog](http://iverilog.icarus.com/)       | Simulation    | [GPL-2.0](https://opensource.org/licenses/GPL-2.0) |
| [Arachne-pnr](https://github.com/cseed/arachne-pnr) | Place & Route | [MIT](https://opensource.org/licenses/MIT)         |
| [IceStorm](http://www.clifford.at/icestorm/)        | Bitstream     | [ISC](https://opensource.org/licenses/ISC)         |

## Supported FPGAs

iCE40 LP/HX 1K/4K/8K

## Supported Devkits

- [icoBoard](https://shop.trenz-electronic.de/en/TE0887-02M-icoBoard-Version-1.1-with-8-MBit-SRAM)
- [iCEstick](http://www.latticesemi.com/icestick)
- [iCE40-HX8K Breakout Board](http://www.latticesemi.com/Products/DevelopmentBoardsAndKits/iCE40HX8KBreakoutBoard.aspx)
