# Supported Systems

This is a list of supported systems and the emulators/cores to run them, it will be updated regularly.

Note that because of lack of time, not all of these systems have been thoroughly tested, help is always appreciated if you want to test them and report back!

Every system needs to have the correct folder structure inside the base path (the base ROM path is `/storage/roms`), for example Super Nintendo needs ROMS inside `/storage/roms/snes`.
This path is actually a second partition on your SD card, for more information on how to add your games please refer to this article: [Adding Games](Getting-to-Know-351ELEC#adding-games)

You will also find the correct extensions, almost all cores support .zip and .7z files as well as those listed.

## Fully Playable Systems

The **bold** one is the default one.

|&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;System&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;|&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;Core/Emu&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;|ROM Path|Extension| 
|---|---|---|---|
|AMIGA|**puae**<br />amiberry<br />uae4arm|amiga|.zip .uae .adf .dms .fdi .ipf .adz .lha .hdf .hdz|
|AMIGA CD32|**puae**<br />uae4arm|amigacd32|.iso .cue .chd .lha|
|[AMSTRAD CPC](System-Amstrad-CPC)|**crocods**<br />cap32|amstradcpc|.dsk .sna [crocods: .kcr]<br/>[cap32: .tap .cdt .voc .m3u .zip .7z]|
|[ARCADE](Arcade)|**mame2003_plus**<br />mame2000<br />mame2010<br />mame2015<br />mame<br />fbneo<br />fbalpha2012<br />fbalpha2019<br />AdvanceMame|arcade|.zip .7z|
|ATARI 800|**atari800**|atari800|.rom .xfd .atr .atx .cdm .cas .car .bin .a52 .xex .zip .7z|
|ATARI 2600|**stella-2014**<br />stella|atari2600|.a26 .bin .zip .7z|
|ATARI 5200|**atari800**|atari5200|.rom .xfd .atr .atx .cdm .cas .car .bin .a52 .xex .zip .7z|
|ATARI 7800|**prosystem**|atari7800|.a78 .bin .zip .7z|
|ATARI LYNX|**handy**<br />beetle_lynx|atarilynx|.lnx .o .zip .7z|
|[ATARI ST](System-Atari-ST)|**hatari**<br />HATARISA|atarist|.st .msa .stx .dim .ipf .m3u .zip .7z|
|[AQUAPLUS P/ECE](System-Aquaplus-Piece)|**piemu**|piece|.pex .pfi|
|SAMMY<br />ATOMISWAVE|**flycast**|atomiswave|.lst .bin .dat .zip .7z|
|[BANDAI<br />WONDERSWAN](System-Bandai-Wonderswan)|**beetle_wswan**|wonderswan|.ws .zip .7z|
|[BANDAI<br />WONDERSWAN COLOR](System-Bandai-Wonderswan)|**beetle_wswan**|wonderswancolor|.wsc .zip .7z|
|FAIRCHILD<br />CHANNEL F|**fairchaf**|channelf|.bin .chf .zip .7z|
|COLECOVISION|**bluemsx**<br />gearcoleco<br />smsplus|coleco|.bin .col .rom .zip .7z|
|COMMODORE 16<br />(PLUS/4)|**vice_xplus4**|c16|.d(64, 71, 80, 81, 82, 6z, 7z, 8z) .g(64, 41, 6z, 4z) .x64 .t64 .tap .prg .p00 .crt .bin .x6z .cmd .m3u .vsf .nib .nbz|
|COMMODORE 64|**vice_x64**|c64|.d(64, 71, 80, 81, 82, 6z, 7z, 8z) .g(64, 41, 6z, 4z) .x64 .t64 .tap .prg .p00 .crt .bin .x6z .cmd .m3u .vsf .nib .nbz|
|COMMODORE 128|**vice_x128**|c128|.d(64, 71, 80, 81, 82, 6z, 7z, 8z) .g(64, 41, 6z, 4z) .x64 .t64 .tap .prg .p00 .crt .bin .x6z .cmd .m3u .vsf .nib .nbz|
|COMMODORE VIC-20|**vice_xvic**|vic20|.20 .40 .60 .a0 .b0 .d(64, 71, 80, 81, 82, 6z, 7z, 8z) .g(64, 41, 6z, 4z) .x64 .t64 .tap .prg .p00 .crt .bin .gz .x6z .cmd .m3u .vsf .nib .nbz|
|[LASERDISC](System-Laserdisc)|**hypseus-singe**|laserdisc|.daphne or .ld (folder extension)|
|[FINALBURN NEO](System-FBNeo)|**fbneo**<br />mame2003_plus<br />fbalpha2012<br />fbalpha2019<br />mame2010<br />mame2015<br />mame|fbneo|.zip .7z|
|MATTEL<br />INTELLIVISION|**freeintv**|intellivision|.int .bin .rom .zip .7z|
|[MAME](System-MAME)|**mame2003_plus**<br />AdvanceMame<br />mame2000<br />mame2010<br />mame2015<br />mame<br />fbneo<br />fbalpha2012<br />fbalpha2019|mame|.zip .7z|
|MSX|**bluemsx**<br />fmsx|msx| .dsk .mx1 .mx2 .rom .zip .7z .m3u|
|MSX2|**bluemsx**<br />fmsx|msx2|.dsk .mx1 .mx2 .rom .zip .7z .m3u|
|[NEC<br />PC 8800](System-PC-88)|**quasi88**|pc88|.d88 .m3u|
|[NEC<br />PC 9800](System-PC-98)|**np2kai**<br />nekop2|pc98|.d98 .zip .98d .fdi .fdd .2hd .tfd .d88 .88d .hdm .xdf .dup .hdi .thd .nhd .hdd .hdn|
|NEC<br />PC ENGINE|**beetle_pce_fast**<br />beetle_supergrafx|pcengine|.pce .bin .zip .7z|
|NEC<br />PC ENGINE CD|**beetle_pce_fast**<br />beetle_supergrafx|pcenginecd|.cue .ccd .chd .toc .m3u|
|NEC<br />SUPERGRAFX|**beetle_supergrafx**|sgfx|.pce .sgx .cue .ccd .chd .zip .7z|
|NEC<br />TURBOGRAFX 16|**beetle_pce_fast**<br />beetle_supergrafx|tg16|.pce .bin .zip .7z|
|NEC<br />TURBOGRAFX CD|**beetle_pce_fast**<br />beetle_supergrafx|tg16cd|.cue .ccd .chd .toc .m3u|
|NINTENDO<br />ENTERTAINMENT SYSTEM|**nestopia**<br />fceumm<br />quicknes|nes|.nes .unif .unf .zip .7z|
|NINTENDO<br />FAMICOM|**nestopia**<br />fceumm<br />quicknes|famicom|.nes .unif .unf .zip .7z|
|NINTENDO<br />FAMICOM DISK SYSTEM|**nestopia**<br />fceumm<br />quicknes|fds|.fds .zip .7z|
|NINTENDO<br />GAME BOY|**gambatte**<br />sameboy<br />gearboy<br />tgbdual<br />mgba<br />vbam|gb|.gb .gbc .zip .7z|
|[NINTENDO<br />GAME BOY ADVANCE](System-Game-Boy-Advance)|**mgba**<br />beetle_gba<br />gpsp<br />vbam<br />vba_next|gba|.gba .zip .7z|
|NINTENDO<br />GAME BOY COLOR|**gambatte**<br />sameboy<br />gearboy<br />tgbdual<br />mgba<br />vbam|gbc|.gbc .gb .zip .7z|
|NINTENDO<br />GAME & WATCH|**gw**|gameandwatch|.mgw .zip .7z|
|NINTENDO<br />POKÉMON MINI|**pokemini**|pokemini|.min .zip .7z|
|[NINTENDO<br />SUPER NINTENDO](System-Super-Nintendo-Entertainment-System)|**snes9x**<br />snes9x2002<br />snes9x2005_plus<br />snes9x2010<br />beetle_supafaust|snes|.smc .sfc .swc .fig .zip .7z|
|[NINTENDO<br />SUPER FAMICOM](System-Super-Nintendo-Entertainment-System)|**snes9x**<br />snes9x2002<br />snes9x2005_plus<br />snes9x2010<br />beetle_supafaust|sfc|.smc .sfc .swc .fig .zip .7z|
|[NINTENDO<br />SUPER NINTENDO MSU-1](System-Super-Nintendo-Entertainment-System)|**snes9x**<br />beetle_supafaust|snesmsu1|.smc .fig .sfc .swc .zip .7z|
|[NINTENDO<br />SATELLAVIEW](System-Super-Nintendo-Entertainment-System#satellaview-bs-x)|**snes9x**<br />snes9x2002<br />snes9x2005_plus<br />snes9x2010|satellaview|.smc .sfc .swc .fig .bs .bsx .zip .7z|
|[BANDAI<br />SUFAMI TURBO](System-Super-Nintendo-Entertainment-System#sufami-turbo)|**snes9x**|sufami|.st .zip .7z|
|[NINTENDO<br />VIRTUAL BOY](System-Virtual-Boy)|**beetle_vb**|virtualboy|.vb .zip .7z|
|[MAGNAVOX<br />ODYSSEY²](System-Magnavox-Odyssey2)|**o2em**|odyssey|.bin .zip .7z|
|[PHILIPS<br />VIDEOPAC](System-Magnavox-Odyssey2)|**o2em**|videopac|.bin .zip .7z|
|[PC (DOS x86)](System-MS-DOS)|**dosbox_pure**<br />dosbox_svn|pc|.com .bat .exe .dosz, disk images (iso, cue, img, ima, vhd) can be put into the .dosz|
|[PICO-8](System-PICO-8)|**pico8**|pico-8|.png .p8|
|[SONY<br />PLAYSTATION](System-Sony-PlayStation)|**pcsx_rearmed**<br />duckstation<br />swanstation|psx|.bin .cue .img .pbp .mdf .toc .cbn .m3u .ccd .chd .iso|
|SEGA<br />SG-1000|**gearsystem**<br />genesis_plus_gx<br />picodrive|sg-1000|.bin .sg .zip .7z|
|SEGA<br />SC-3000|**bluemsx**|sc-3000|.sg .bin .zip .7z|
|SEGA<br />GAMEGEAR|**gearsystem**<br />genesis_plus_gx<br />picodrive<br />smsplus|gamegear|.gg .bin .zip .7z|
|SEGA<br />MASTER SYSTEM|**gearsystem**<br />genesis_plus_gx<br />picodrive<br />smsplus|mastersystem|.sms .bin .zip .7z|
|SEGA<br />GENESIS|**genesis_plus_gx**<br />genesis_plus_gx_wide<br />picodrive|genesis|.gen .md .sg .smd .bin .zip .7z|
|SEGA<br />MEGA DRIVE|**genesis_plus_gx**<br />genesis_plus_gx_wide<br />picodrive|megadrive<br />megadrive-japan|.gen .bin .md .sg .smd .zip .7z|
|SEGA 32X|**picodrive**|sega32x|.32x .bin .md .smd .zip .7z|
|SEGA CD|**genesis_plus_gx**<br />picodrive|segacd|.chd .cue .iso .m3u8|
|SEGA MEGA CD|**genesis_plus_gx**<br />picodrive|megacd|.chd .cue .iso .m3u|
|SEGA<br />SATURN|**yabasanshiroSA**|saturn|.cue .iso .chd|
|SNK<br />NEO-GEO|**fbneo**<br />mame2003_plus<br />fbalpha2012<br />fbalpha2019<br />mame2010<br />mame2015<br />mame|neogeo|.7z .zip|
|SNK<br />NEO-GEO CD|**neocd**<br />fbneo|neocd|.chd .cue .iso|
|SNK<br />NEO-GEO POCKET|**beetle_ngp**<br />race|ngp|.ngp .ngc .zip .7z|
|SNK<br />NEO-GEO POCKET COLOR|**beetle_ngp**<br />race|ngpc|.ngc .zip .7z|
|WATARA<br />SUPERVISION|**potator**|supervision|.sv .zip .7z|
|WELBACK HOLDINGS<br />MEGADUCK|**sameduck**|megaduck|.bin .zip .7z|
|TIC-80|**tic80**|tic-80|.tic|
|UZEBOX|**uzem**|uzebox|.uze|
|GCE<br />VECTREX|**vecx**|vectrex|.bin .gam .vec .zip .7z|
|SHARP<br />X1|**x1**|x1|.dx1 .2d .2hd .tfd .d88 .88d .hdm .xdf .dup .tap .cmd .zip .7z|
|[SHARP<br />X68000](System-X68000)|**px68k**|x68000|.dim .img .d88 .88d .hdm .dup .2hd .xdf .hdf .cmd .m3u .zip .7z|
|SINCLAIR<br />ZX81|**81**|zx81|.tzx .p .zip .7z|
|SINCLAIR<br />ZX SPECTRUM|**fuse**|zxspectrum|.tzx .tap .z80 .rzx .scl .trd .dsk .zip .7z|

You can also view this (WIP) spreadsheet with information for each core, as well as if it requires bios or not: [https://docs.google.com/spreadsheets/d/1T962LmL0ci7Hs88TZT3iMtqdvzug4tL3ayTb0uoxijQ](https://docs.google.com/spreadsheets/d/1T962LmL0ci7Hs88TZT3iMtqdvzug4tL3ayTb0uoxijQ)

Please Note that MAME and FBA screen ratio are not optimized as they should have been optimized on game basis (some are 4:3, some alre 3:2 some are vertical), so we decided to leave the default options.

## Low Performance Systems
These platforms, due to hardware limitation, are included and worked on, but will never work perfectly.
Some games/systems work almost perfectly, some others they may never work smoothly.

|System|Status|Core/Emu|ROM Path|Extension| 
|---|---|---|---|---|
|3DO|Only low performance|**opera**|3do|.iso .cue .bin .chd|
|J2ME|Quite smooth playing|**freej2me**|j2me|.jar|
|NEC<br />PC-FX|Only low performance|**beetle_pcfx**|pcfx|.chd .cue .ccd .toc|
|[NINTENDO N64](System-N64)|Some games run well, others are unplayable|mupen64plus<br />mupen64plus_next<br />**parallel_n64**<br />parallel_n64_gln64<br />mupen64plussa_glide64mk2<br />mupen64plussa_rice|n64|.z64 .n64 .v64 .zip .7z|
|NINTENDO DS|2D Games almost fully playable|**drastic**|nds|.nds .zip|
|SEGA<br />NAOMI|Some games run well, others are unplayable|**flycast**|naomi|.lst .bin .dat .zip .7z|
|SEGA DREAMCAST|Some games run well, others are unplayable|**flycast**|dreamcast|.cdi .gdi .chd .m3u|
|[SONY PSP](System-Sony-PlayStation-Portable)|Many games run well, especially with frameskip. Some games are unplayable |**PPSSPPSDL**<br />ppsspp|psp|.cso .iso .pbp|
|[SONY<br />PSP MINIS](System-Sony-PlayStation-Portable)|Most games are less demanding than PSP, and run well, though a few may run badly|**PPSSPPSDL**<br />ppsspp| pspminis |.iso .cso .pbp|

\*Games can also run internally from the gamedata/ppsspp/psp/GAMEDATA folder, this also allows DLC and custom textures to be added.

## Game Engines

|&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;System&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;|&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;Core/Emu&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;|ROM Path|Extension| 
|---|---|---|---|
|[Build Engine](System-Build-Engine)|**raze**|build|[.build](System-Build-Engine#how-to-create-a-build-file)|
|[DOOM](System-Doom)|**gzdoom**<br />lzdoom<br />prboom|doom|[.doom](System-Doom#how-to-create-a-doom-file)|
|[EASYRPG](System-EasyRPG)|**easyrpg**|easyrpg|.zip .easyrpg .ldb|
|OPENBOR|**openbor**|openbor|.pak|
|[SCUMMVM](System-ScummVM)|**scummvmsa**<br />scummvm|scummvm/games|.sh .svm .scummvm|
|SOLARUS|**solarus**|solarus|.solarus|
|[WOLFENSTEIN 3D](System-Wolfenstein-3D)|**ecwolf**|ecwolf|[.ecwolf](System-Wolfenstein-3D#how-to-create-a-ecwolf-file)|

## Homebrew

| Port |  Core/Emu  | ROM Path  |  Extension | 
|---|---|---|---|
|HYDRA CASTLE LABYRINTH|hcl|
|PRINCE OF PERSIA|SDLPoP|
|TYRIAN|OpenTyrian|

## Collections

|&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;Platform&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;|&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;Core/Emu&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;&#x2800;|ROM Path|Extensions|
|---|---|---|---|
|NINTENDO<br />GAME BOY HACKS|**gambatte**<br />sameboy<br />mgba<br />tgbdual<br />gearboy<br />vbam|gbh|.gb .zip .7z|
|NINTENDO<br />GAME BOY COLOR HACKS|**gambatte**<br />sameboy<br />mgba<br />tgbdual<br />gearboy<br />vbam|gbch|.gbc .gb .zip .7z|
|NINTENDO<br />GAME BOY ADVANCE HACKS|**mgba**<br />gpsp<br />vbam<br />vba_next<br />beetle_gba|gbah|.gba .zip .7z|
|NINTENDO<br />ENTARTAINMENT SYSTEM HACKS|**nestopia**<br />fceumm<br />quicknes|nesh|.nes .unif .unf .zip .7z|
|NINTENDO<br />SUPER NINTENDO HACKS|**snes9x**<br />snes9x2010<br />snes9x2002<br />snes9x2005_plus<br />beetle_supafaust|snesh|.smc .sfc .swc .fig .zip .7z|
|SEGA<br />GAME GEAR HACKS|**gearsystem**<br />genesis_plus_gx<br />picodrive<br />smsplus|gamegearh|.gg .bin .zip .7z|
|SEGA<br />GENESIS HACKS|**genesis_plus_gx**<br />genesis_plus_gx_wide<br />picodrive|genh|.gen .md .sg .smd .bin .zip .7z|

***

# BIOS 
Some platforms need bios files, these should go in /storage/roms/bios.
You can check which bios you’re missing directly on your device by pressing START, Games Settings, Missing Bios.

## What Doesn't Run
* SONY PLAYSTATION 2
* SONY PLAYSTATION 3
* SONY PLAYSTATION 4
* NINTENDO GAMECUBE
* NINTENDO 3DS
* NINTENDO WII/U
* MICROSOFT XBOX (any)
* ATARI JAGUAR
* ANYTHING NEWER