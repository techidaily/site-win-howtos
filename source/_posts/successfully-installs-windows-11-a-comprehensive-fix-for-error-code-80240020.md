---
title: "Successfully Installs Windows 11: A Comprehensive Fix for Error Code 80240020"
date: 2024-09-12T17:45:44.276Z
updated: 2024-09-17T21:53:00.700Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Successfully Installs Windows 11: A Comprehensive Fix for Error Code 80240020"
excerpt: "This Article Describes Successfully Installs Windows 11: A Comprehensive Fix for Error Code 80240020"
thumbnail: https://thmb.techidaily.com/0c851aeff0505f93ab9210c28e47cf3dc2d61368996282399757ef6f40d2d48e.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://fox-hovers.techidaily.com/new-enrich-your-photographic-expression-techniques-for-inserting-text-onto-images-for-2024/"><u>[New] Enrich Your Photographic Expression Techniques for Inserting Text Onto Images for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-ultimate-10-audio-elevators-on-computersmobile/"><u>[Updated] 2024 Approved Ultimate 10 Audio Elevators on Computers/Mobile</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-viral-video-evolution-youtubes-favorites/"><u>[Updated] Viral Video Evolution YouTube's Favorites</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-instructions-to-deliver-gaming-joy-with-a-steam-gift-card/"><u>Easy Instructions to Deliver Gaming Joy with a Steam Gift Card</u></a></li>
<li><a href="https://tech-hub.techidaily.com/elevate-your-tech-game-for-free-harness-the-power-of-gpt-4-turbo-via-copilot/"><u>Elevate Your Tech Game for Free – Harness the Power of GPT-4 Turbo via Copilot</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-the-issue-of-steam-games-failing-to-start-on-windows-11/"><u>Fixing the Issue of Steam Games Failing to Start on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/most-efficient-dvd-to-mp4-software-for-windows-users/"><u>Most Efficient DVD to MP4 Software for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp4-aac-4/"><u>MP4 形式から AAC への自由なコンバーター4つ、あなたに最適なもの選びましょう!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-networked-video-streaming-with-vlc/"><u>Navigating Networked Video Streaming with VLC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pc2024ts/"><u>PC上にて2024年版TSファイルの再生法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seamless-conversion-of-videos-into-mp3-format-a-step-by-step-guide/"><u>Seamless Conversion of Videos Into MP3 Format: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seamlessly-change-your-pictures-to-sound-a-step-by-step-guide-for-mp3-creation-from-imgs/"><u>Seamlessly Change Your Pictures to Sound: A Step-by-Step Guide for MP3 Creation From IMGs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-voice-recording-on-windows-11-pcs/"><u>Step-by-Step Guide to Voice Recording on Windows 11 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-capturing-and-saving-twitter-video-clips-everywhere/"><u>Step-by-Step Tutorial: Capturing and Saving Twitter Video Clips Everywhere</u></a></li>
<li><a href="https://tech-haven.techidaily.com/synergizing-storytelling-with-ai-transforming-dandd-through-chatgpt-and-dall-e/"><u>Synergizing Storytelling with AI: Transforming D&D Through ChatGPT & DALL-E</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-audiophiles-guide-selecting-the-best-soundtracks-that-complement-visual-storytelling-for-2024/"><u>Updated Audiophiles Guide Selecting the Best Soundtracks that Complement Visual Storytelling for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

