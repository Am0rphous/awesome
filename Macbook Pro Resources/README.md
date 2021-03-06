# Macbook Pro Resources

## Collection of various resources
- [Awesome Mac](https://github.com/jaywcjlove/awesome-mac)
- [Awesome macOS](https://github.com/iCHAIT/awesome-macOS) -  A curated list of awesome applications, softwares, tools and shiny things for macOS.
- [Awesome macOS open source applications by  serhii-londar](https://github.com/serhii-londar/open-source-mac-os-apps)
- [Cmatrix](https://github.com/levithomason/cmatrix) - The original Matrix effect for your Mac terminal.
- [Download-BigSur](https://github.com/chris1111/Download-BigSur) - Simple macOS Appplication for downloading macOS Big Sur 11.
- [Mac Apps](https://github.com/jeffreyjackson/mac-apps)


## Communication
- [ThunderBird](https://www.thunderbird.net)
  #### IRC
  - [LimeChat](http://github.com/psychs/limechat) - IRC Client for Mac. [limechat.net/mac](http://limechat.net/mac)

## Monitoring
- [ProcessMonitor](https://github.com/objective-see/ProcessMonitor) - Process Monitor Library (based on Apple's new Endpoint Security Framework.

## Music
- [Beardedspice](https://github.com/beardedspice/beardedspice) - Mac Media Keys for the Masses.
- [Cumulus](https://github.com/gillesdemey/Cumulus) - ☁️ A SoundCloud player that lives in your menubar.
- [eqMac](https://github.com/bitgapp/eqMac) - macOS System-wide Audio Equalizer 🎧 [eqmac.app](https://eqmac.app).
- [SoundCleod](https://github.com/salomvary/soundcleod) - SoundCloud for macOS and Windows.
- [Soundnode](https://www.soundnodeapp.com) - An opensource SoundCloud app for Desktop.
- [Vox](https://vox.rocks/) - Premium Mac Music Player for Hi-Res music through the popular sources.

## Network
- [LuLu](https://github.com/objective-see/LuLu) - LuLu is the free macOS firewall.
  - Install with `brew install lulu`
  ### Proxy
  - [clashX](https://github.com/yichengchen/clashX) - A rule based proxy For Mac base on Clash.
  - [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG) - Next Generation of ShadowsocksX.
  ### Security
  - [DoNotDisturb](https://github.com/objective-see/DoNotDisturb) - Detect Evil Maid Attacks. 'Do Not Disturb' (DnD) is a free open-source security tool for macOS that aims to detect unauthorized physical access to your laptop!
  - [ReiKey](https://github.com/objective-see/ReiKey) - Malware and other applications may install persistent keyboard "event taps" to intercept your keystrokes. ReiKey can scan, detect, and monitor for such taps!

## Tools
- [Eul](https://github.com/gao-sun/eul) - 🖥️ macOS status monitoring app written in SwiftUI.
- [Java](https://www.oracle.com/java/technologies/javase-jdk15-downloads.html) - Go and download the .dmg file and follow instructions.
- [Keka](https://github.com/aonez/Keka) - The macOS file archiver.
- [MacForge](https://github.com/MacEnhance/MacForge) - Plugin, App, and Theme store which includes plugin injection for macOS.
- [MacHack](https://github.com/kendfinger/MacHack) - Hidden Tools in macOS.
- [MacOS Fortress](https://github.com/essandess/macOS-Fortress) - Firewall and Privatizing Proxy for Trackers, Attackers, Malware, Adware, and Spammers with Anti-Virus On-Demand and On-Access Scanning (PF, squid, privoxy, hphosts, dshield, emergingthreats, hostsfile, PAC file, clamav).
- [The Unarchiver](https://apps.apple.com/us/app/the-unarchiver/id425424353?mt=12) - Open any archive in seconds.
- [Shield](https://github.com/theevilbit/Shield) - An app to protect against process injection on macOS.
- [WineBottler](https://winebottler.kronenberg.org) - Run .exe files on Macbook using Wine. Logfile: `~/Library/Logs/Wine.log`
- [WineHQ for MacOS](https://wiki.winehq.org/MacOS) - Requires `brew install xquartz` >= 2.7.7. [xquartz.org](https://www.xquartz.org) `brew cask install wine-stable`
  ### Creating Bootable USB
  - dd - check my [Disk CheatSheet notes](https://github.com/Am0rphous/CheatSheets/blob/main/Linux/Disk.md)
  - diskutil command. Procedure is as follows
  ````
  diskutil list
  diskutil unmountDisk /dev/disknumber
  sudo dd if=/path/to/image.iso of=/dev/rdisknumber bs=1m>
  sudo dd if=/Users/user_name/Downloads/CentOS-8-x86_64-boot.iso of=/dev/rdisk2
  ````
  ### Development
  - [Node-appDMG](https://github.com/LinusU/node-appdmg) - 💾 Generate your app dmgs.
  - [Rumps](https://github.com/jaredks/rumps) - Ridiculously Uncomplicated macOS Python Statusbar apps.
  - [Tray Example](https://github.com/kevinsawicki/tray-example) - Electron Tray Mac OS X Example App.
  ### Package Managers
  - [Brew / HomeBrew](https://brew.sh/) - Package Manager for Linux and MacOS.
  - [Brew Documentation](https://docs.brew.sh)

   Quick install:
   ````
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ````
- [Homebrew gathers anonymous aggregate user behaviour analytics using Google Analytics. ](https://docs.brew.sh/Analytics#opting-out)
   To opt out of analytics, run
   ````
   export HOMEBREW_NO_ANALYTICS=1
   brew analytics off
   ````
### Remote Desktop Applications
- [Remote Desktop Manager Free](https://remotedesktopmanager.com/home/downloadfree) - Windows, Mac, Linux, Android & iOS.
### Virtualization
- [QEMU](https://www.qemu.org/download/#macos) - May be installed with `brew install qemu`.
- [Parallels Desktop ($)](https://www.parallels.com/eu/) - The fastest, easiest and most powerful application for running Windows on Mac—without rebooting. Includes 30+ utilities to simplify everyday tasks on Mac and Windows.
- [VirtualBox](https://www.virtualbox.org)
- [VMWare Fusion](https://www.vmware.com/products/fusion/fusion-evaluation.html)
  - [Open Virtualization Format Tool (ovftool)](https://code.vmware.com/web/tool/4.4.0/ovf) - VMware OVF Tool is a command-line utility that allows you to import and export OVF packages to and from many VMware products.

## Macbook with Linux
- [bcwc_pcie](https://github.com/patjak/bcwc_pcie) - Reverse engineered Linux driver for the FacetimeHD (Broadcom 1570) PCIe webcam.
- [Hw-probe](https://github.com/linuxhw/hw-probe) - Probe for hardware, check operability and find drivers.
- [Linux ARM M1](https://github.com/corellium/linux-m1)
- [Linuxbrew Core](https://github.com/Homebrew/linuxbrew-core) - [Linuxbrew documentation](https://docs.brew.sh/Homebrew-on-Linux)
- [mbp-2016-linux](https://github.com/Dunedan/mbp-2016-linux) - State of Linux on the MacBook Pro 2016 & 2017.
- [mbp-ubuntu-kernel](https://github.com/marcosfad/mbp-ubuntu-kernel) - Ubuntu Kernel for MacBook Pro (incl. T2 patches).
- [Roadrunner2's macbook12-spi-driver](https://github.com/roadrunner2/macbook12-spi-driver) - Input driver for the SPI keyboard / trackpad found on 12" MacBooks (2015 and later) and newer MacBook Pros (late 2016 through mid 2018), as well a simple touchbar and ambient-light-sensor driver for late 2016 MacBook Pro's and later.
- [State of Linux on the MacBook Pro 2016 & 2017](https://github.com/Dunedan/mbp-2016-linux) - Provides an overview about Linux support for Apple's MacBook Pro 2016 and MacBook Pro 2017 models.

  ### Linux tools specificly for Macbook
  - [mbpfan](https://github.com/linux-on-mac/mbpfan) - A simple daemon to control fan speed on all MacBook/MacBook Pros (probably all Apple computers) for Linux Kernel 3 and newer 

## Productivity
- [AirUnlock-for-Mac (Archived)](https://github.com/pinetum/AirUnlock-for-Mac) - Using android phone to establish a connection with your Mac via Bluetooth low-energy (BLE), controlling Mac lock state (Lock or Unlock).
- [Fanny](https://github.com/DanielStormApps/Fanny) - Monitor your Mac's fan speed and CPU/GPU temperature from your Notification Center. [fannywidget.com](https://www.fannywidget.com)
- [KeepingYouAwake](https://github.com/newmarcel/KeepingYouAwake) - A Caffeine clone for macOS. Prevents your Mac from going to sleep. 
- [MacOS Big Sur - Replacements Icons](https://github.com/elrumo/macOS_Big_Sur_icons_replacements) -  Replacement icons for popular apps in the style of macOS Big Sur.
- [PodcastMenu](https://github.com/insidegui/PodcastMenu) - Put Overcast on your Mac's menu bar.
  ### Automation
  - [Hammerspoon](https://github.com/Hammerspoon/hammerspoon) - Staggeringly powerful macOS desktop automation with Lua.
  - [Mjolnir](https://github.com/mjolnirapp/mjolnir) - Lightweight automation and productivity app for OS X.
  ### Time
  - [Countdown](https://github.com/funway/Countdown) - A countdown task App on macOS.
  - [MenubarCountdown](https://github.com/kristopherjohnson/MenubarCountdown) - Menubar countdown timer for macOS.
