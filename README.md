Electronics-Tutorials
=====================

[![Issues](http://img.shields.io/github/issues/macmade/Electronics-Tutorials.svg?logo=github)](https://github.com/macmade/Electronics-Tutorials/issues)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg?logo=git)
![License](https://img.shields.io/badge/license-ohl-brightgreen.svg?logo=open-source-initiative)  
[![Contact](https://img.shields.io/badge/follow-@macmade-blue.svg?logo=twitter&style=social)](https://twitter.com/macmade)
[![Sponsor](https://img.shields.io/badge/sponsor-macmade-pink.svg?logo=github-sponsors&style=social)](https://github.com/sponsors/macmade)

### About

Various electronics test projects.

### Software

Schemas and PCB layouts are created with KiCad:  
http://www.kicad-pcb.org

#### Footprints Library

This project requires the [XS-Labs KiCad Library](https://github.com/macmade/XS-KiCad-Library) to be installed in KiCad.

### Projects

  - [Astable Multivibrator](#1)
  - [SR Latch](#2)
  - [NPN Logic Gates](#3)

<a name="1"></a>
Astable Multivibrator
---------------------

![3D](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/Astable-Multivibrator-3D.png)
![Top](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/Astable-Multivibrator-Top.png)
![Bottom](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/Astable-Multivibrator-Bottom.png)

### Bill Of Materials

| Manufacturer            | Part No.             | Details                                                                  | Quantity |
|-------------------------|----------------------|--------------------------------------------------------------------------|----------|
| ON Semiconductor        | [BC547BTF]           | Bipolar Transistors - BJT NPN 45V 100mA HFE/450                          | 2        |
| Vishay                  | [MAL214258109E3]     | Aluminium Electrolytic Capacitors - Radial Leaded 10uF 63V 20%           | 2        |
| VCC                     | [4302H1-12V]         | Standard LEDs - Red - 12V                                                | 2        |
| Vishay                  | [CCF071K00JKE36]     | Metal Film Resistors 1/4watt 1Kohms 5%                                   | 2        |
| Vishay                  | [CCF07100KJKE36]     | Metal Film Resistors 1/4watt 100Kohms 5%                                 | 2        |
| Wurth Elektronik        | [691214110002]       | Fixed Terminal Blocks WR-TBL 300VAC 10A 2P Horizontal                    | 1        |

[BC547BTF]: https://www.mouser.ch/ProductDetail/512-BC547BTF
[MAL214258109E3]: https://www.mouser.ch/ProductDetail/594-MAL203858109E3
[4302H1-12V]: https://www.mouser.ch/ProductDetail/606-4302H1-12V
[CCF071K00JKE36]: https://www.mouser.ch/ProductDetail/71-CCF071K00JKE36
[CCF07100KJKE36]: https://www.mouser.ch/ProductDetail/71-CCF07100KJKE36
[691214110002]: https://www.mouser.ch/ProductDetail/710-691214110002

<a name="2"></a>
SR Latch
--------

![3D](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/SR-Latch-3D.png)
![Top](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/SR-Latch-Top.png)
![Bottom](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/SR-Latch-Bottom.png)

### Bill Of Materials

| Manufacturer            | Part No.             | Details                                                                  | Quantity |
|-------------------------|----------------------|--------------------------------------------------------------------------|----------|
| ON Semiconductor        | [BC547BTF]           | Bipolar Transistors - BJT NPN 45V 100mA HFE/450                          | 4        |
| VCC                     | [4302H5-12V]         | Standard LEDs - Green - 12V                                              | 1        |
| VCC                     | [4302H1-12V]         | Standard LEDs - Red - 12V                                                | 1        |
| Vishay                  | [CCF07390RJKE36]     | Metal Film Resistors 1/4watt 390ohms 5%                                  | 2        |
| Vishay                  | [CCF071K00JKE36]     | Metal Film Resistors 1/4watt 1Kohms 5%                                   | 4        |
| Vishay                  | [CCF0710K0JKE36]     | Metal Film Resistors 1/4watt 10Kohms 5%                                  | 4        |
| Omron                   | [B3W-9010-R1R]       | Tactile Switches - Green                                                 | 1        |
| Omron                   | [B3W-9010-R1R]       | Tactile Switches - Red                                                   | 1        |
| Wurth Elektronik        | [691214110002]       | Fixed Terminal Blocks WR-TBL 300VAC 10A 2P Horizontal                    | 1        |

[BC547BTF]: https://www.mouser.ch/ProductDetail/512-BC547BTF
[4302H5-12V]: https://www.mouser.ch/ProductDetail/606-4302H5-12V
[4302H1-12V]: https://www.mouser.ch/ProductDetail/606-4302H1-12V
[CCF07390RJKE36]: https://www.mouser.ch/ProductDetail/71-CCF07390RJKE36
[CCF071K00JKE36]: https://www.mouser.ch/ProductDetail/71-CCF071K00JKE36
[CCF0710K0JKE36]: https://www.mouser.ch/ProductDetail/71-CCF0710K0JKE36
[B3W-9010-G1G]: https://www.mouser.ch/ProductDetail/653-B3W-9010-G1G
[B3W-9010-R1R]: https://www.mouser.ch/ProductDetail/653-B3W-9010-R1R
[691214110002]: https://www.mouser.ch/ProductDetail/710-691214110002

<a name="3"></a>
NPN Logic Gates
---------------

![3D](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/NPN-Gates-3D.png)
![Top](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/NPN-Gates-Top.png)
![Bottom](https://raw.githubusercontent.com/macmade/Electronics-Tutorials/master/Assets/NPN-Gates-Bottom.png)

| Manufacturer            | Part No.             | Details                                                                  | Quantity |
|-------------------------|----------------------|--------------------------------------------------------------------------|----------|
| ON Semiconductor        | [BC547BTF]           | Bipolar Transistors - BJT NPN 45V 100mA HFE/450                          | 24       |
| VCC                     | [4302H5-12V]         | Standard LEDs - Green - 12V                                              | 6        |
| VCC                     | [4302H1-12V]         | Standard LEDs - Red - 12V                                                | 4        |
| Vishay                  | [CCF07390RJKE36]     | Metal Film Resistors 1/4watt 390ohms 5%                                  | 10       |
| Vishay                  | [CCF071K00JKE36]     | Metal Film Resistors 1/4watt 1Kohms 5%                                   | 14       |
| Vishay                  | [CCF0710K0JKE36]     | Metal Film Resistors 1/4watt 10Kohms 5%                                  | 24       |
| NKK Switches            | [M2012SA1W03]        | Toggle Switches ON-ON PC SPDT                                            | 2        |
| Wurth Elektronik        | [691214110002]       | Fixed Terminal Blocks WR-TBL 300VAC 10A 2P Horizontal                    | 1        |

[BC547BTF]: https://www.mouser.ch/ProductDetail/512-BC547BTF
[4302H5-12V]: https://www.mouser.ch/ProductDetail/606-4302H5-12V
[4302H1-12V]: https://www.mouser.ch/ProductDetail/606-4302H1-12V
[CCF07390RJKE36]: https://www.mouser.ch/ProductDetail/71-CCF07390RJKE36
[CCF071K00JKE36]: https://www.mouser.ch/ProductDetail/71-CCF071K00JKE36
[CCF0710K0JKE36]: https://www.mouser.ch/ProductDetail/71-CCF0710K0JKE36
[M2012SA1W03]: https://www.mouser.ch/ProductDetail/633-M2012A03
[691214110002]: https://www.mouser.ch/ProductDetail/710-691214110002

License
-------

All project files are released under the terms of the CERN Open Hardware License - CERN OHL v.1.2.

Repository Infos
----------------

    Owner:          Jean-David Gadina - XS-Labs
    Web:            www.xs-labs.com
    Blog:           www.noxeos.com
    Twitter:        @macmade
    GitHub:         github.com/macmade
    LinkedIn:       ch.linkedin.com/in/macmade/
    StackOverflow:  stackoverflow.com/users/182676/macmade
