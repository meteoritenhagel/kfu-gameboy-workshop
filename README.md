# glt26-gameboy-workshop
Resources for the workshop "Hands-On Introduction to Game Boy Programming" at the University of Graz.

This tutorial and the primary game mechanic of the rhythm input are inspired by my game
[Tyro Shaman](https://github.com/meteoritenhagel/TyroShaman) which I have programmed in 2025.

## License
Except otherwise noted in section [Credits](#credits):
* All code is licensed under the [MIT License](https://mit-license.org/).
* All assets are under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/). This especially applies to the
  presentation slides:
  * `gameboy-hands-on-DE.fodp`
  * `gameboy-hands-on-DE.pdf`
  * `gameboy-hands-on-EN.fodp`
  * `gameboy-hands-on-EN.pdf`
 
## Requirements
* [RGBDS v1.0.1 (MIT License)](https://github.com/gbdev/rgbds)
* [Gearboy 3.7.5 (GPL-3.0)](https://github.com/drhelius/Gearboy/)
* [GNU make (GPL-3.0)](https://www.gnu.org/software/make/)
* Any text editor, but I recommend [VSCodium (MIT License)](https://vscodium.com/) with the
  [RGBDS Extension (MIT License)](https://github.com/DonaldHays/rgbds-vscode).

## Credits
* Public Domain music library [hUGEDriver](https://github.com/SuperDisk/hUGEDriver) by
  [Nick Faro](https://github.com/SuperDisk). Files:
  * `./raw_resources/hUGEDriver/hUGE.inc` resp. `./project/include/hUGE.inc`
  * `./raw_resources/hUGEDriver/hUGE_note_table.inc` resp. `./project/include/hUGE_note_table.inc`
  * `./raw_resources/hUGEDriver/hUGEDriver.asm` resp. `./project/src/hUGEDriver.asm`
* The [Public Pixel](https://santiagocrespo.itch.io/public-pixel-for-gbs) adapted by
  [Santiago Crespo](https://itch.io/profile/santiagocrespo) and licensed under CC0. Files:
  * `./raw_resources/images/font.png` resp. `./project/res/font.png`
* The logo of the University of Graz belongs to the University of Graz. The title graphics file is partially derived
  from this logo:
  * `./raw_resources/images/title.png` resp. `./res/title.png`

