---
title: Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution
date: 2024-11-15T20:45:08.084Z
updated: 2024-11-18T17:28:40.705Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution
excerpt: This Article Describes Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution
thumbnail: https://thmb.techidaily.com/a9744aafdac80a7e4f169749236f6a9a3444533f48662a5ae5f051ec41bdae27.jpg
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
<li><a href="https://win-howtos.techidaily.com/dragon-ball-fighterz-successfully-overcoming-network-setup-errors/"><u>Dragon Ball FighterZ - Successfully Overcoming Network Setup Errors!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-the-problem-of-unavailable-specified-modules/"><u>Expert Tips for Repairing the Problem of Unavailable Specified Modules</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-corsair-k70-mouse-up-and-running-with-fresh-driver-downloads/"><u>Get Your Corsair K70 Mouse Up and Running with Fresh Driver Downloads</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ften-can-creators-expect-to-be-paid-by-youtube-for-2024/"><u>How Often Can Creators Expect to Be Paid by YouTube for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-fix-overcoming-time-sensitive-response-delays-service-error-1053/"><u>Immediate Fix: Overcoming Time-Sensitive Response Delays (Service Error 1053)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-comprehensive-list-of-budget-friendly-online-editors/"><u>In 2024, Comprehensive List of Budget-Friendly Online Editors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-future-ready-data-retention-selecting-excellent-cloud-providers/"><u>In 2024, Future-Ready Data Retention Selecting Excellent Cloud Providers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-top-asmrists-aiding-the-nighttime-ritual/"><u>In 2024, Top ASMRists Aiding the Nighttime Ritual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/night-light-not-functioning-heres-what-to-do-for-windows-11-systems/"><u>Night Light Not Functioning? Here's What to Do for Windows 11 Systems</u></a></li>
<li><a href="https://win-fantastic.techidaily.com/probleme-de-chargement-du-systeme-dexploitation-windows-10-resolu/"><u>Problème De Chargement Du Système D'exploitation Windows 10 Résolu</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-and-simple-guide-to-getting-those-crucial-sandisk-ssd-drivers-installed/"><u>Quick and Simple Guide to Getting Those Crucial Sandisk SSD Drivers Installed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-driver-failed-fixes-and-steps-for-setting-user-preferences-correctly/"><u>Resolving 'Driver Failed' - Fixes and Steps for Setting User Preferences Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-instructions-to-correct-the-openal32dll-not-detected-problem/"><u>Step-by-Step Instructions to Correct the 'openal32.dll' Not Detected Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-role-of-msda80dll-in-windows-systems-keep-or-remove/"><u>The Role of MSDA80.DLL in Windows Systems - Keep or Remove?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-apps-and-online-tools-to-track-tecno-spark-10-pro-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Tecno Spark 10 Pro Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-recurring-crashes-in-microsoft-flight-simulator-2020/"><u>Troubleshooting Recurring Crashes in Microsoft Flight Simulator 2020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-step-by-step-troubleshooting-for-no-video-signal-monitor-issue/"><u>Ultimate Guide: Step-by-Step Troubleshooting for 'No Video Signal' Monitor Issue</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144273/7443" target="_top" id="2144273">
  <img src="//a.impactradius-go.com/display-ad/7443-2144273" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144273/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

