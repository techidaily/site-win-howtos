---
title: "Resolving the 'Video File Unplayable' Mistake: Fixing Error Code 224003"
date: 2024-10-14T22:04:02.393Z
updated: 2024-10-15T22:37:54.269Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the 'Video File Unplayable' Mistake: Fixing Error Code 224003"
excerpt: "This Article Describes Resolving the 'Video File Unplayable' Mistake: Fixing Error Code 224003"
thumbnail: https://thmb.techidaily.com/75e496d7d03af882c809a7273c9e1eb1d9baeae9a3a5a4a6ed566b778061c9ff.png
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-efficiently-using-skypes-screen-share-feature-in-telecommuting/"><u>[New] 2024 Approved Efficiently Using Skype's Screen-Share Feature in Telecommuting</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-explore-the-finest-cost-free-videocalling-platforms-for-2024/"><u>[New] Explore the Finest Cost-Free Videocalling Platforms for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-premier-video-call-alternatives-zooms-rivalry-explained/"><u>[New] In 2024, Premier Video Call Alternatives Zoom's Rivalry Explained</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-streamlining-your-experience-live-cricket-viewing-tips/"><u>[New] In 2024, Streamlining Your Experience Live Cricket Viewing Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-wd-my-passport-ultra-not-detected-in-windows/"><u>[Solved] WD My Passport Ultra Not Detected in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-bend-the-light-homegrown-animated-innovations-for-2024/"><u>[Updated] Bend the Light Homegrown Animated Innovations for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-immersive-inventory-visualization/"><u>[Updated] In 2024, Immersive Inventory Visualization</u></a></li>
<li><a href="https://win-howtos.techidaily.com/case-closed-absence-of-opengl-support-in-drivers/"><u>Case Closed: Absence of OpenGL Support in Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-performance-hiccups-a-guide-to-optimizing-warhammer-on-windows/"><u>Eradicate Performance Hiccups: A Guide to Optimizing Warhammer on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-login-problems-caused-by-user-profile-service-error-in-windows-11/"><u>Fixing Login Problems Caused by User Profile Service Error in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-11s-troublesome-youtube-audio-output-error-for-clear-streaming-experience/"><u>Fixing Windows 11'S Troublesome YouTube Audio Output Error for Clear Streaming Experience</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Realme 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maintain-a-positive-tone-users-are-often-looking-for-solutions-so-use-positive-words-like-guide-or-solutions-that-indicate-you-have-the-answer-theyre-seekin17/"><u>Maintain a Positive Tone: Users Are Often Looking for Solutions, so Use Positive Words Like Guide or Solutions that Indicate You Have the Answer They're Seeking. Avoid Using Negative Connotations in Your Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-it-management-configuring-user-permissions-in-windows-environments/"><u>Mastering IT Management: Configuring User Permissions in Windows Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-new-world-launch-a-step-by-step-solution-for-the-easy-anti-cheat-problem/"><u>Mastering New World Launch: A Step-by-Step Solution for the Easy Anti-Cheat Problem</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/new-data-usage-provisions-explanation/"><u>New Data Usage Provisions Explanation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-how-to-correctly-setup-your-ps4-network-configuration/"><u>Step-by-Step Solution: How to Correctly Setup Your PS4 Network Configuration</u></a></li>
<li><a href="https://blog-min.techidaily.com/the-ultimate-guide-to-16-free-mac-screenshot-applications-ranked/"><u>The Ultimate Guide to 16 Free Mac Screenshot Applications - Ranked!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-rendering-errors-updated-solutions/"><u>Troubleshooting the Rendering Errors - Updated Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

