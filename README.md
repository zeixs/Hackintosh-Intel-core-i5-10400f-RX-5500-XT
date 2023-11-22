# Hackintosh Intel Core i5 10400f RX 5500 XT

## Hardware
- Intel Core i5 10400f Processor (F series no integrated gpu)
- MSI B560M Mortar Wifi Motherboard
- 32Gb (4 x 8) Gb Corsair Vengeance LPX CL 16 3200MT
- Vgen 512Gb M.2 Nvme Ssd

## Things to consider
### Proccessor
- Intel core i7 10th gen (8 >= core) and below is fine using this config*
- If you are using i9 you have to adjust some parameter in config.plist

### Graphic Card
- Upon making this build, i using RX 5500xt from Sapphire,
- In theory any gpu that use same architecture should work, but in any case it's not work for you, just go to official opencore site to folow the guide

### Motherboard
- Any Motherboard with same chipset should be work, except for asus, you need to add SSDT-RHUB.aml (See official guide)

## Using this EFI
- You need to map usb on your own to suit your needs
- You need to regenerate new smbios (see official guide)


## Official Guide
- [OpenCore Official Site](https://dortania.github.io/OpenCore-Install-Guide/)

## Screenshot

![Screenshot](/screenshot/sc1.png?raw=true "Screenshoot 1")