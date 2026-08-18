# :material-arch: Arch Linux based Distros 
[archlinux.org](https://archlinux.org/)

will be your best choice if you have prior experience with Linux and can get behind the concept of rolling releases.  
Arch based distros are fast, have a simple structure and allow their users great control over the OS.  
Another benefit is the [Arch User Repository (AUR)](https://aur.archlinux.org/) with a massive amount of user-maintained package builds available to be compiled using an AUR helper like `paru`.  

**Useful Links:**  
[Arch Linux News](https://archlinux.org/news/) for package updates that require manual intervention and other related Announcements.

There a two Arch based Distros available:

## Arch Linux ARM (Alarm)
[archlinuxarm.org](https://archlinuxarm.org/)  
is community port attempting to bring Arch Linux to ARMv7 and v8 based devices.  


#### Benefits:
- Fast, very customizable base OS
- Barebones images, ship without any DE or WM installed
- [Arch Wiki](https://wiki.archlinux.org/title/Main_page)
- Rolling release model **should** provide up-to-date packages

#### Drawbacks:
- Can be overwhelming for new users
- Barebones images, ship without any DE or WM installed
- Good chance of breaking your system if you mess around & don't know what youre doing
- Rolling updates can introduce breaking changes, bugs
- Repositories have been quite stale for a while, shipping outdated packages that are behind regular Arch

[:material-linux:](../kernel.md/#pipa-mainline-kernel) pipa-mainline, 6.15.11  
[Telegram :material-download: ](https://t.me/pipa_mainline/32978){ .md-button .md-button--primary } [PKGBUILDs :material-package: ](https://github.com/maakiopus/PKGBUILDs-pipa){ .md-button }


##Artix Linux ARM (ARMtix)
[armtixlinux.org](https://armtixlinux.org/)  
is the ARM port of the Artix Linux Distro, a fork of Arch that doesnt use the Systemd init system, instead offering the user a choice between multiple init systems.


#### Benefits:
- Same as Alarm
- No Systemd (Maintainer provides images shipping with `dinit`, `openrc`, `runit` & `s6`)

#### Drawbacks:
- Same as Alarm
- No Systemd (Learning curve if youre used to Systemd based OSs, packages may not be compatible / need adjustments for your init system)

**Useful links:**  
[Auris, the Artix User Repository of Init Scripts](https://auris.artixlinux.org/auris)  

[:material-linux:](../kernel.md/#pipa-mainline-kernel) main: pipa-mainline, 6.15.11
[:material-linux:](../kernel.md/#pipadb-kernel) strawberry: pipaDB, 7.1.7  
[Source :material-github:](https://github.com/Neo10e/armtix-xiaomi-pipa){ .md-button .md-button--primary } [Images :material-download: ](https://github.com/Neo10e/armtix-xiaomi-pipa/releases/latest){ .md-button } [PKGBUILDs :material-package: ](https://github.com/Neo10e/PKGBUILDs-pipa){ .md-button }
