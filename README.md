[English](https://github.com/1457384613gh/rEFInd-theme-named-Yours) | [简体中文](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E8%87%AA%E8%BF%B0%E6%96%87%E4%BB%B6.md) | [繁體中文](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E7%B9%81%E4%BD%93%E4%B8%AD%E6%96%87.md)
|---|---|---|
|[Preview](https://github.com/1457384613gh/rEFInd-theme-named-Yours#reboot-to-see-what-if)|[预览效果](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E8%87%AA%E8%BF%B0%E6%96%87%E4%BB%B6.md#%E9%87%8D%E5%90%AF%E7%9C%8B%E7%9C%8B)|[預覽效果](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E7%B9%81%E4%BD%93%E4%B8%AD%E6%96%87.md#%E9%87%8D%E5%95%9F%E7%9C%8B%E7%9C%8B)

# rEFInd-theme-named-Yours
It is a theme of rEFInd Boot Manager, which can
- set ___your profile___
- set ___device___
- set ___your name___.

## Note!
- #If you have **ChromeOS on BrunchFramework**, you shall read **[this](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/README/Brunch.md)**.
- #If you have OpenCore, you shall set `LauncherOption=System`.
- #If you have Bliss OS, `/EFI/android` should be renamed `/EFI/blissos` .
- #If you have prime os, `/EFI/android` should be renamed `/EFI/prime` .
- #If you have Phoenix OS Darkmatter, `/EFI/android` should be renamed `/EFI/darkmatter` .
- #If you have ventoy, `VTOY: /EFI/BOOT` should be renamed `VTOY: /EFI/VENTOY` .
- #如果你的U盘里有微PE工具箱，`U盘：/EFI/BOOT` 应该被重命名为 `U盘：/EFI/WEPE` 。

## Download the last with `.vhdx` or `.zip`
1. Download the last from [Releases](https://github.com/1457384613gh/rEFInd-theme-named-Yours/releases).
### As for `.vhdx`
- `.vhdx` can be used by hyper-V; You can preview by hyper-V.
- You can mount `.vhdx` by Windows 10+ for editing and copying.
- The resolution is 1024×768.
![image](https://user-images.githubusercontent.com/69227436/166185140-c74909ee-31b5-4dd4-9716-13b1073a9504.png)
### As for `.zip`
- `.zip` is so easy to use.
- The resolution is 1920×1080.

## Set Resolution and Choose Mouse or Touch
 #1.5 Mount `.vhdx`

 #1.5 Unpack `.zip`
 
2. Edit `\EFI\refind\themes\Yours\theme.conf`

 #2. (Edit `\EFI\boot\themes\Yours\theme.conf` for old devices)

- to select your resolution
- to decide mouse or touch
![image](https://user-images.githubusercontent.com/69227436/164884137-91064754-2100-4f7b-8fa7-57a37b833164.png)

## Edit Banner to Set Your Profile, Device and Your Name
- You can edit banner by using [Microsoft Office 2021+](https://github.com/1457384613gh/rEFInd-theme-named-Yours#for-microsoft-office-2021)
- You can edit banner by using [Adobe Photoshop](https://github.com/1457384613gh/rEFInd-theme-named-Yours#for-adobe-photoshop)
### For Microsoft Office 2021+
3. Open `\EFI\refind\themes\Yours\banners\$resolution\BannerEditor.pptx` by using Microsoft Office 2021+

 #3. (Open `\EFI\boot\themes\Yours\banners\$resolution\BannerEditor.pptx` by using Microsoft Office 2021+ for old devices)

![image](https://user-images.githubusercontent.com/69227436/164608436-e3b76607-7b73-4016-be0b-ec3c23ae9012.png)
- to set your profile
- to set device 
- to set your name.

![image](https://user-images.githubusercontent.com/69227436/164615647-597163f7-4021-4ae5-922f-7fef1ce521bb.png)
4. Export as png to overwrite BannerEditor.png
![image](https://user-images.githubusercontent.com/69227436/164616497-d3ca3e4a-f231-4fc2-99ac-587a32c09453.png)
### For Adobe Photoshop
- #(Also, you can use [online PS](https://ps.gaoding.com/#/))
3. Open `\EFI\refind\themes\Yours\banners\$resolution\BannerEditor.psd` by using Adobe Photoshop

 #3. (Open `\EFI\boot\themes\Yours\banners\$resolution\BannerEditor.psd` by using Adobe Photoshop for old devices)

- to set your profile
- to set device 
- to set your name.

![image](https://user-images.githubusercontent.com/69227436/164608548-03b00cf6-4c88-489e-878a-aec8f328f1ce.png)

4. Export as png to overwrite BannerEditor.png
### For those who have no these fonts
- `Agency FB`  is the font of `The Device`
- `French Script MT` is the font of `your name`

 #4.5. If you have no these fonts, you can download and install [These Fonts](https://github.com/1457384613gh/rEFInd-theme-named-Yours/releases/tag/Fonts).

 #4.5. You can select other fonts you like.

## Read and Write ESP
5. For new devices, copy the folder named refind into `ESP: /EFI/`

 #5. For old devices, copy the folder named boot into `ESP: /EFI/`

## Add a New Boot Entry
6. By UEFI BIOS setup

## Reboot to see what if
Here is mine.
![5_screenshot_001](https://user-images.githubusercontent.com/69227436/166140209-6f2c14b6-1e0c-4f29-8cae-74b85285fb1d.png)
![5_screenshot_002](https://user-images.githubusercontent.com/69227436/166140211-fc94ed16-946b-4974-9cb5-0945c276cfcf.png)

## Star
 #7. If you like it and are looking forward to the coming update, you can star it.⭐
 
## Credits
Many icons have been adapted from [refind-theme-regular](https://github.com/munlik/refind-theme-regular) of [munlik](https://github.com/munlik)

Some icons have been adapted from [The rEFInd Boot Manager](http://www.rodsbooks.com/refind/)

Some icons have been adapted from [brunch](https://github.com/sebanc/brunch/)

A few has been adapted from unknown.
