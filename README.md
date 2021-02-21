# macOS-Thinkpad-T430-OC
EFI folder for hackintosh development with OpenCore. Work in progress.
Made with OC 0.6.5
- Remember to generate SMBIOS values! See https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/ivy-bridge.html#starting-point for full info.

# Working:
- wifi
- power on/off
- USB (all 4!)
- iServices
- Audio (through replacing AppleALC.kext with VoodooHDA.kext in post-install)

# Not working:
- Sleep (only display off)
- Battery Readout 
- App Store (recently stopped, worked with this setup)
- Bluetooth (unusure, not present on this system)
- Airdrop

Tested to boot with MacOS High Sierra and Mojave. This will be updated as progress is made. Credit to OpenCore team, tonymacx86, r/hackintosh, corpnewt and Rehabman for resources.
