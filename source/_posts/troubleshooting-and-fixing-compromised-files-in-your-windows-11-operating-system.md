---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2024-12-26T01:58:37.663Z
updated: 2024-12-27T20:14:19.858Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
excerpt: This Article Describes Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
thumbnail: https://thmb.techidaily.com/a7dd9142f70f2e1fb0515e1b92c73345b73af0eebd789d21de62a66b954929b6.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afe2f523108.jpg)

When you met boot error with Windows 10, you hoped that automatic repair will help fix the problem. But it got you more troubles. The worse thing is that repair process seems never end. Then what to do to end the loop? Read on to find the solutions.  

 Since the Windows keeps restarting, it is impossible for you access Advanced Options, that you can fix the problem there. In this case, you can boot from a USB or DVD.
  
 To use the solutions below, you’ll need to prepare a bootable USB or a DVD with an installation file on it. If you are not sure how to create a bootable USB, refer [How to Burn Windows 10 ISO to USB](https://tools.techidaily.com/drivereasy/download/) . Note you need to do this on another computer.
  
 **First start your PC from the USB or DVD and open Command Prompt**
  
 1.  
  
 For USB bootable way:  
  
 Plug the USB the computer that has the problem.After you power on the computer, press function key, usually F2 or F12, to enter boot menu. The key to enter boot menu depends on the computers that you are using. You can go to the PC manufacturer’s website to check for it.
  
 For DVD bootable way:  
  
 Insert the DVD to the computer that has the problem. Wait until you see the message “Press any key to boot from CD or DVD”. Press any key to continue. If you don’t see this message, you probably have to change the boot order in the BIOS (Basic Input/Output System) .  
  
 Learn[How to Boot from a USB Drive, DVD or CD](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. When you go to the setup screen, select the Language that you wish to use.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
 2\. Type **bcdedit /set GUID recoveryenabled No** and hit**Enter** . Replace GUID with the number that you noted in last step. (For example, if the number is 7ce0dd34-d277-11e4-8263-68f7286346fb, the full command will be “bcdedit /set 7ce0dd34-d277-11e4-8263-68f7286346fb recoveryenabled No”)  
  
 3\. Reboot your PC and Windows should start without no problem.

 **Solution 3: Remove Your RAM**
  
 The loop error can be fixed by simply removing the RAM. You can try this solution. Before removing, remember to turn off the PC.If you have more than one RAM, remove one at a time then start your PC without it. You might need to do this a few times until you test every RAM module.

 After entering Windows, run a disk check to check if there is any problem with the disk, and run a system file check to check if some system files are corrupted. If neither of them work, try to restore Windows registry.  
  
**Run a disk check**
  
 Follow steps below:  
  
 1\. Open[**Command Prompt**](https://tools.techidaily.com/drivereasy/download/) as an administrator.
  
 2\. Type**chkdsk /f /r** and hit**Enter** . You need to wait a while until the process completes.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affee4bc504.png)
  
 Hope the solutions here will help you fix the Windows 10 Automatic Repair loop error.

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
<li><a href="https://article-files.techidaily.com/new-essential-devices-for-capturing-journeys/"><u>[New] Essential Devices for Capturing Journeys</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-removing-discord-servers-step-by-step/"><u>[Updated] 2024 Approved Removing Discord Servers Step-by-Step</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-crafting-compelling-conversations-essential-expressions/"><u>[Updated] Crafting Compelling Conversations Essential Expressions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-finest-racing-games-roundup-top-5/"><u>[Updated] Finest Racing Games Roundup (Top 5)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726026759413-youtube/"><u>「楽曲付与の秘訣：パソコンを使ってYouTubeショート動画音効を手軽に」</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726029337508-windows7/"><u>「長時間にわたり Windows7 画面動画化のステップ」</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726030308789-mp4ts/"><u>【もらえないでしょうか、お手数をおかけします】MP4ビデオをTSフォーマットに無料変換する詳細ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-how-to-troubleshoot-and-resolve-issues-with-non-playable-instagram-video-content/"><u>1. How to Troubleshoot and Resolve Issues with Non-Playable Instagram Video Content</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-snowball-rally-highlights-from-the-beijing-games-2022/"><u>2024 Approved Snowball Rally Highlights From the Beijing Games, 2022</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726026818275-4/"><u>4人気の無料ウィンドウズ端末図像キャプチャツールをご紹介</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028674552-pc/"><u>容易な手順：PCやスマホを使って動画に画像・写真を追加するテクニック</u></a></li>
<li><a href="https://tech-hub.techidaily.com/gemini-vs-chatgpt-can-googles-newest-ai-challenge-the-leader-in-conversation/"><u>Gemini Vs. ChatGPT: Can Google's Newest AI Challenge the Leader in Conversation?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-from-iphone-7-by-drfone-ios/"><u>How to Bypass iCloud Lock from iPhone 7</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-best-mc-housing-plans-for-vibrant-villages/"><u>In 2024, Best MC Housing Plans for Vibrant Villages</u></a></li>
<li><a href="https://games-able.techidaily.com/mobile-fun-or-frustration-analyzing-game-pros-and-cons/"><u>Mobile Fun or Frustration? Analyzing Game Pros & Cons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726030570507-pc/"><u>PCやスマートフォンでプロジェクト・アッシュへの撮影方法</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-management-on-windows-1110/"><u>Sticky Notes Management on Windows 11/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726027860310-vimeo/"><u>Vimeoビデオのチャンブラダウンロードテクニック：手っ取り早いフリーガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726029005974-dvd2/"><u>リージョンコードが違うDVD「コード2」での問題と修正手段：見落としたポイント</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

