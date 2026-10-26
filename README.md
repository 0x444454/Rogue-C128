# Rogue for Commodore C128

Ported and enhanced from Classic Rogue 5.4.4: https://github.com/Davidslv/rogue.

![screenshots](media/rogue_c128_screenshot.png)

## Requirements

- Commodore C128.
- 80 column monitor.
- Disk drive (or drive emulator).

## Release files

Binaries are [here](release/)

## Documentation

https://docs-archive.freebsd.org/44doc/usd/30.rogue/paper.pdf

## Items and enemies

<details>
  <summary>Spoiler</summary>
  <img src="media/rogue_c128_symbols.png" width="304" style="image-rendering: crisp-edges; image-rendering: pixelated;">
</details>

### Build details

- Classic Rogue 5.4.4 source code is patched to compile on [Oscar64](https://github.com/drmortalwombat/oscar64) targeting C128.  
- Code and some data stay (barely !) in bank 0, while most strings and other structs are moved to bank 1.  
- I/O routines are replaced with custom C128 versions.
- Full (optional) color modes.
- Huge upgraded PETSCII and (optional) 8x8 lifelike icons ;-)
- Full level map peek (for cheaters, won't tell you the secret key-combo).

# LICENSE

This project is licensed under a BSD-style license. See [LICENSE.TXT](release/LICENSE.TXT) for details.

Copyright (C) 1980-1983, 1985, 1999 Michael Toy, Ken Arnold and Glenn Wichman

Portions based on work by:

Nicholas J. Kisseberth (state.c, mdport.c)
David Burren (xcrypt.c)

This is a port from:
https://github.com/Davidslv/rogue

Please add a link to this github project.

