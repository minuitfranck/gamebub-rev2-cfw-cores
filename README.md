# Game Bub rev2: firmware and cores

A rev2 (vertical) [Game Bub](https://github.com/elipsitz/gamebub) running custom firmware and cores loaded from
the SD card, as of 28 September 2026. The pictures are the handheld's own screenshots, enlarged three times.
Not affiliated with, endorsed by or supported by Eli Lipsitz or the Game Bub project.

<p align="center">
  <img src="images/gamebub-rev2-home.svg" width="36%" alt="A rev2 Game Bub showing its main menu">
  <img src="images/gamebub-rev2-comix-zone.svg" width="36%" alt="A rev2 Game Bub playing Comix Zone">
</p>

## On the device

| Part | Version | Battery saves | Save states |
|---|---|---|---|
| Firmware | r2-17u, a fork of Game Bub firmware 1.1.0-beta2 | | |
| Game Boy / Game Boy Color, built in | v1.0.2, rev2 build | yes | no |
| Game Boy Advance, built in | v1.0.2, rev2 build | yes | no |
| Game Boy / Game Boy Color, MiSTer core | r2.11 | yes | yes |
| Game Boy Advance, MiSTer core | r2.15 | yes | yes |
| Super Nintendo | 0.0.3 r2.6 | yes | yes |
| NES / Famicom | r2.10 | yes | yes |
| PC Engine / TurboGrafx-16 | r2.12 | yes | yes |
| Mega Drive / Genesis | r2.19 | yes | yes |
| Neo Geo Pocket Color | r2.9 | yes | yes |
| WonderSwan / WonderSwan Color | r2.7 | yes | yes |
| Super Game Boy | r2.8 | yes | yes |

Save state: Home + R. Load state: Home + L. Screenshot: Home + Select. Volume and brightness: Home + a direction.
2x speed on the MiSTer Game Boy and Game Boy Advance cores: Home + Start. The clock is set from a PC over USB.

Beyond Game Bub firmware 1.1.0-beta2: cores loaded from the SD card, each with a settings page; hotkeys for save
states, 2x speed and screenshots, each of which can be switched off; rumble levels; auto power off; a GBA BIOS
choice; checked save reads; the same loudness on every core; a console over USB for tests and for setting the
clock from a PC; four menu themes: Light Game Bub, Dark Game Bub, minuitfranck dark and minuitfranck light. The
minuitfranck themes take the colors of [minuitfranck.com](https://minuitfranck.com): lavender for the cursor,
green while a value is being edited, amber on the number under change, and the site's banner on the main menu.

## Menus

The menus in the theme in use, minuitfranck light.

|  |  |  |
|---|---|---|
| <img src="images/menu-main.png" width="100%" alt="Main menu"> | <img src="images/menu-cores.png" width="100%" alt="Cores"> | <img src="images/menu-core-detail.png" width="100%" alt="A core's page"> |
| Main menu | Cores | A core's page |
| <img src="images/menu-game-list.png" width="100%" alt="A core's game list"> | <img src="images/menu-home.png" width="100%" alt="Home menu over a game"> | <img src="images/menu-core-panel-gba-mister.png" width="100%" alt="A core's settings over a game (Game Boy Advance, MiSTer core)"> |
| A core's game list | Home menu over a game | A core's settings over a game (Game Boy Advance, MiSTer core) |
| <img src="images/menu-core-panel-mega-drive.png" width="100%" alt="A core's settings over a game (Mega Drive / Genesis)"> | <img src="images/menu-tools.png" width="100%" alt="Tools"> | <img src="images/menu-settings.png" width="100%" alt="Settings"> |
| A core's settings over a game (Mega Drive / Genesis) | Tools | Settings |
| <img src="images/menu-settings-general.png" width="100%" alt="Settings > General"> | <img src="images/menu-settings-general-theme-editing.png" width="100%" alt="Settings > General, choosing the theme"> | <img src="images/menu-settings-hotkeys.png" width="100%" alt="Settings > Hotkeys"> |
| Settings > General | Settings > General, choosing the theme | Settings > Hotkeys |
| <img src="images/menu-settings-date-time.png" width="100%" alt="Settings > Date & Time"> | <img src="images/menu-settings-date-time-editing.png" width="100%" alt="Settings > Date & Time, changing the day"> | <img src="images/menu-settings-cores-builtin.png" width="100%" alt="Settings > Cores: Built-in"> |
| Settings > Date & Time | Settings > Date & Time, changing the day | Settings > Cores: Built-in |
| <img src="images/menu-settings-cores-sd.png" width="100%" alt="Settings > Cores: SD Card"> | <img src="images/menu-settings-core-gb-builtin.png" width="100%" alt="Core: GB / GBC (Game Bub)"> | <img src="images/menu-settings-core-gba-builtin.png" width="100%" alt="Core: GBA (Game Bub)"> |
| Settings > Cores: SD Card | Core: GB / GBC (Game Bub) | Core: GBA (Game Bub) |
| <img src="images/menu-settings-core-gb-mister.png" width="100%" alt="Core: GB / GBC (MiSTer)"> | <img src="images/menu-settings-core-mega-drive.png" width="100%" alt="Core: Mega Drive / Genesis"> | <img src="images/menu-about.png" width="100%" alt="About"> |
| Core: GB / GBC (MiSTer) | Core: Mega Drive / Genesis | About |

## Themes

Settings > General > Theme. The main menu in each of the four.

|  |  |  |  |
|---|---|---|---|
| <img src="images/menu-theme-light-game-bub.png" width="100%" alt="Light Game Bub"> | <img src="images/menu-theme-dark-game-bub.png" width="100%" alt="Dark Game Bub"> | <img src="images/menu-theme-minuitfranck-dark.png" width="100%" alt="minuitfranck dark"> | <img src="images/menu-theme-minuitfranck-light.png" width="100%" alt="minuitfranck light"> |
| Light Game Bub | Dark Game Bub | minuitfranck dark | minuitfranck light |

## Game Boy / Game Boy Color (built in)

|  |  |  |
|---|---|---|
| <img src="images/gb-pokemon-tcg-gb.png" width="100%" alt="Pokemon TCG GB"> | <img src="images/gb-bomberman.png" width="100%" alt="Bomberman GB"> | <img src="images/gb-tetris-rosy-retrospection.png" width="100%" alt="Tetris, Rosy Retrospection (color hack)"> |
| Pokemon TCG GB | Bomberman GB | Tetris, Rosy Retrospection (color hack) |

## Game Boy / Game Boy Color (MiSTer core)

|  |  |  |
|---|---|---|
| <img src="images/gbm-detective-conan.png" width="100%" alt="Detective Conan, border file"> | <img src="images/gbm-links-awakening-redux.png" width="100%" alt="Link's Awakening Redux, border file"> | <img src="images/gbm-pokemon-coral.png" width="100%" alt="Pokemon Coral (fan game)"> |
| Detective Conan, border file | Link's Awakening Redux, border file | Pokemon Coral (fan game) |

## Game Boy Advance (built in)

|  |  |  |
|---|---|---|
| <img src="images/gba-emibios-gyakuten-load.png" width="100%" alt="emibios, the open BIOS, loading Phoenix Wright: Ace Attorney, Trials and Tribulations"> | <img src="images/gba-ace-attorney-trials-and-tribulations.png" width="100%" alt="Phoenix Wright: Ace Attorney, Trials and Tribulations, the title that follows"> | <img src="images/gba-warioware-twisted.png" width="100%" alt="WarioWare: Twisted!"> |
| emibios, the open BIOS, loading Phoenix Wright: Ace Attorney, Trials and Tribulations | Phoenix Wright: Ace Attorney, Trials and Tribulations, the title that follows | WarioWare: Twisted! |
| <img src="images/gba-advance-wars.png" width="100%" alt="Advance Wars"> |  |  |
| Advance Wars |  |  |

## Game Boy Advance (MiSTer core)

|  |  |  |
|---|---|---|
| <img src="images/gbam-metal-slug-advance.png" width="100%" alt="Metal Slug Advance"> | <img src="images/gbam-f-zero-maximum-velocity.png" width="100%" alt="F-Zero: Maximum Velocity"> | <img src="images/gbam-kirby-amazing-mirror.png" width="100%" alt="Kirby & the Amazing Mirror"> |
| Metal Slug Advance | F-Zero: Maximum Velocity | Kirby & the Amazing Mirror |
| <img src="images/gbam-dokapon.png" width="100%" alt="Dokapon"> | <img src="images/gbam-ace-attorney-trials-and-tribulations.png" width="100%" alt="Phoenix Wright: Ace Attorney, Trials and Tribulations"> |  |
| Dokapon | Phoenix Wright: Ace Attorney, Trials and Tribulations |  |

## Super Nintendo

|  |  |  |
|---|---|---|
| <img src="images/snes-yoshis-island.png" width="100%" alt="Yoshi's Island"> | <img src="images/snes-super-mario-world.png" width="100%" alt="Super Mario World"> | <img src="images/snes-turtles-in-time.png" width="100%" alt="Turtles in Time"> |
| Yoshi's Island | Super Mario World | Turtles in Time |
| <img src="images/snes-mega-man-x2.png" width="100%" alt="Mega Man X2"> | <img src="images/snes-bs-zelda.png" width="100%" alt="BS Zelda: Ancient Stone Tablets"> | <img src="images/snes-bust-a-move.png" width="100%" alt="Bust-A-Move"> |
| Mega Man X2 | BS Zelda: Ancient Stone Tablets | Bust-A-Move |
| <img src="images/snes-parodius.png" width="100%" alt="Parodius"> |  |  |
| Parodius |  |  |

## NES / Famicom

|  |  |  |
|---|---|---|
| <img src="images/nes-kirbys-adventure.png" width="100%" alt="Kirby's Adventure"> | <img src="images/nes-light-from-within.png" width="100%" alt="Light From Within (homebrew)"> | <img src="images/nes-journey-into-the-unknown.png" width="100%" alt="A Journey Into The Unknown (homebrew)"> |
| Kirby's Adventure | Light From Within (homebrew) | A Journey Into The Unknown (homebrew) |

## PC Engine / TurboGrafx-16

|  |  |  |
|---|---|---|
| <img src="images/pce-neutopia.png" width="100%" alt="Neutopia"> | <img src="images/pce-street-fighter-2.png" width="100%" alt="Street Fighter II'"> | <img src="images/pce-bomberman-93.png" width="100%" alt="Bomberman '93"> |
| Neutopia | Street Fighter II' | Bomberman '93 |

## Mega Drive / Genesis

|  |  |  |
|---|---|---|
| <img src="images/md-comix-zone.png" width="100%" alt="Comix Zone"> | <img src="images/md-gunstar-heroes.png" width="100%" alt="Gunstar Heroes"> | <img src="images/md-sonic-3.png" width="100%" alt="Sonic the Hedgehog 3"> |
| Comix Zone | Gunstar Heroes | Sonic the Hedgehog 3 |
| <img src="images/md-phantasy-star-iv.png" width="100%" alt="Phantasy Star IV"> | <img src="images/md-vectorman.png" width="100%" alt="Vectorman"> | <img src="images/md-rocket-knight-adventures.png" width="100%" alt="Rocket Knight Adventures"> |
| Phantasy Star IV | Vectorman | Rocket Knight Adventures |

## Neo Geo Pocket Color

|  |  |  |
|---|---|---|
| <img src="images/ngpc-king-of-fighters-r1.png" width="100%" alt="The King of Fighters R-1"> | <img src="images/ngpc-kof-battle-de-paradise.png" width="100%" alt="The King of Fighters: Battle de Paradise"> | <img src="images/ngpc-biomotor-unitron.png" width="100%" alt="Biomotor Unitron"> |
| The King of Fighters R-1 | The King of Fighters: Battle de Paradise | Biomotor Unitron |

## WonderSwan / WonderSwan Color

|  |  |  |
|---|---|---|
| <img src="images/ws-dicing-knight.png" width="100%" alt="Dicing Knight"> | <img src="images/ws-inuyasha.png" width="100%" alt="Inuyasha"> |  |
| Dicing Knight | Inuyasha |  |

## Super Game Boy

|  |  |  |
|---|---|---|
| <img src="images/sgb-kirbys-dream-land-2.png" width="100%" alt="Kirby's Dream Land 2"> | <img src="images/sgb-bomberman.png" width="100%" alt="Bomberman"> | <img src="images/sgb-detective-conan.png" width="100%" alt="Detective Conan"> |
| Kirby's Dream Land 2 | Bomberman | Detective Conan |
| <img src="images/sgb-pokemon-scarlet.png" width="100%" alt="Pokemon Scarlet (fan game)"> |  |  |
| Pokemon Scarlet (fan game) |  |  |

## Source

- Mega Drive / Genesis core: [gamebub-rev2-mega-drive](https://github.com/minuitfranck/gamebub-rev2-mega-drive)
  (source, documentation and builds).
- The firmware and the other cores are not published.

## Credits

**The handheld and its software**

- [Game Bub](https://github.com/elipsitz/gamebub) by [Eli Lipsitz](https://github.com/elipsitz): the hardware, the
  firmware, the FPGA framework and the built-in Game Boy, Game Boy Color and Game Boy Advance cores. Firmware
  GPL-3.0-only; FPGA and hardware CERN-OHL-S-2.0. Everything shown here is a change to, or an addition on top of,
  that work. "Game Bub" is the name and logo of that project.
- Upstream contributions carried in the firmware: the GBA cartridge-cache valid bit by
  [coolbho3k](https://github.com/coolbho3k) (Game Bub pull request 47); the RTC weekday fix by
  [Chris Pickel](https://github.com/sfiera) (pull request 42).

**Cores**

- Super Nintendo: port for the Game Bub by [neutralinsomniac](https://github.com/neutralinsomniac) of the MiSTer
  [SNES core](https://github.com/MiSTer-devel/SNES_MiSTer) by [srg320](https://github.com/srg320). GPL-3.0.
- PC Engine / TurboGrafx-16: the MiSTer [TurboGrafx16 core](https://github.com/MiSTer-devel/TurboGrafx16_MiSTer),
  a port of [Gregory Estrade](https://github.com/Torlus)'s FPGAPCE, with MiSTer port, mappers and tweaks by
  [Sorgelig](https://github.com/sorgelig), CD support by [srg320](https://github.com/srg320), fixes by
  [greyrogue](https://github.com/greyrogue), palettes and audio filters by [Kitrinx](https://github.com/Kitrinx),
  maintenance by [dshadoff](https://github.com/dshadoff). No license is declared on that repository. HuCard save
  states from [Bruc3Dev573](https://github.com/Bruc3Dev573)'s
  [savestate fork](https://github.com/Bruc3Dev573/TurboGrafx16_MiSTer) (v0.2.0-pre1).
- NES / Famicom: the MiSTer [NES core](https://github.com/MiSTer-devel/NES_MiSTer), based on
  [FPGANES](https://github.com/strigeus/fpganes) by Ludvig Strigeus, ported and extended for MiSTer by its
  contributors. GPL-3.0.
- Neo Geo Pocket Color: the MiSTer [NGPC core](https://github.com/MiSTer-devel/NGPC_MiSTer) by
  [Kitrinx](https://github.com/Kitrinx), whose README states the core was made with AI doing most of the writing
  under their direction and debugging. GPL-2.0. The [Analogue Pocket port](https://github.com/janisc/openfpga-NGPC)
  by janisc, written with Claude, was a reference for compact saves and states.
- Mega Drive / Genesis: the archived MiSTer [Genesis core](https://github.com/MiSTer-devel/Genesis_MiSTer).
  Original Genesis code by Gregory Estrade; MiSTer port and maintenance by [Sorgelig](https://github.com/sorgelig),
  with [srg320](https://github.com/srg320), [greyrogue](https://github.com/greyrogue),
  [Kitrinx](https://github.com/Kitrinx) and [dshadoff](https://github.com/dshadoff); YM2612 and PSG by Jose Tejada
  Gomez (jt12, jt89); 68000 by Jorge Cwik (FX68K); Z80 by Daniel Wallner (T80). GPL-3.0. Save states: the engine
  from [keFEAR89](https://github.com/keFEAR89)'s
  [Genesis_MiSTer_Savestates](https://github.com/keFEAR89/Genesis_MiSTer_Savestates) fork (R58), merged and
  adapted.
- Game Boy / Game Boy Color (MiSTer core): the MiSTer [Gameboy core](https://github.com/MiSTer-devel/Gameboy_MiSTer):
  Till Harbaum's MiST core, ported and extended by [Sorgelig](https://github.com/sorgelig), Robert Peip and others.
  GPL-3.0.
- Super Game Boy: the MiSTer [SGB core](https://github.com/MiSTer-devel/SGB_MiSTer) by
  [srg320](https://github.com/srg320). GPL-3.0.
- WonderSwan / WonderSwan Color: the MiSTer [WonderSwan core](https://github.com/MiSTer-devel/WonderSwan_MiSTer) by
  Robert Peip (FPGAzumSpass). GPL-2.0.
- Game Boy Advance (MiSTer core): the MiSTer [GBA core](https://github.com/MiSTer-devel/GBA_MiSTer) by Robert Peip
  (FPGAzumSpass). GPL-2.0.

Each core contains further work credited in its own source files and license headers: CPU cores, sound chips and
helper modules.

**Other files on the card**

- emibios, an open replacement Game Boy Advance BIOS (LGPL-3.0).
- crosi12's SGB overlay pack (v1.0), turned into Super Game Boy border files.

**This project**

- minuitfranck: direction, hardware testing, and what ships.
- Claude, Anthropic's AI assistant: the code, the simulations and the documentation, under that direction.
  Commits carry a `Co-Authored-By: Claude` line. AI assistance is credited wherever a project states it, as above.

**Not included anywhere in this project's repositories**

- BIOS files and games.
- The built Super Nintendo core (its build embeds Nintendo and Capcom coprocessor firmware) and the built PC Engine
  core (no upstream license). The Super Nintendo source is public upstream.
- Kitrinx's Game Bub packages for the rev4.

## License

The text and the two handheld illustrations in this repository: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
The game screenshots belong to the games' publishers and are shown to document the device.
