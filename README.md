[English](https://github.com/1457384613gh/rEFInd-theme-named-Yours) | [简体中文](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E8%87%AA%E8%BF%B0%E6%96%87%E4%BB%B6.md) | [繁体中文](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E7%B9%81%E4%BD%93%E4%B8%AD%E6%96%87.md)
# rEFInd-theme-named-Yours
It is a theme of rEFInd Boot Manager that can set ___your profile___, ___device___ and ___your name___.

## Set Resolution and Choose Mouse or Touch
Download the last from [Releases](https://github.com/1457384613gh/rEFInd-theme-named-Yours/releases).

Unpack the zip.

Edit `\EFI\refind\themes\Yours\theme.conf`

(Edit `\EFI\boot\themes\Yours\theme.conf` for old devices)

to select your resolution and decide mouse or touch
![image](https://user-images.githubusercontent.com/69227436/162579811-bf3277c0-0ce0-4c35-b22a-a49370ae34fc.png)

## Edit Banner to Set Your Profile, Device and Your Name
Open `\EFI\refind\themes\Yours\banners\$resolution\BannerEditor.pptx` by using Microsoft Office 2021+

(`Open \EFI\boot\themes\Yours\banners\$resolution\BannerEditor.pptx` by using Microsoft Office 2021+ for old devices)
![image](https://user-images.githubusercontent.com/69227436/162580042-d32719bf-5091-41cd-976e-527087642f37.png)
to set your profile, device and your name.

Export as png to overwrite BannerEditor.png
![image](https://user-images.githubusercontent.com/69227436/162580182-73dcc418-c6e0-4802-af90-daab30ede40d.png)

## Read and Write ESP
For new devices, copy the folder named refind into `ESP: /EFI/`

For old devices, copy the folder named boot into `ESP: /EFI/`

## Add a New Boot Entry
By UEFI BIOS setup

## Reboot to see what if
Here is mine.
![image](https://user-images.githubusercontent.com/69227436/164479464-442996f7-ffc3-47f2-94c5-a258369c3a5e.png)

## Credits
Many icons have been adapted from [refind-theme-regular](https://github.com/munlik/refind-theme-regular) of [munlik](https://github.com/munlik)

Some icons have been adapted from [The rEFInd Boot Manager](http://www.rodsbooks.com/refind/)

Some icons have been adapted from [brunch](https://github.com/sebanc/brunch/)

A few has been adapted from unknown.
