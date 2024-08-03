﻿# Index of fonts
Ordinary Unicode fonts for use with bob's game and non-OpenType-savvy programs (e.g. Microsoft Word 2007). The fonts are available under the terms of the WTFPL license.
* My own version of [the font with the same name as the game](https://github.com/bobsgamed/okClassic/raw/main/nDmenu/data/bobsgame.ttf) with revised glyphs and support for more glyphs like vowels with umlauts. **P.S.** The original font in the game itself is from the Hamtaro/Mario & Luigi RPG GBA games with modified glyphs and is a web font generated by Font Squirrel's generator according to the US English naming field with unknown ID 200.
* **BobsGame Big** – Based on the font used in Mario & Luigi RPG games for the Nintendo DS. **P.S.** This font was created in 2012-12-20 and was hosted in a subfolder in the Bob Corporation website.
* **BobsGame Mono** – Based on the “System VIO” font from OS/2 with revised glyphs and support for more glyphs. **P.S.** The game author uploaded it to the Bob Corporation website in December 2015 and moved it to a subfolder.
* **BobsGame nD** – Based on the font in third/fourth generation Pokémon games with revised glyphs and support for more glyphs. The numbers were taken from *Castlevania: Aria of Sorrow*. Windows Vista and newer fakes the font preview as Japanese (21 Kanji letters are included in this font).
* **Pixel Sans** – Based on the font used in many Nintendo 3DS, Game Boy Advance and Nintendo DS games. This font was created in 2015 under the name of **DS Sans**. Windows Vista and newer fakes the font preview as Chinese (the ideographs are included in Pixel Sans Fallback).
* **Pixel Sans Fallback** – For use with Japanese and Korean. `fc-scan` does not show Japanese or Korean in the language fields despite these languages are supported.
* **Pixel Sans Terminal** – An alternate version with lowercase letters changed to match the font used in [UniPad](http://www.unipad.org/) (Sharmahd Computing, 1997-2006).
* **Pixel Sans Textbook** – Based on the font used in Western versions of Pokémon Black & White with revised glyphs and support for more glyphs. This font has the same character set as the non-Fallback version of Pixel Sans.

## Tools used
* **CrystalTile2** – Freeware Licensed Software
* **High-Logic FontCreator 5.6** – Shareware Licensed Software
* **Microsoft Paintbrush, Windows XP version** – Software distributed with Windows
* **NFTREdit** – Freeware Licensed Software
* **Tinke** – GNU GPL Licensed Open-Source Software

## Installation Instructions
http://bobsgame.wikia.com/wiki/Category:Fonts

**Note:** The category about the fonts in this wiki has licensing information for other fonts.

## NFTR version
The NFTR includes partial coverage of code page 1252 (the missing characters are the non-breaking space (160/A0h), florin (130/83h) and small tilde). Use [Tinke](https://github.com/pleonex/tinke) to replace the font file.
1. Get a copy of the More English Training European game cartridge on sellers and dump the ROM file or download the ROM from ROM sites (e.g. ROM Hustler, Emuparadise, etc.) and open it. **NB:** ROM sites and links to pre-patched ROMs are not tolerated by GBAtemp.
>>>>>>> a631929 (Added florin character code)
2. Go to `common/fonts/data` and you'll see a file called **European_LC12.NFTR**.
3. Press **Change file** to replace the file.
4. Press **Save ROM** to save the ROM in a new name.
5. Play the game in flash cards (e.g. TTDS) or emulators (e.g. NO$GBA, DeSmuME, etc. etc. etc.).

**Note:** Don't try this in the Japanese or Korean versions of the game!
