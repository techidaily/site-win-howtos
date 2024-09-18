---
title: Troubleshooting PCs Freezing During Windows Setup Process
date: 2024-09-12T17:11:48.021Z
updated: 2024-09-17T20:57:53.271Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting PCs Freezing During Windows Setup Process
excerpt: This Article Describes Troubleshooting PCs Freezing During Windows Setup Process
thumbnail: https://thmb.techidaily.com/128936f1237a7dae7d947e202ae29738fcba18f1e1925b63e660146e08554eaf.jpg
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
  

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

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
<li><a href="https://eaxpv-info.techidaily.com/new-3-step-formula-how-to-check-youtube-income-for-2024/"><u>[New][3-Step Formula] How To Check YouTube Income for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-free-to-paid-the-transition-to-youtubes-elite-service/"><u>[Updated] In 2024, From Free to Paid The Transition to YouTube's Elite Service</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-top-7-fps-experiences-of-the-decade-for-2024/"><u>[Updated] Top 7 FPS Experiences of the Decade for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/access-all-english-movies-for-free-with-simple-steps-on-youtube-and-safe-downloads/"><u>Access All English Movies for Free with Simple Steps on YouTube and Safe Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/appleiphoneavi3/"><u>Appleスマホで楽しむ「iPhone」AVIファイルの魅力!おすすめアプリベスト3ピックアップ</u></a></li>
<li><a href="https://win-howtos.techidaily.com/celebrate-hobbit-day-with-free-online-screening-the-desolation-of-smaug/"><u>Celebrate Hobbit Day with Free Online Screening - The Desolation of Smaug</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-editors-treasure-trove-curated-list-of-iconic-80s-vhs-hacks-for-editing/"><u>In 2024, The Editor's Treasure Trove Curated List of Iconic 80S VHS Hacks for Editing</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/pioneering-water-dynamics-video-games-roundup-for-2024/"><u>Pioneering Water Dynamics Video Games Roundup for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-samsung-galaxy-f34-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Samsung Galaxy F34 5G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-full-potential-with-network-traffic-insight-via-win11s-netstat/"><u>Unlock Your Full Potential with Network Traffic Insight via Win11's Netstat</u></a></li>
<li><a href="https://techtrends.techidaily.com/winxvideo-ai-mobile-app-gratis-descargar-para-android-e-ios/"><u>Winxvideo AI Mobile App Gratis Descargar Para Android E iOS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726030248120-youtube-3/"><u>YouTubeで動画音量強化レシピ ベスト3</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028110366-5/"><u>スピットライフ無料音楽ダウンロード！5つの最優秀録音ソフトブックメーカー</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028239801-pc/"><u>パーソナライズドデスクのためのPCプログラム：動的な壁紙設定ツール「無料・有料」選び方ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726027833388-powerdirector/"><u>ビデオの音量調整:PowerDirectorで見つけた効果的なテクニック</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

