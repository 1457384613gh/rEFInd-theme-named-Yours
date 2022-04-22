[English](https://github.com/1457384613gh/rEFInd-theme-named-Yours) | [简体中文](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E8%87%AA%E8%BF%B0%E6%96%87%E4%BB%B6.md) | [繁体中文](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E7%B9%81%E4%BD%93%E4%B8%AD%E6%96%87.md)
|---|---|---|
|[Preview](https://github.com/1457384613gh/rEFInd-theme-named-Yours#reboot-to-see-what-if)|[预览效果](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E8%87%AA%E8%BF%B0%E6%96%87%E4%BB%B6.md#%E9%87%8D%E5%90%AF%E7%9C%8B%E7%9C%8B)|[預覽效果](https://github.com/1457384613gh/rEFInd-theme-named-Yours/blob/main/%E7%B9%81%E4%BD%93%E4%B8%AD%E6%96%87.md#%E9%87%8D%E5%95%9F%E7%9C%8B%E7%9C%8B)

# rEFInd-theme-named-Yours
It is a theme of rEFInd Boot Manager that can set ___your profile___, ___device___ and ___your name___.

#If you have OpenCore, you shall set `LauncherOption=System`.

## Set Resolution and Choose Mouse or Touch
Download the last from [Releases](https://github.com/1457384613gh/rEFInd-theme-named-Yours/releases).

Unpack the zip.

Edit `\EFI\refind\themes\Yours\theme.conf`

(Edit `\EFI\boot\themes\Yours\theme.conf` for old devices)

to select your resolution and decide mouse or touch
![image](https://user-images.githubusercontent.com/69227436/164616080-c1fbb4b0-58de-4eab-807e-905f8affc065.png)

## Edit Banner to Set Your Profile, Device and Your Name
You can edit banner by using [Microsoft Office 2021+](https://github.com/1457384613gh/rEFInd-theme-named-Yours#for-microsoft-office-2021) or [Adobe Photoshop](https://github.com/1457384613gh/rEFInd-theme-named-Yours#for-adobe-photoshop)
### For Microsoft Office 2021+
Open `\EFI\refind\themes\Yours\banners\$resolution\BannerEditor.pptx` by using Microsoft Office 2021+

(Open `\EFI\boot\themes\Yours\banners\$resolution\BannerEditor.pptx` by using Microsoft Office 2021+ for old devices)

![image](https://user-images.githubusercontent.com/69227436/164608436-e3b76607-7b73-4016-be0b-ec3c23ae9012.png)
to set your profile, device and your name.

![image](https://user-images.githubusercontent.com/69227436/164615647-597163f7-4021-4ae5-922f-7fef1ce521bb.png)
Export as png to overwrite BannerEditor.png
![image](https://user-images.githubusercontent.com/69227436/164616497-d3ca3e4a-f231-4fc2-99ac-587a32c09453.png)
### For Adobe Photoshop
Open `\EFI\refind\themes\Yours\banners\$resolution\BannerEditor.psd` by using Adobe Photoshop

(Open `\EFI\boot\themes\Yours\banners\$resolution\BannerEditor.psd` by using Adobe Photoshop for old devices)

to set your profile, device and your name.
![image](https://user-images.githubusercontent.com/69227436/164608548-03b00cf6-4c88-489e-878a-aec8f328f1ce.png)

Export as png to overwrite BannerEditor.png

## Read and Write ESP
For new devices, copy the folder named refind into `ESP: /EFI/`

For old devices, copy the folder named boot into `ESP: /EFI/`

## Add a New Boot Entry
By UEFI BIOS setup

## Reboot to see what if
Here is mine.
![image](https://user-images.githubusercontent.com/69227436/164609533-dbaa87f5-4384-4cbb-b8f3-8c457af7169b.png)

## Credits
Many icons have been adapted from [refind-theme-regular](https://github.com/munlik/refind-theme-regular) of [munlik](https://github.com/munlik)

Some icons have been adapted from [The rEFInd Boot Manager](http://www.rodsbooks.com/refind/)

Some icons have been adapted from [brunch](https://github.com/sebanc/brunch/)

A few has been adapted from unknown.
