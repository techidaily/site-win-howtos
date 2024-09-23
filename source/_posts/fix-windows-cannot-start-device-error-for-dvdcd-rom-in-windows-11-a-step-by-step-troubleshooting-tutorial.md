---
title: "Fix 'Windows Cannot Start Device' Error for DVD/CD-ROM in Windows 지원(11): A Step-by-Step Troubleshooting Tutorial"
date: 2024-09-15T20:54:47.806Z
updated: 2024-09-22T20:29:00.521Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fix 'Windows Cannot Start Device' Error for DVD/CD-ROM in Windows 지원(11): A Step-by-Step Troubleshooting Tutorial"
excerpt: "This Article Describes Fix 'Windows Cannot Start Device' Error for DVD/CD-ROM in Windows 지원(11): A Step-by-Step Troubleshooting Tutorial"
thumbnail: https://thmb.techidaily.com/95f65ec843e39dc81b80b6ffcbfef45d788958cee2b82fb5803fb90b93482a66.jpg
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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-retrieve-lost-tiktok-videos-after-an-unwanted-reload/"><u>[New] 2024 Approved Retrieve Lost TikTok Videos After an Unwanted Reload</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-integrating-real-time-collaboration-slack-and-filmoras-meeting-guide-for-2024/"><u>[Updated] Integrating Real-Time Collaboration Slack & Filmora's Meeting Guide for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/42024windows11/"><u>4最も効果的な2024年のWindows11画面録画手段</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/5-tutorials-on-how-to-transfer-photos-from-apple-iphone-15-pro-max-to-new-iphone-drfone-by-drfone-transfer-from-ios/"><u>5 Tutorials on How to Transfer Photos From Apple iPhone 15 Pro Max to New iPhone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726030670934-3/"><u>連続して3枚のビデオを効果的に一画面表示するテクニック</u></a></li>
<li><a href="https://discover-dash.techidaily.com/easy-methods-for-embedding-subtitles-into-mkv-files-using-movavi-on-pcmac-systems/"><u>Easy Methods for Embedding Subtitles Into MKV Files Using Movavi on PC/Mac Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-the-steelseries-arctis-pro-microphone-issue-a-comprehensive-guide/"><u>Fixing the SteelSeries Arctis Pro Microphone Issue: A Comprehensive Guide</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/in-2024-top-10-storyboarding-software-freeandpaid/"><u>In 2024, Top 10 Storyboarding Software Free&Paid</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028866954-nhk/"><u>NHKオンデマンドコンテンツを効果的に保存するための手引き</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlocking-the-potential-of-zoom-meetings-for-2024/"><u>Unlocking the Potential of Zoom Meetings for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726029828019-wavmp3/"><u>WAV形式へのMP3ファイル変換手順</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/webcam-mastery-unique-ideas-explored/"><u>Webcam Mastery Unique Ideas Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726030393316-youtube/"><u>YouTube動画のサムネイルアイコンを取得する究極ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726030030122-youtubeiphone/"><u>YouTubeからiPhoneへ: 個人用動画保存とダウンロードの手順</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028427345-pc/"><u>デスクトップPC用マイクレコーディングの基本とは？</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105876/7443" target="_top" id="2105876">
  <img src="//a.impactradius-go.com/display-ad/7443-2105876" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105876/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

