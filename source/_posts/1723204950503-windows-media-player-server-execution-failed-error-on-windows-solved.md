---
title: Windows Media Player “Server Execution Failed” Error on Windows [Solved]
date: 2024-11-12T23:46:03.194Z
updated: 2024-11-19T01:20:50.035Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows Media Player “Server Execution Failed” Error on Windows [Solved]
excerpt: This Article Describes Windows Media Player “Server Execution Failed” Error on Windows [Solved]
thumbnail: https://thmb.techidaily.com/97473d93769b74152c0b0b04df270598f5aded17925dea70fd12d869a1bbc744.jpg
---

## How to Overcome Unexpected Shutdown (Error 1067) on Your Windows PC - Now Solved

 Windows background services enable Windows features function properly. If some errors happen to services, you will face trouble then. Here in this article, we will be telling you how to fix one of the errors occurring to Windows services — **Error 1067: The process terminated unexpectedly** . Follow the tried-and-true solution below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Step 1

 On you keyboard, press**Windows** key +**R** key together to open Run box.  
 Type**regedit** in the box and hit**Enter** to open Registry Editor window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/2-1.png)

## Step 2

 Click **Yes**  when prompted by UAC (User Account Control).

![](https://images.drivereasy.com/wp-content/uploads/2017/06/3-2.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Step 3\

 On Registry Editor window, expand **HKEY\_LOCAL\_MACHINE**  \> **SYSTEM**  \> **CurrentControlSet**  \> **Services** .

![](https://images.drivereasy.com/wp-content/uploads/2017/06/4-1.png)

## **Step 4.**

 Find and**right-click** on your service with error 1067 under Services dialog.  
 Then choose**Export** .  
 Choose a place to save it on the pop-up window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/5-1.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Step 5.**

 Back on Registry Editor window,**right-click** on the same service.  
 This time choose**Delete** .  
 Then close the window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/6-2.png)

## **Step 6.**

 Type**cmd** in the search box.  
 Right-click on**Command Prompt** to choose**Run as administrator** .

![](https://www.drivereasy.com/wp-content/uploads/2023/12/win11-cmd-Run-as-administrator.jpg)

## **Step 7.**

 Click **Yes**  when prompted by UAC.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/10-1.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Step 8.**

 Type**sfc /scannow** in the pop-up window.  
 Press**Enter** to run it.  
 Wait till verification**100%** complete.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/11-1.jpg)

## **Step 9.**

 Close the window and**restart** your computer.  
 Then find your service file saved at Step 4.  
 Right-click on it to choose**Merge** .  
 Click **Yes**  when prompted by UAC.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/7-1.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Step 10.**

 Open a Run box to type **services.msc**  in it and press **Enter**  to open Services window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/8.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Step 11.**

 On Services window, find and right-click on your service.  
 Then click**Start** and close the window.  
 See if the error still exists.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/9.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

That’s it. Hope it did help you.

For any confusion, please feel free to leave your comment below, thanks.

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-a-kinemaster-editors-roadmap-for-flawless-transitions/"><u>[New] 2024 Approved A Kinemaster Editor's Roadmap for Flawless Transitions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-ace-your-green-screen-videos-must-know-secrets/"><u>[Updated] 2024 Approved Ace Your Green Screen Videos Must-Know Secrets</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-youtubes-copyright-rules-simplified-a-non-legal-guide/"><u>[Updated] In 2024, YouTube's Copyright Rules Simplified A Non-Legal Guide</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-nokia-g42-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-overview-of-the-anker-roav-dash-cam-c1-your-ideal-road-companion/"><u>Comprehensive Overview of the Anker Roav Dash Cam C1 - Your Ideal Road Companion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-strategies-to-repair-the-critical-system-files-and-tackle-error-0xc00aturate-your-pc/"><u>Comprehensive Strategies to Repair the Critical System Files and Tackle Error 0Xc00aturate Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-troubleshooting-windows-network-issue-error-0x800704cf/"><u>Effective Fixes for Troubleshooting WINDOWS Network Issue (Error 0X800704CF)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensuring-smooth-mousepad-functionality-in-all-windows-systems-tips-and-tricks-for-win-1087-users/"><u>Ensuring Smooth Mousepad Functionality in All Windows Systems: Tips and Tricks for Win 10/8/7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-11-0x800705b4-update-error-a-comprehensive-guide/"><u>Fixing the Windows 11 0X800705b4 Update Error: A Comprehensive Guide</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/free-online-converter-change-pdfs-into-mp3-audio-files-with-ease/"><u>Free Online Converter: Change PDFs Into MP3 Audio Files with Ease</u></a></li>
<li><a href="https://some-guidance.techidaily.com/guia-eficaz-para-realizar-copias-de-seguridad-en-formato-dvd-y-iso-con-winx-dvd-copy/"><u>Guía Eficaz Para Realizar Copias De Seguridad en Formato DVD Y ISO Con WinX DVD Copy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-determine-if-system-configurations-are-controlled-by-admin-in-windows/"><u>How to Determine If System Configurations Are Controlled by Admin in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-tecno-pova-5-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Tecno Pova 5 Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-fixing-problems-with-windows-update-strategies-and-techniques/"><u>Master The Art Of Fixing Problems With Windows Update: Strategies And Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/optimal-visual-snatchers-for-videos-for-2024/"><u>Optimal Visual Snatchers for Videos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-function-key-problems-effective-strategies-and-tips-unveiled/"><u>Overcoming Function Key Problems: Effective Strategies and Tips Unveiled</u></a></li>
</ul></div>

