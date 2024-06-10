# Firmware

Firmware Update - June 2024

A few people reported their insert LED was always on.  The firmware files below resolve that; pick the version you would like:

- [Insert LED off](davek184_fc660c_vial_BgRgb44LEDs_InsertLED_Off.hex) *(there is NO insert LED and/or you always want it off; most people)*
- [Insert LED Num Lock](davek184_fc660c_vial_BgRgb44LEDs_InsertLED_NumLock.hex)
- [Insert LED Scroll Lock](davek184_fc660c_vial_BgRgb44LEDs_InsertLED_ScrollLock.hex)

New firmware has boot magic to enter boot loader mode **hold down Esc while powering on** (this doesn't apply to the old firmware so you may need to hit the reset button on the controller)

*(Alternately, compile your own firmware. Desired source files are included in the repo)*

Note: If you don not use RBG underglow official VIA firmware can be used [FC660C](https://www.caniusevia.com/docs/download_firmware)
