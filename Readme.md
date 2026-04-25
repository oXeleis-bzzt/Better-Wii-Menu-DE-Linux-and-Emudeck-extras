<img width="902" height="243" alt="banner" src="https://github.com/user-attachments/assets/e0752819-14d6-491c-866d-1c5be08bf07d" />

# Better Wii Menu - For Dolphin Emulator - Linux and Emudeck Extras

A custom Dolphin build that lets disc image files (.rvz, .iso, .wbfs, .gcz, .ciso, .wia) work as channels on the Wii System Menu.

Switching between games has never been easier!
### Features

- Automatically syncs users' Dolphin game library with the Wii Menu

- Switching between games is now possible with only the Wii Remote

- Right-click any game in the Dolphin menu to manually add/remove games from the Wii Menu

- Visually replicates the same experiences as if game files are .wad in Wii Menu

### How to use
*You have to uninstall dolphin emulator if you already have it installed as a flatpak whether from flathub or from emudeck.*

1. Download the flatpak from the release page
2. Install it with `flatpak install --user BetterWiiMenuDE.flatpak`
3. Launch the emulator, go to tools, perform online update and choose region
4. Load up the Wii Menu or head straight into a game and enjoy easier game switching!

### Emudeck Extras (works in steam deck game mode)
If you installed dolphin emulator with emudeck before you still have to uninstall it first but after installing with this method the emulator will regain all of emudeck's configurations.

If you want to launch directly to the home menu from a Frontend such as ES-DE with emudeck then follow steps 1-3 and then:
1. Download the file `Wii-Menu.sh` from the release page
2. Drag it to your emulation folder, then roms, then desktop, and place the .sh file there
3. A new console section will appear when you go back to game mode and to emulation station called desktop, it will recognize the file we added and will launch the emulator directly to the home menu (this desktop folder is actually useful for launching many other actual desktop stuff you have without leaving the emulation station or game mode)


If the `Wii-Menu.sh` file doesn't work for you, you might need to open it with a text editor and change the numeric code inside to the correct one for your region.
