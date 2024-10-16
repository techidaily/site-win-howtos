---
title: The Ultimate Guide to Correcting Windows Error Code 0X8000FFFF Issues on Your PC
date: 2024-10-09T20:45:48.250Z
updated: 2024-10-15T23:42:38.436Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes The Ultimate Guide to Correcting Windows Error Code 0X8000FFFF Issues on Your PC
excerpt: This Article Describes The Ultimate Guide to Correcting Windows Error Code 0X8000FFFF Issues on Your PC
thumbnail: https://thmb.techidaily.com/7ac5f26a6db87f846700248f8f73ccc48783db9e18aa51cea1cc573fd025f0cb.jpg
---

## Conquering the Blue Screen of Death: Fix Your Windows 0xC0000098 Error Today

 While booting your PC, Windows gives you a BSOD with the**error code** **0xc0000098** . It can be rather frustrating not being able to use your device. You just get stuck at the blue/black screen. But don’t panic. This is a most common Windows error and it’s never hard to fix it at all…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## About the error 0xc0000098

> _During the start-up process, the**Boot Configuration Data** (BCD) is very essential to provide required information to load the operating system. If the Boot Configuration Data is missing or corrupted, Windows won’t be able to load operating system and gives you the error**0xc0000098** ._

![](https://images.drivereasy.com/wp-content/uploads/2019/12/0xc0000098-windows-7.jpg)

 _Error Code**0xc0000098**_  o_n Windows 7, Vista_

![](https://images.drivereasy.com/wp-content/uploads/2019/12/0xc0000098.jpg)

 _Error Code**0xc0000098**_  o_n Windows 10, 8, 8.1_

## Try these fixes

 Below you will get to know all possible fixes to solve your boot error 0xc0000098\. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Rebuild BCD manually](#f1)**
2. **[Try Startup Repair](#f2)**
3. **[Perform a CHKDSK](#f3)**
4. **[Run System File Checker](#f4)**
5. **[Use a Windows Reimage Tool](#fix-reimage)**
6. **[Perform a clean install of Windows](#f5)**

### Fix 1: Rebuild BCD manually

 Since this is a BSOD error, you won’t be able to access your PC normally. To repair your PC, you’ll need to use a Windows recovery drive: an installation USB media or a CD/DVD.

#### Step 1: Prepare installation media

 If you don’t have one, you need to create USB/DVD bootable media yourself. Here is how to do it:

**Note:** You can skip to Step 2 if you already have a (DVD/USB) installation media.

 1) Go to **[Windows 10 download](https://www.microsoft.com/en-us/software-download/windows10)**  page. (Or **[Windows 11](https://www.microsoft.com/software-download/windows11) ,** [Windows 8](https://www.microsoft.com/en-us/software-download/windows8ISO) ,[**Windows 7**](https://www.microsoft.com/en-us/software-download/windows7) )

![](https://images.drivereasy.com/wp-content/uploads/2020/01/download-win-10-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062447/7443" target="_top" id="1062447">
  <img src="//a.impactradius-go.com/display-ad/7443-1062447" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062447/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Download the installation media and save it on your computer.

3) Double-click the Media Creation Tool to launch the tool.

4) Select the **Create installation media (USB flash drive, DVD, or ISO file) for another PC** option.

![](https://images.drivereasy.com/wp-content/uploads/2020/01/Create-instalaltion-media-USB-flash-driveor-CD-DVD.jpg)

 5) Select the language, edition, and architecture (64-bit or 32-bit) for the Windows system.

 6) Choose your preferred media. If you choose a USB flash drive, make sure you have a blank USB flash drive with at least 8GB of space.

 7) Follow the on-screen instructions to finish the setup.

#### Step 2: Change the boot order to USB/DVD

 Change the boot order in the BIOS setup. If you use a bootable USB drive, please put**Removable Devices** as the first boot choice. Otherwise, your PC will boot normally from your hard drive.

1) Turn on your device.

2) As soon as your computer starts booting up, press the function key to enter BIOS.

**Note:** The key to access BIOS can vary from**Esc** ,**Delete** to**F2** ,**F8** ,**F12** , depending on your manufacturer and computer model.  
![](https://images.drivereasy.com/wp-content/uploads/2019/12/keyboard-bios-keys.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Once in BIOS, go to the**Boot** sector and set**Removable Devices** or**CD-Rom Drive** as the first boot device.

 4) Save the changes and exit.

#### Step 3: Boot with an Installation or Repair disc or USB drive

1) Boot your PC from the bootable CD/DVD/USB.

2) In the Windows Setup menu, click**Next** .

3) Select**Repair your computer** in the lower-left corner.

4) Go to**Troubleshoot** \>**Advanced Options** \>**Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt.png)

 5) In Command Prompt, type the following command lines and hit Enter after each command. (There’s a space between**bootrec** and**/** .)

bootrec /scanos

bootrec /fixmbr

bootrec /fixboot

bootrec /rebuildbcd

 Type**Y** and press**Enter** if you’re prompted for permission.

 6) After you have entered the commands above, close the Command Prompt and Reboot your PC.

 The 0xc0000098 error should now be fixed as your PC begins to load. If not, try the fix below.

### Fix 2: Startup Repair

 Startup Repair is a built-in tool to diagnose and repair some common problems on Windows. You may need to run Startup Repair (even 2 or 3 times).

1) Boot your PC from your setup disk (USB/DVD/CD).

2) Select**Repair your computer** and go to**Troubleshoot** \>**Advanced Options** \>**Startup Repair** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/startup-repair.jpg)

 3) Startup Repair will begin scanning your installation for known issues and will attempt a repair if it finds any.

 4) If it fails, you can run Startup Repair again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 3: CHKDSK

 CHKDSK, short for “check disk”, aims to check disk and verify system files for any errors.

 1) Boot your device from your installation media and go to**Command Prompt** .

 2) Type the following command line and press**Enter** .

chkdsk C: /f /r /x

* **C:** is the letter of the drive where Windows is installed, you can change it if you’ve installed it on another drive.
* **r** directs to find out the error.
* **x** symbolizes the volume that requires scanning.

3) CHKDSK will manage to fix the problems it finds.

4) Close Command Prompt and restart your device to check if the Windows system can load up again.

### Fix 4: System File Checker

 The error 0xc0000098 can also be caused by missing or corrupt system files. System File Checker (SFC) can help you to restore the missing files and repair any problematic ones.

 1) Again go to**Command Prompt** and type the following command and hit**Enter** .

sfc /scannow /offbootdir=c:\ /offwindir=c:\windows

 This command is slightly different from_**sfc /scannow**_ because this is done with a different installation of Windows (**_/offwindir=c:\\windows_** ) on a different drive (_**/offbootdir=c**_ :).

2) Wait for the scan to finish.

### Fix 5: Use a Windows Fortect Tool

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  Windows repair works by replacing system files automatically. It’s like a clean Windows reinstallation in one hour, without losing any programs, settings, or user data. It can fix the 0xc0000098 error code without a computer restart.

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.

 2) Open Fortect and it might take 3\~5 minutes to analyze your PC. Sit back and grab a cup of coffee. Once complete, you will be able to review the detailed scan report for free.

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)

 3) Click**Start Repair** to restore any corrupted files. You will need to purchase a license key to do so and don’t have pressure on it, for it has a 60-day money-back guarantee.

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Enter your license key and the restoration will begin automatically. Reimage handles all.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 6: Perform a clean install of Windows

 If neither of the fixes above did the trick, then you need to do a clean reinstall of Windows to fix your issues and return your PC to a cleaner state.

 1) Boot from your installation media and select**Next** .

 2) Select**Install now** \> check the**I accept** box >**Next** \> select**Custom: Install Windows only (advanced)** .

 3) If multiple disks are displayed, you’ll only need to delete all partitions from the disk where you want to install Windows.

 3) Highlight each drive/partition in the list and select**Delete** . When the Windows Setup notification appears, select**OK** .

 4) Do this for every drive in the list except the one that says**Unallocated Space** . When you’re finished, only**Drive 0 Unallocated Space** should remain.

 5) Select**Next** .

 6) The Windows setup screen requests you choose your language/keyboard layout, remove the external storage drive from your device, and select**OK** . This will restart your device.

 7) Your device should be working properly now.

#### Pro tip: Update the essential drivers

 If the new setup fails to add some essential drivers correctly after a clean installation, such as for the network adapter and graphics card, you’ll need to update the driver whether through**Windows Update** or**Device Manager** .

##### 1\. Check for updates

![](https://images.drivereasy.com/wp-content/uploads/2020/01/Windows-update.jpg)

 Type**Check for updates** in the Search box and press**Enter** .

##### 2\. Device Manager

![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-driver.jpg)

 In Device Manager, right-click your device and select**Update Driver** then choose search automatically.

##### 3\. Download from the manufacturer’s website

 Although Windows does a pretty good job detecting and installing most device drivers automatically, it can’t always update all of your drivers because of the OEM (Original equipment manufacturer) restrictions. In that case, you need to go to the manufacturer’s website for new drivers and install it manually.

##### 4\. Update all of your drivers automatically (Recommended)

 If you don’t have the time, patience or computer skills to update these drivers manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 **All the drivers in Driver Easy come straight from the manufacturer.**

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Click**Update All** to automatically download and install the correct version of all essential and peripheral drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click_Update All_ . You get**full support** and a no-questions-asked**30-day money back guarantee** .)

![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers.jpg)

 Note: You can do it for free if you like, but it’s partly manual.

 If you need assistance or have any questions, please contact Driver Easy’s support team at [**support@drivereasy.com**](https://vapordna.pxf.io/vnbxna) .

 Good to go? Hopefully, one of the fixes above did the trick for you. Feel free to leave us a comment if you have further questions or suggestions.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-a-list-nintendo-switch-fighter-titles-max-156/"><u>[New] In 2024, A-List Nintendo Switch Fighter Titles (Max 156)</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-how-to-use-video-titles-and-youtube-tags-for-more-views/"><u>[New] In 2024, How to Use Video Titles and YouTube Tags for More Views?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2023diy2/"><u>2023年最新指紋識別裝置DIY尺寸大修改：從2英吋照片到最佳身分證攝影技巧</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp4mp3/"><u>優化發現：MP4到MP3自由變換技術 - 快速無需付錢！</u></a></li>
<li><a href="https://win-howtos.techidaily.com/archiviazione-digitale-gratuita-cambia-i-tuoi-dati-da-ram-a-mov-su-movavi-online/"><u>Archiviazione Digitale Gratuita: Cambia I Tuoi Dati Da RAM a MOV Su Movavi Online</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/astro-clear-sweep-your-essential-guide-to-removing-windows-file-clutter/"><u>Astro Clear Sweep: Your Essential Guide to Removing Windows File Clutter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convert-your-audio-files-flac-to-webm-for-free-with-movavis-simple-tool/"><u>Convert Your Audio Files: FLAC to WebM for Free with Movavi's Simple Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-mkv-to-avi-converter-with-movavi-video-editor/"><u>Efficient MKV to AVI Converter with Movavi Video Editor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-converter-convert-mov-files-to-3gp-format-with-movavi/"><u>FREE Online Converter: Convert MOV Files to 3GP Format with Movavi</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-hevc-h-265-video-on-xiaomi-redmi-13c-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How to play HEVC H.265 video on Xiaomi Redmi 13C?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/impostor-chatgpt-chrome-add-on-exposes-facebook-accounts/"><u>Impostor ChatGPT Chrome Add-On Exposes Facebook Accounts</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solutions-for-resolving-chatgpt-moderation-errors/"><u>Solutions for Resolving ChatGPT 'Moderation Errors'</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/streamline-your-media-library-convert-vob-to-wma-on-the-web-at-no-cost-moveavi-solutions/"><u>Streamline Your Media Library: Convert VOB to WMA on the Web at No Cost - Moveavi Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-huawei-p60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-17-pc-bildprogrammer-i-verden-movavi-screen-capture-tools/"><u>Top 17 PC Bildprogrammer I Verden - Movavi Screen Capture Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/zacatejte-konvertovat-videoze-z-youtube-do-mp3-13-napadnejsich-programu-movavi/"><u>Začátejte Konvertovat Vídeoze Z YouTube Do MP3 - 13 Nápadnejších Programů Movavi</u></a></li>
</ul></div>

