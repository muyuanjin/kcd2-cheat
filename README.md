This repository is forked from the [KCD2 Cheat Mod](https://github.com/pryans/kcd2-cheat) repository, used to store my own modifications.

# Added Modifications
- Added the `cheat_transfer_items` command to the `cheat`, used to transfer all items from the npc to player/horse/stash/delete.

---

## KCD2 Cheat Mod
https://www.nexusmods.com/kingdomcomedeliverance2/mods/114

### Build Env
I use VSCode and WSL to build and release this mod.
- Install VSCode
- Install WSL
- Install WSL VSCode plugin
- Install the latest Ubuntu using the WLS plugin.
- In the terminal tab of VSCode you start an Ubuntu-XX(WSL) terminal.
- Run `./release.sh` to auto create `env.properties` then edit this file with your KCD2 path.

### Build Process
- Edit `cheat*.properties` files and bump the version numbers as needed.
- Run `./release.sh` to rebuild all mods and install them in KCD2.
- The mod zip files will be in the `./build/` folder for uploading.
