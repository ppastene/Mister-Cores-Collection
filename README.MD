# Mister Core Collection
This is a Mister FPGA core list to be to disposition to anyone who wants to fetch cores for their setup.

## Why?
I know many devs uses github or other platforms to share their developed cores as well others don't so they have to be installed manually. Also I know the existance of [Mister Ongo Collection](https://github.com/OngoGablogian/MiSTer_Ongo) so, why another core repository? Well, I think one more repository will not hurt anyonme but the main reason is it bothers me the fragmentation on how the mister cores are developed and distributed. Open or closed source. Github or patreon. Basic or premuim features. Releasing the cores for free and being community driven or staying behind a paywall with sporadic releases. I know the open souce nature of the Mister FPGA project and anyone have their will to profit or how to distribute their creation, but still is a problem that it wont fix by adding one more line to the downloader.ini while everyone have their own rules of distribution. So I think a way to structure the availability of the Mister Cores and have more strict rules like in MAME could be a solution, but in the mean time consider this collection as a curated list of cores being organized by developer and with the availability to be in one place.

## Considerations
Despite being a public list of cores, I have the following considerations to allow a core being part of this list:
- This collection shares Mister FPGA cores being available to the public by their developers without restriction independent of the source (github, patreon, devs own website, internet archive, mister fpga forums/discord server, etc...).
- This collection is not a replacement to the update.sh and update_all.sh scripts, to other collections and dabatases, but an alternative to seek and structure the cores you wanna install. My suggestion is to use update_all.sh to get certain cores and use this to source other cores to keep your installed cores organized.
- Cores that aren't public to the people or are behind a paywall or authentication for whatever reason are not going be part of this collection.
- Since this repository fetchs automatically all of the cores available I cannot guarantee the following:
    - A core was developed with vibecode or assisted by AI, with the MAME codebase and/or by studying the hardware PCB.
    - A core have features like analog video output, savestates, pause, SNAC support, networking, etc....
    - The selection of one core if there are many coded by different developers and based on the same game and/or hardware.

## Installation
At the moment there is no database to add to the downloader.ini file like other repositories. The idea is to allow the user which cores wants to add to their mister setup, it could be all of the cores or a few from certain developer. So the best way to get this collection is to clone this repository with git clone or with the download zip option and add them manually to the SD.

## Organization
There are four main categories in Mister: _Arcade, _Computer, _Console and _Other (used mostly for hybrid cores). Considering the great amount of arcade cores, the _Arcade folder is the only category which offer the categorization of cores by the developer name while the rest all of the cores will be on the folder's root.

If there is a name matching between files they will be renamed adding the developer's name as a prefix. In the case of renaming the .brf files it also affect the brf tag inside their respective .mra file.

## Roms
This repository will not host and share any romset or bios either a file or url. But soon I will share a romset.txt file with a list of all of the romset required for this collection, just in case if you wanna have the roms and not search manually what are the required romset for each core.

## Resources
Here a list of resources like databases, documentation and repositories

- [MiSTer-devel](https://github.com/MiSTer-devel) Main MiSTer organization page and distribution of cores.
    - [Wiki](https://github.com/MiSTer-devel/Wiki_MiSTer/wiki): MiSTer wiki
    - [Forums](https://misterfpga.org/): MiSTer forums
    - [Discord](https://discord.com/invite/misterfpga): MiSTer discord server
- [Mister Ongo Collection](https://github.com/OngoGablogian/MiSTer_Ongo): Collection of MiSTer cores from many developers and sources
- [MiSTer-DB9](https://github.com/MiSTer-DB9): MiSTer organization in charge of host, modify and distribute cores with support for DB9 SNAC

## Credits & Acknowledgments
Thanks to the Mister FPGA team for their contribution to the Mister Project. Also thanks to everyone who contributed to the Mister FPGA either by developing cores or spreading words of the project.
