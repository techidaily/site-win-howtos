---
title: "USB Troubleshooting in Windows 11: Fixing Unrecognized Devices and Failed Port Resets"
date: 2024-10-03T00:53:54.951Z
updated: 2024-10-04T13:26:44.425Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes USB Troubleshooting in Windows 11: Fixing Unrecognized Devices and Failed Port Resets"
excerpt: "This Article Describes USB Troubleshooting in Windows 11: Fixing Unrecognized Devices and Failed Port Resets"
thumbnail: https://thmb.techidaily.com/5f93c49b1c440b80d1268f9b261207858efb549976695493b8cd986466735cf6.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959707/19272" target="_top" id="1959707">
  <img src="//a.impactradius-go.com/display-ad/19272-1959707" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959707/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-ringtone-repository-best-sources-online/"><u>[Updated] In 2024, Ringtone Repository Best Sources Online</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-maximizing-harvests-with-ideal-valheim-seeds/"><u>[Updated] Maximizing Harvests with Ideal Valheim Seeds</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-oppo-find-x6-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Oppo Find X6 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-understanding-huawei-p10-its-advantages-in-mobile-connectivity/"><u>2024 Approved Understanding Huawei P10 Its Advantages in Mobile Connectivity</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1726030073986-mp4/"><u>画像キャプチャーデータをMP4に変換する方法：詳しいガイド付き</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convert-opus-files-to-mp3-for-free-with-movavis-web-based-converter-service/"><u>Convert OPUS Files to MP3 for Free with Movavi's Web-Based Converter Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/criar-arquivos-em-formato-ogg-a-partir-de-mov-gratuitamente-no-convidativo-site-movavi-um-guia-facil/"><u>Criar Arquivos Em Formato OGG a Partir De MOV Gratuitamente No Convidativo Site Movavi – Um Guia Fácil!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decouvrez-les-12-meilleures-applications-denregistrement-voip-pour-skype-sous-mac-selectionne-par-movavi/"><u>Découvrez Les 12 Meilleures Applications D'enregistrement VoIP Pour Skype Sous Mac, Sélectionné Par Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/drie-griffelijke-strategies-voor-laten-beheer-apparaatstjes-mobilhulpmiddelen-of-computern-inzake-podcast-downloads-naar-personalcomputermobiele-applicaties16/"><u>Drie Griffelijke Strategies Voor Laten Beheer Apparaatstjes, Mobilhulpmiddelen Of Computern Inzake Podcast-Downloads Naar Personalcomputer/Mobiele Applicaties</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-realme-11-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/google-hangouts-ingangstappen-6-kostenloze-methoden-via-movavi/"><u>Google Hangouts Ingangstappen: 6 Kostenloze Methoden via Movavi</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-6-plus-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-pro-passcode-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 Pro Passcode without Computer?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-10-apps-for-free-photo-editing-settembre-2024/"><u>Top 10 Apps for Free Photo Editing - Settembre 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726223452341-mka-mp3/"><u>무료 MKA MP3 변환 - 컴퓨터, 스마트폰에서 사용하는 최고의 툴</u></a></li>
</ul></div>

