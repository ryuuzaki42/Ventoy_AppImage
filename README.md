
# Ventoy_AppImage

Ventoy is an open source tool to create bootable USB drive for ISO/WIM/IMG/VHD(x)/EFI files

https://www.ventoy.net/en/index.html

## Repository: https://github.com/ryuuzaki42/Ventoy_AppImage
    Ventoy: 1.1.17

### Run it as root
    su
    ./Ventoy-*_JB-x86_64.AppImage

### Or
    sudo ./Ventoy-*_JB-x86_64.AppImage

### If use KDE
    kdesu ./Ventoy-*_JB-x86_64.AppImage

---
### Errors
1. cannot open display: :1 - https://github.com/ryuuzaki42/Ventoy_AppImage/issues/5

   Try:

        xhost +SI:localuser:root

    Or: https://github.com/ryuuzaki42/Ventoy_AppImage/issues/5#issuecomment-5132052855

---
Based on: https://github.com/stupid-kid-af/Ventoy-AppImage

---
https://github.com/ventoy/Ventoy/releases
