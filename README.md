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
  - [NPN Gates](#3)

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

[BC547BTF]: https://www.mouser.ch/ProductDetail/onsemi-Fairchild/BC547BTF?qs=GcrAnsq4Ss7FY6sMmzmP8w%3D%3D
[MAL214258109E3]: https://www.mouser.ch/ProductDetail/Vishay-BC-Components/MAL203858109E3?qs=G99oyVYclWWJ4E%2Fuyfur8w%3D%3D
[4302H1-12V]: https://www.mouser.ch/ProductDetail/VCC/4302H1-12V?qs=I7nE1oQSFs%252BsAaSQbADByg%3D%3D
[CCF071K00JKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF071K00JKE36?qs=NQWA6AwZmkMdaaeOGvuguw%3D%3D
[CCF07100KJKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF07100KJKE36?qs=2C0eY6jyEMg5anHdnDFVuA%3D%3D
[691214110002]: https://www.mouser.ch/ProductDetail/Wurth-Elektronik/691214110002?qs=7gQLVZk5cPmb9EqUyfv%252B2g%3D%3D

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
| VCC                     | [4302H1-12V]         | Standard LEDs - Red - 12V                                                | 2        |
| Vishay                  | [CCF07390RJKE36]     | Metal Film Resistors 1/4watt 390ohms 5%                                  | 2        |
| Vishay                  | [CCF071K00JKE36]     | Metal Film Resistors 1/4watt 1Kohms 5%                                   | 4        |
| Vishay                  | [CCF0710K0JKE36]     | Metal Film Resistors 1/4watt 10Kohms 5%                                  | 4        |
| Omron                   | [B3W-9010-R1R]       | Tactile Switches                                                         | 2        |
| Wurth Elektronik        | [691214110002]       | Fixed Terminal Blocks WR-TBL 300VAC 10A 2P Horizontal                    | 1        |

[BC547BTF]: https://www.mouser.ch/ProductDetail/onsemi-Fairchild/BC547BTF?qs=GcrAnsq4Ss7FY6sMmzmP8w%3D%3D
[4302H1-12V]: https://www.mouser.ch/ProductDetail/VCC/4302H1-12V?qs=I7nE1oQSFs%252BsAaSQbADByg%3D%3D
[CCF07390RJKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF07390RJKE36?qs=GXUZvAFNa0ohtCtagujS8g%3D%3D
[CCF071K00JKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF071K00JKE36?qs=NQWA6AwZmkMdaaeOGvuguw%3D%3D
[CCF0710K0JKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF0710K0JKE36?qs=NQWA6AwZmkNSbeldIV%252BliA%3D%3D
[B3W-9010-R1R]: https://www.mouser.ch/ProductDetail/Omron-Electronics/B3W-9010-R1R?qs=sR392Zi6y%2F%2Fb9yxo8dNKag%3D%3D
[691214110002]: https://www.mouser.ch/ProductDetail/Wurth-Elektronik/691214110002?qs=7gQLVZk5cPmb9EqUyfv%252B2g%3D%3D

<a name="3"></a>
NPN Gates
---------

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

[BC547BTF]: https://www.mouser.ch/ProductDetail/onsemi-Fairchild/BC547BTF?qs=GcrAnsq4Ss7FY6sMmzmP8w%3D%3D
[4302H5-12V]: https://www.mouser.ch/ProductDetail/VCC/4302H5-12V?qs=I7nE1oQSFs9Q1s%2F%252BOaNzdw%3D%3D
[4302H1-12V]: https://www.mouser.ch/ProductDetail/VCC/4302H1-12V?qs=I7nE1oQSFs%252BsAaSQbADByg%3D%3D
[CCF07390RJKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF07390RJKE36?qs=GXUZvAFNa0ohtCtagujS8g%3D%3D
[CCF071K00JKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF071K00JKE36?qs=NQWA6AwZmkMdaaeOGvuguw%3D%3D
[CCF0710K0JKE36]: https://www.mouser.ch/ProductDetail/Vishay-Dale/CCF0710K0JKE36?qs=NQWA6AwZmkNSbeldIV%252BliA%3D%3D
[M2012SA1W03]: https://www.mouser.ch/ProductDetail/NKK-Switches/M2012SA1W03?qs=7qTko1p7JkMWph6qTPDvKQ%3D%3D
[691214110002]: https://www.mouser.ch/ProductDetail/Wurth-Elektronik/691214110002?qs=7gQLVZk5cPmb9EqUyfv%252B2g%3D%3D

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
