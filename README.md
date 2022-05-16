# stlink_firmware
Restore your stlink after mcu replacement

Pinout of internal swd connector of st-link:
![pinout_stlink](https://user-images.githubusercontent.com/69225471/168513126-b19c756d-a91e-48cb-9540-7b63668a1dbb.png)

Wire your working programmer to the broken stlink, according the pinout above.
Then, using stlink flash utility upload firmware, that you can find in this repo.

After all you can update firmware of your newly restored stlink with a new one from stm servers or, also, make it a jlink
