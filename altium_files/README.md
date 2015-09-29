# altium_dump

# Making a part

- make *PCB Library* with pin pads, thermal pads, and include step model or mechanical extrusion, include outline and pin 1 designator, **do not use fills for thermal pads, use rectangular pin pads**
- make *Schematic Library* pins, draw box around pins, label pins, include thermal pad as a pin
- make *Schematic Sheet*, make net labels on important pins

# Part list

Part                                      | PCB Library | Schematic Library | Schematic Sheet | Verified?
-----  | ------      | ------       | ------- | -------
Hirose ZX62-B-5PA(11) (micro-USB)        | Yes (Fix pads)          | Yes                | Yes              | No
Texas Instruments TPS799 (SOT-5)          | Yes          | No                | No              | No
Texas Instruments CC110L (20-QFN)         | No        | Yes               | Yes             | No
Freescale FXAS21002C (24-QFN)             | Yes         | Yes               | Yes             | Yes
Silicon Labs CP2102                       | Yes       | Yes                | Yes              | Yes (update schdoc from schlib when working)
Texas Instruments TPS54531 (8SO PowerPad) | Yes         | Yes               | Yes             | Yes (need 3.3V version)
Samtec MUSB-05-F-B-SM-A (mini-USB)        | Yes        | Yes              | Yes              | Yes
Texas Instruments MSP430G2553 (28-TSSOP)  | Yes         | Yes                | Yes            | Yes