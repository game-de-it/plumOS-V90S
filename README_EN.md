# plumOS-V90S
plumOS-V90S

<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/plumOS-V90S_logo.png" width="640">  

<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc01.jpg" width="320">  

<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc02.jpg" width="320"> <img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc03.jpg" width="320">   
<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc04.jpg" width="320"> <img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc05.jpg" width="320">     

---
# Introduction

plumOS-V90S is a CFW based on the StockOS (Batocera).  
For information on how to operate Batocera, please refer to the following link:  
https://wiki.batocera.org/start

## Download
[You can download the SD image file from the "Releases" page](https://github.com/game-de-it/plumOS-V90S/releases)

## Basic Features
- [pyxel](https://github.com/kitao/pyxel) available
- Portmaster available
- OD-Commander available
- SSH connection supported  
   - Username: `root`, Password: `linux`
- Samba connection supported  
   - Username: `root`, Password: `linux`
- Improved performance with modified yabasanshiro core
- Automatic time synchronization when connected to Wi-Fi  
   - This is an experimental feature that sets the time automatically based on your location inferred from your global IP address
- Reduced noise when using USB-DAC with RetroArch
- Volume can be boosted up to 150%

## Known Issues
- Scraping feature is not available
- We cannot provide support for Portmaster; please refer to the Portmaster Discord or other resources

## OS Hotkeys
| Button Combo | Action | 
|:-------------|--------:|
| SELECT+Vol+  | Increase screen brightness |
| SELECT+Vol-  | Decrease screen brightness |
| SELECT+R2    | Enable left analog stick emulation |

> [!IMPORTANT]
> Pressing SELECT+R2 will make the D-pad emulate an analog stick, which may disable cursor movement, etc.  
> Pressing SELECT+R2 again will revert the D-pad to normal functionality, allowing cursor movement again.

## RetroArch Hotkeys
- RetroArch hotkey settings can be changed by editing the `Batocera.conf` file under the systemc directory.

| Button Combo | Action | 
|:-------------|--------:|
| SELECT+B     | Open RetroArch menu |
| SELECT+R     | Save state |
| SELECT+L     | Load state |
| SELECT+R2    | Fast forward |
| SELECT+L2    | Slow motion |
| SELECT+X     | Take a screenshot |
| SELECT+Y     | Show FPS |

> [!WARNING]
> SELECT+R2 (Fast Forward) conflicts with the analog stick emulation described earlier.  
> In most games that work with RetroArch, the left analog stick can substitute for the D-pad, so this usually won’t be an issue.  
> If you experience problems like being unable to move the cursor, press SELECT+R2 again to revert.

## About USB-DAC
- You can connect or disconnect the USB-DAC even during gameplay, but it is recommended to do so before starting a game.

## About USB Wi-Fi Dongles
<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc06.jpg" width="320">  <img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc07.jpg" width="320">   

- The TP-Link Archer T3U Nano/A Wi-Fi dongle has been confirmed to work.
    - It has high power consumption, so we recommend unplugging it when not in use.

That's all.
