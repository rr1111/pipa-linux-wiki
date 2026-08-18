# :material-fedora: Fedora based Distros  
[fedoraproject.org](https://fedoraproject.org/)

Until there are maintained Ubuntu/Debian images available, Fedora Linux based Distros will probably be your best choice for day-to-day stability and ease of use.  
ARM64 is a first-class architecture for Fedora, so it will probably have the best documentation and a large selection of packages.  

There are two types of Fedora based Distros available:

## Pocketblue Fedora Remix
is a libostree and Bootc based immutable Distro with a read-only root filesystem and image-based, atomic updates.  
Images are based on Upstream Silverblue/Kionite images so the experience is very close to 'stock' Fedora.  
Pocketblue will probably be your best Choice if you want a stably OS for daily use without much tinkering.  

#### Benefits:
- Very beginner-friendly
- Mature Project with own Wiki
- Stable, hard-to-break immutable Base
- Easy install with ready-made flash script
- Ships with Mu Silicium UEFI and a GRUB Bootloader, enabling easy Linux Multibooting and other Goodies
- You don't have to worry about updates, as the whole system is updated in one go

#### Drawbacks:
- You will rely heavily on Toolbox, Flatpaks and AppImages for Apps
- Atomic nature requires extra steps to install regular RPM packages
- Might feel limiting to Enthusiasts

**Useful links:**  
[Switching from kxboot to Silicium UEFI & GRUB on a running System](https://github.com/pocketblue/pocketblue/issues/223)  
[Fedora Atomic Documentation](https://docs.fedoraproject.org/en-US/atomic-desktops/getting-started/)  

[:material-linux:](../kernel.md/#pipadb-kernel): pipaDB, 7.1.7  
[Source :material-github:](https://github.com/pocketblue/pocketblue){ .md-button .md-button--primary } [Wiki :material-book:](https://pocketblue.github.io){ .md-button } [Images :material-download: ](https://github.com/pocketblue/pocketblue/releases/latest){ .md-button } [COPR :material-package: ](https://copr.fedorainfracloud.org/coprs/pocketblue){ .md-button }


## Regular Fedora
provides a regular Fedora experience with its benefits and drawbacks.  
Probably your best choice if you have prior Linux experience and want an up-to-date, stable Distro you can tinker on and still get work done.  

#### Benefits:
- Packages directly from the Fedora Repos, everything but pipa-specific packages independent from the distro maintainer
- You can build your own Images with packages of your choosing
- I try to ship the newest Kernel on my Builds
- Good mix of leading-edge and stability

#### Drawbacks:
- Things might break on updates as the maintainer has little control over a running System
- Might miss default packages (Fonts, etc ...)

[:material-linux:](../kernel.md/#pipadb-kernel) pipaDB, 7.1.7  
[rr1111 Source :material-github:](https://github.com/rr1111/pipa-fedora-builder-43){ .md-button .md-button--primary } [Images :material-download: ](https://github.com/rr1111/pipa-fedora-builder-43/releases/latest){ .md-button } [COPR :material-package: ](https://copr.fedorainfracloud.org/coprs/reyr111/pipa-packages){ .md-button }   

[:material-linux:]() 6.15.11  
[pipaDB Source :material-github:](https://github.com/PipaDB/fedora-xiaomi-pipa){ .md-button .md-button--primary } [Images :material-download: ](https://github.com/PipaDB/fedora-xiaomi-pipa/releases/latest){ .md-button } [COPR :material-package: ](https://copr.fedorainfracloud.org/coprs/rmuxnet/pipa-support){ .md-button }
