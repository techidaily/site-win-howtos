---
title: Troubleshooting High GPU Usage From Desktop Window Manager in WINDOWS 10 and 11 - A Step-by-Step Guide
date: 2024-11-24T21:32:03.901Z
updated: 2024-11-28T07:56:11.322Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting High GPU Usage From Desktop Window Manager in WINDOWS 10 and 11 - A Step-by-Step Guide
excerpt: This Article Describes Troubleshooting High GPU Usage From Desktop Window Manager in WINDOWS 10 and 11 - A Step-by-Step Guide
thumbnail: https://thmb.techidaily.com/4824b5bc1ec47ceadb929bb6b68e8c9454196f2de65b71eab7da2ab3371e3a0f.png
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-best-7-live-streaming-apps-to-amplify-your-youtube-presence-on-iphone-and-android/"><u>[New] 2024 Approved Best 7 LIVE Streaming Apps to Amplify Your YouTube Presence on iPhone and Android</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-capture-and-share-leading-the-charge-with-androids-best-8-free-tools-for-2024/"><u>[New] Capture & Share - Leading the Charge with Android's Best 8 Free Tools for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-how-to-create-a-live-stream-online/"><u>[Updated] In 2024, How to Create a Live Stream Online</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-turn-off-youtube-sneak-peek-embrace-uninterrupted-watching/"><u>[Updated] In 2024, Turn Off YouTube Sneak Peek, Embrace Uninterrupted Watching</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-vivo-y36-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Vivo Y36 without App | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-bridging-platforms-instagram-and-tik-tok-synergy-manual/"><u>In 2024, Bridging Platforms Instagram & Tik Tok Synergy Manual</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-oppo-a78-5g-and-browser-drfone-by-drfone-virtual-android/"><u>In 2024, Prevent Cross-Site Tracking on Oppo A78 5G and Browser | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-sluggish-closure-in-windows-10-operating-system/"><u>Resolved: Fixing Sluggish Closure in Windows 10 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-fixing-pasting-errors-on-your-windows-11-pc/"><u>Step-by-Step Solution for Fixing Pasting Errors on Your Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-commence-quickly-open-windows-and-sticky-notes/"><u>Streamlined Commence: Quickly Open Windows and Sticky Notes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-loading-screens-on-valorant-solutions-and-tips/"><u>Troubleshooting Persistent Loading Screens on VALORANT: Solutions and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-your-dell-webcam-fails-on-a-windows-pc/"><u>Troubleshooting Steps When Your Dell Webcam Fails on a Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-fixing-silent-streams-on-netflix-instantly/"><u>Ultimate Guide: Fixing Silent Streams on Netflix Instantly</u></a></li>
<li><a href="https://buynow-help.techidaily.com/ultimate-review-of-twelve-souths-bookbook-v2-for-macbook-smart-and-stylish-protection/"><u>Ultimate Review of Twelve South's BookBook V2 for MacBook: Smart & Stylish Protection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winapi-deficit-microsoft-runtime-layer-1/"><u>WinAPI Deficit: Microsoft Runtime Layer 1</u></a></li>
</ul></div>

