# Linux Kernel Information and Status

## Kernel developers
The talented People involved in initial kernel upbringing, maintenance, porting ...  
List credit to: [TheMojoMan/xiaomi-pipa](https://github.com/TheMojoMan/xiaomi-pipa).  
In no particular order or degree of involvement. Completeness not guaranteed.  
Please open a PR if you're missing!

- adomerle [:material-github:](https://github.com/adomerle) 
- vipaoL [:material-github:](https://github.com/vipaoL) 
- luka177 [:material-github:](https://github.com/luka177) 
- Dominik Sitarski [:material-github:](https://github.com/domin746826) 
- Danila Tikhonov [:material-github:](https://github.com/JIaxyga) 
- Teguh Sobirin [:material-github:](https://github.com/tjstyle) 
- lujianhua [:material-github:](https://github.com/lujianhua) 
- map220v [:material-github:](https://github.com/map220v) 
- maverickjb [:material-github:](https://github.com/maverickjb) 
- rmuxnet [:material-github:](https://github.com/rmuxnet) 
- Users nixxiz, nikroks at pipa telegram groups 
- [postmarketOS Team](https://postmarketos.org) 

## Kernel Hardware Status
- all Kernels:

| Sleep | Speakers | Mic | WLAN | Bluetooth | Charging @10w | Battery Status | Hall Sensor | Display | Brightness | Touch | GPU | USB (Host/Client) | DP alt mode | UFS | Back Camera | Front Camera | Sensors | Xiaomi Keyboard | Pen |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ | ✅️ (Video only) | ✅️ | ⚠️ (sometimes) | ❌️ | ⚠️ (flaky) | ✅️ (pmOS: ❌️) | ✅️ (pmOS: ❌️) |  
  
## Actively maintained Kernels
All of those are based on the original port of the mainline kernel.  

Currently, the 6.18.2 branch of pipa-mainline seems to be the most stable, at least to me.  


### pipaDB Kernel
- source at [github.com/pipaDB/linux](https://github.com/pipaDB/linux)
- latest version: `7.1.7`
- 'close-to'-mainline
- DP alt mode audio, front camera, ~~25w charging~~ working on newest branches



### pipa-mainline Kernel
- source at [github.com/pipa-mainline/linux](https://github.com/pipa-mainline/linux)
- latest version: `6.18.28`
- 'close-to'-mainline



### postmarketOS Kernel
- source at [gitlab.postmarketos.org/postmarketOS/pmaports/-/tree/main/device/testing/linux-xiaomi-pipa](https://gitlab.postmarketos.org/postmarketOS/pmaports/-/tree/main/device/testing/linux-xiaomi-pipa)
- latest version: `7.1.4`
- mainline kernel with separate patches
- seemingly no support for the Xiaomi Pen & Keyboard at this time
