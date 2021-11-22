# mtkclient-gui
GUI tool for unlocking bootloader and bypassing authorization on Mediatek devices

Note: This program was made for Windows 10 and 11 and might not run properly on older versions and other OSes.

## Creating a distributable archive for Windows
1. Download Python 3.9 from https://python.org/downloads
2. Install it to mtkclient-gui/runtime folder
3. Open PowerShell
4. `.\python -m ensurepip`
5. `.\python -m pip install -r ..\requirements.txt`
6. `.\python -m pip install -r https://github.com/bkerler/mtkclient/raw/main/requirements.txt`
7. Package everything in a ZIP archive

## Bootloader lock/unlock
This is the list of devices that work/doesnt work properly with this feature

### Works with
Redmi Note 9  
Redmi 9  
Redmi 9A  
Redmi 9C  
Redmi Note 8 Pro  
Redmi Note 9T  
Redmi Note 10S

### Doesnt work with
Redmi 6A  
Redmi 6

If your device isnt listed here, that doesnt mean it doesnt work, you should take a backup of your devinfo, proinfo and seccfg partitions and try unlocking your bootloader, you can report your success/failure with unlocking the bootloader to this repo.
