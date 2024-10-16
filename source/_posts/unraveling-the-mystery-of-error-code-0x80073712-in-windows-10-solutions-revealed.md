---
title: Unraveling the Mystery of Error Code 0X80073712 in Windows 10 - Solutions Revealed
date: 2024-10-13T02:10:31.615Z
updated: 2024-10-15T23:07:52.886Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Unraveling the Mystery of Error Code 0X80073712 in Windows 10 - Solutions Revealed
excerpt: This Article Describes Unraveling the Mystery of Error Code 0X80073712 in Windows 10 - Solutions Revealed
thumbnail: https://thmb.techidaily.com/3a57b1ddb74892f92e7ea8db98be1fa90b1375e9f535e64688bd677d4ca59d83.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://visual-screen-recording.techidaily.com/new-is-there-a-superior-cameras-marketplace-in-2024/"><u>[New] Is There a Superior Cameras Marketplace, In 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-unlocking-the-potential-of-time-extension-for-2024/"><u>[New] Unlocking the Potential of Time Extension for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-m34-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy M34 Lock Screen Password?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-from-apple-iphone-15-plus-5-tips-you-must-know-by-drfone-ios/"><u>In 2024, Turning Off Two Factor Authentication From Apple iPhone 15 Plus? 5 Tips You Must Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp3-oma-windowsmac202/"><u>MP3ファイル変換ソフトウェア 「OMA」の推奨版 『Windows/Mac用』に最適化しました202</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp3wma-windows-media-player/"><u>MP3ファイルからWMAへの効率的な変換方法 - Windows Media Playerで使えるテクニック</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mpeg-ts-to-mp4-conversion-premium-quality-techniques-for-windows-11-users-top-11-recommended-methods/"><u>MPEG-TS to MP4 Conversion: Premium Quality Techniques for Windows 11 Users - Top 11 Recommended Methods</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-skype-message-delivery-failures-effective-strategies-for-seamless-communication/"><u>Overcoming Skype Message Delivery Failures: Effective Strategies for Seamless Communication</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ering-the-future-the-art-of-sensory-based-filmmaking-for-2024/"><u>Pioneering the Future The Art of Sensory-Based Filmmaking for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-starfield-sound-glitches-no-more-crackling-or-skipping/"><u>Resolved: Starfield Sound Glitches - No More Crackling or Skipping</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rotating-mov-file-formats-for-windows-and-mac-users-top-5-techniques-explained/"><u>Rotating Mov File Formats for Windows & Mac Users: Top 5 Techniques Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-non-playable-tweets-a-comprehensive-guide/"><u>Solving the Issue of Non-Playable Tweets: A Comprehensive Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-the-economics-of-music-sharing-on-facebook/"><u>Unveiling The Economics of Music Sharing on Facebook</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

