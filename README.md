# Hackintosh EFI for PC

- Tested in Catalina 10.15.
- Everything works (for me).


## Specs
- **Motherboard**: MSI Z170A Gaming M5
- **CPU**: Intel I7 6700K
- **Memory**: Corsair 1x16G 2400MHz
- **GPU**: MSI Radeon VII

## Bios
1. Pressed F6 first for defaults
2. Disable XHCI Hand-off
3. Disable Serial Port
4. Disable CFG Lock
5. Disable VT-D

## SMBIOS
Has been set to iMacPro1,1 due to Rsdeon VII fully utilized only in iMac Pro's SMBIOS.

## TODO
Thermals - FakeSMC sensors, etc.

## References
- [Vanilla Skylake Guide](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/config.plist-per-hardware/skylake)
- TonyMacX86
