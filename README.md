# lowlevel.1989

**Dev & Modder.** I like taking things apart to see how they work: emulators, game ports, ROM hacking and retro hardware, all on Linux.

I document everything step by step (in Spanish) on my blog: **[lowlevel1989.click](https://lowlevel1989.click)**

---

## Projects

- **[dbar4gun](https://github.com/lowlevel-1989/dbar4gun)**: Linux userspace driver that turns Wiimotes + a DolphinBar (or a Wii sensor bar) into light guns. Built for Raspberry Pi / RetroPie, works across MAME versions.
- **[ambidextro-port](https://github.com/lowlevel-1989/ambidextro-port)**: PortMaster port of Ambidextro (Godot) for AArch64 handhelds. Virtual or native controls, a lightweight mode for low-end devices, and mod support through Godot Mod Loader.
- **[ambidextro-mods](https://github.com/lowlevel-1989/ambidextro-mods)**: Godot mods for Ambidextro: an in-game achievements screen and snappier trampolines.
- **[tamatama](https://github.com/lowlevel-1989/tamatama)**: runs an Android game `.so` on Linux with my own loader (QEMU x86_64 and Raspberry Pi), replacing Android calls with stubs until the whole game runs native.
- **[vol2spinnerd](https://github.com/lowlevel-1989/vol2spinnerd)**: Rust daemon that turns a USB volume knob into an arcade spinner for Arkanoid in RetroArch.
- **Pachinko Wars (SNES ROM hacking)**: reverse engineering the game's LZSS compression to decompress, edit and reinsert graphics without touching the original code.
  Write-ups: [LZSS graphics](https://lowlevel1989.click/snes/pachinko-wars-entendiendo-e-inyectando-graficos-comprimidos-con-lzss-en-snes/) · [finding the money](https://lowlevel1989.click/snes/pachinko-wars-como-hallar-el-dinero/)
- **[krontra](https://github.com/lowlevel-1989/krontra)**: Contra (NES, Japan) hacking notes: finding lives and weapon values in RAM with FCEUX, then patching the ROM with Radare2.

## Contributing to

- **[PortMaster](https://github.com/PortsMaster/PortMaster-New)**: I'm part of the team. I package and maintain ports for Linux handhelds.
- **[RetroPie](https://github.com/RetroPie/RetroPie-Setup)**: dbar4gun install module for RetroPie-Setup, so light guns work out of the box.
- **[MAME (libretro)](https://github.com/libretro/mame)**: fixed the default crosshair path, which matters for light gun setups.
- **[LinApple](https://github.com/linappleii/linapple)** (Apple II emulator): disk / HDD eject support, Spanish keyboard layout and build fixes for Fedora / RHEL.

All my [merged pull requests in other projects](https://github.com/search?q=is%3Apr+author%3Alowlevel-1989+is%3Amerged+-user%3Alowlevel-1989&type=pullrequests).

## Elsewhere

- **[PICO-8 carts](https://www.lexaloffle.com/bbs/index.php?uid=117742&mode=carts&sub=2)** on Lexaloffle, like [Abacus](https://www.lexaloffle.com/bbs/index.php?tid=159322), an abacus for practicing addition and subtraction.
- **[RetroAchievements](https://retroachievements.org/user/lowlevel)**: the retro games I'm playing.

---

If my tools or write-ups are useful to you, you can support my work on [Ko-fi](https://ko-fi.com/lowlevel1989).
