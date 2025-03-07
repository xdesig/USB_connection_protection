# USB connection protection  V 001

This circuit is responsible for the protection against excessive consumption by resettable fuse and protection against overvoltage. to protect each I / O pin from high voltages, from ESD for electronic equipment that can be connected via the USB bus.
Rugged diodes (TVS Diode Arrays (SPA® Diodes) littelfuse) can safely absorb repetitive strokes of ESD at the maximum level specified in the international standard IEC 61000-4-2 (Level 4, contact discharge of ± 8 kV) without performance degradation. Their very low load capacity also makes them ideal for protecting high speed signal pins such as HDMI, DVI, USB2.0 and IEEE 1394.

Protects both the computer and the peripheral. I designed this small circuit when an improper mount of a driver in a RAMPS, burned the USB of the Laptop :-(

Buy PCB in [PCBWAY]

Components: Electronics Lcsc

[USB Female]

[USB Male]

PTC Resettable fuse [SMD1206B050TF]

TVS Littelfuse [SP3003-02JTG]

![Render][RENDER]
![Real][Real]



## Author and license
* Author: [XDeSIG][TWI01]
* License: [Attribution-ShareAlike 4.0 International] [CCBY-SA4.0]

<!-- links -->

[CCBY-SA4.0]: http://creativecommons.org/licenses/by-sa/4.0/
[TWI01]: https://twitter.com/xdesig
[RENDER]: USB_Protect_A_34.png
[Real]: USB_Protect_A_Preta.jpg
[PCBWAY]: https://www.pcbway.com/project/shareproject/USB_connection_protection.html
[USB Female]: https://lcsc.com/product-detail/USB-Connectors_Jing-Extension-of-the-Electronic-Co-LCSC-USB-A-F900-14-1-Not-high-temperature_C2344.html
[USB Male]: https://lcsc.com/product-detail/USB-Connectors_Atype-USBMale-head-USB-05_C112454.html
[SMD1206B050TF]: https://lcsc.com/product-detail/Others_Brightking-Elec-TAIWAN-SMD1206B025TF_C269112.html
[SP3003-02JTG]: https://lcsc.com/product-detail/TVS_Littelfuse_SP3003-02JTG_SP3003-02JTG_C151302.html

