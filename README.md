Forked from https://github.com/IoakeimSogiakas/dactyl_manuform_5x6-ZMK and heavily modified for my purpose.

This dactyl manuform build is based around my idea to create a semi modular hand wired build for a wireless dactyl
manuform with a dongle. Firmware is configured for nice!nano and clones in 3 controller configuration:

1. left keyboard
2. right keyboard
3. dongle

Built firmware has 4 files:
dactyl_dongle-nice_nano_v2-zmk.uf2
dactyl_left-nice_nano_v2-zmk.uf2
dactyl_right-nice_nano_v2-zmk.uf2
settings_reset-nice_nano_v2-zmk.uf2

Settings reset can be used in case of changing dongle controllers to remove all bluetooth pairings.
Recommended flashing procedure is to first flash settings reset on all components, then flash each of the
components while others are turned off. Finally power up the dongle first, followed by keyboard halves, and
make sure all works.

When changing the keymap in theory its enough to reflash the dongle only, but i prefer to reflash all the components.

BOM and full build instructions will be published soon!
