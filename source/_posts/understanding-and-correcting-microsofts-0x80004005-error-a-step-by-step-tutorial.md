---
title: "Understanding and Correcting Microsoft's 0X80004005 Error: A Step-by-Step Tutorial"
date: 2025-02-01T14:13:48.767Z
updated: 2025-02-07T01:24:47.833Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Understanding and Correcting Microsoft's 0X80004005 Error: A Step-by-Step Tutorial"
excerpt: "This Article Describes Understanding and Correcting Microsoft's 0X80004005 Error: A Step-by-Step Tutorial"
thumbnail: https://thmb.techidaily.com/d3c14a87ffc38827c725ed8de3ccbe916ddb5eb1ee9eb3884a315921c0899b5d.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  
5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-exploring-how-youtube-picks-most-engaging-comments/"><u>[New] In 2024, Exploring How YouTube Picks Most Engaging Comments</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-hdr-reality-check-does-aurora-meet-expectations/"><u>[New] In 2024, HDR Reality Check Does Aurora Meet Expectations?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/affordable-quality-and-convenience-combined-exploring-the-tp-link-tapo-s505-smart-wi-fi-light-switch/"><u>Affordable Quality and Convenience Combined - Exploring the TP-Link Tapo S505 Smart Wi-Fi Light Switch</u></a></li>
<li><a href="https://win-top.techidaily.com/1728473291038-aomei-backupper/"><u>AOMEI Backupper製品概要と関連用語解説</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/combining-youtube-and-imovie-for-professional-results/"><u>Combining YouTube and iMovie for Professional Results</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-a-non-functional-backspace-button-on-your-computer/"><u>How to Repair a Non-Functional Backspace Button on Your Computer</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-xiaomi-redmi-note-13-pro-5g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Xiaomi Redmi Note 13 Pro 5G?</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/1724766787089-iphoneiso/"><u>IPhone用「ISOファイルの簡単な入力と再生方法」</u></a></li>
<li><a href="https://win-howtos.techidaily.com/library-loader-l1-1-not-found-in-system-files/"><u>Library Loader L1-1 Not Found in System Files</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/tetap-desimalan-pintasan-dari-komputer-desktop-pelaksanaa-6-utama/"><u>Tetap Desimalan Pintasan Dari Komputer Desktop | Pelaksanaa 6 Utama</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-werfaultexe-problems-swiftly-expert-tips-inside/"><u>Troubleshoot and Fix werFault.exe Problems Swiftly – Expert Tips Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-hp-laptops-webcam-issue-on-windows-11-a-step-by-step-guide/"><u>Troubleshooting Your HP Laptop's Webcam Issue on Windows 11: A Step-by-Step Guide</u></a></li>
</ul></div>

