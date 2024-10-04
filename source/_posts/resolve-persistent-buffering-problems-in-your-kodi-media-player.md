---
title: Resolve Persistent Buffering Problems in Your Kodi Media Player
date: 2024-09-29T01:53:36.102Z
updated: 2024-10-03T18:51:44.100Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolve Persistent Buffering Problems in Your Kodi Media Player
excerpt: This Article Describes Resolve Persistent Buffering Problems in Your Kodi Media Player
thumbnail: https://thmb.techidaily.com/fe3425cd8bd2ff0c1232de1bab83bce21e82181cb81ffb7e2c2a0692c27f7927.png
---

## Resolving Your System's Diagnostics Policy Service Problem Today

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027167/19272" target="_top" id="2027167">
  <img src="//a.impactradius-go.com/display-ad/19272-2027167" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027167/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105877/7443" target="_top" id="2105877">
  <img src="//a.impactradius-go.com/display-ad/7443-2105877" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105877/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://facebook-video-share.techidaily.com/new-cutting-edge-tools-for-unique-youtube-channel-names-for-2024/"><u>[New] Cutting-Edge Tools for Unique YouTube Channel Names for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-passport-self-portrait-maker-free-access-to-top-quality-images/"><u>[New] Passport Self-Portrait Maker – Free Access to Top Quality Images</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-silencing-your-zoom-meeting-with-ease-a-step-by-step-guide/"><u>1. Silencing Your Zoom Meeting with Ease: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convertissez-votre-fichier-3g2-en-audio-wma-sans-frais-conversion-rapide-et-facile-avec-movavi/"><u>Convertissez Votre Fichier .3G2 en Audio WMA Sans Frais - Conversion Rapide Et Facile Avec Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-conversion-transforming-nsv-files-to-avi-format-with-movavi/"><u>Free Online Conversion: Transforming NSV Files to Avi Format with Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-converter-transform-orf-images-into-jpg-format-with-movavi/"><u>Free Online Converter: Transform ORF Images Into JPG Format with Movavi</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-vivo-y02t-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Vivo Y02T Devices</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-itel-s23plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/illuminating-seamless-transitions-in-song-production-crossfade-for-2024/"><u>Illuminating Seamless Transitions in Song Production (Crossfade) for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-cutting-edge-free-and-easy-top-11-youtube-title-inventors/"><u>In 2024, Cutting-Edge, Free, and Easy Top 11 YouTube Title Inventors</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-windows-unveiled-the-new-era-in-user-experience/"><u>In 2024, Windows Unveiled The New Era in User Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/las-mejores-aplicaciones-de-streaming-de-cine-libres-optimizadas-para-windows-10-8-y-7/"><u>Las Mejores Aplicaciones De Streaming De Cine Libres: Optimizadas Para Windows 10, 8 Y 7</u></a></li>
<li><a href="https://tech-hub.techidaily.com/swift-remedies-for-chatgpt-log-in-errors/"><u>Swift Remedies for ChatGPT Log-In Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-10-ai-image-generators-best-tools-for-creating-stunning-graphics/"><u>Top 10 AI Image Generators: Best Tools for Creating Stunning Graphics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transformez-facilement-votre-fichier-video-m1v-en-mpeg-pour-free-via-le-convertisseur-videoconvert-en-ligne/"><u>Transformez Facilement Votre Fichier Vidéo M1V en MPEG Pour Free via Le Convertisseur VidéoConvert en Ligne</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-motorola-moto-e13-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Motorola Moto E13 Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vlamkunstig-versterken-ogg-onlinegelijke-vrije-gif-converteertool-van-movavi/"><u>Vlamkunstig Versterken Ogg: Onlinegelijke Vrije Gif-Converteertool Van Movavi</u></a></li>
</ul></div>

