中文
# rEFInd-theme-named-Yours
It is a theme of rEFInd Boot Manager that can set your profile, device and your name.

## Set Resolution and Choose Mouse or Touch
Download the last from release.

Unpack the zip.

Edit \EFI\refind\themes\Yours\theme.conf

(Edit \EFI\boot\themes\Yours\theme.conf for old devices)

to choose your resolution and choose mouse or touch
![image](https://user-images.githubusercontent.com/69227436/162579811-bf3277c0-0ce0-4c35-b22a-a49370ae34fc.png)

## Edit Banner to Set Your Profile, Device and Your Name
Open \EFI\refind\themes\Yours\banners\$resolution\BannerEditor.pptx by using Microsoft Office 2021+

(Open \EFI\boot\themes\Yours\banners\$resolution\BannerEditor.pptx by using Microsoft Office 2021+ for old devices)
![image](https://user-images.githubusercontent.com/69227436/162580042-d32719bf-5091-41cd-976e-527087642f37.png)
to set your profile, device and your name.

Export as png to overwrite BannerEditor.png
![image](https://user-images.githubusercontent.com/69227436/162580182-73dcc418-c6e0-4802-af90-daab30ede40d.png)

## Read and Write ESP
For new devices, copy the folder named refind into ESP: /EFI/

For old devices, copy the folder named boot into ESP: /EFI/

## Add a New Boot Entry
By UEFI BIOS setup

## Reboot to see what if
Here is mine.
![screenshot_001](https://user-images.githubusercontent.com/69227436/162580866-cff24d07-04b4-4553-8411-f34884d94f2b.png)
