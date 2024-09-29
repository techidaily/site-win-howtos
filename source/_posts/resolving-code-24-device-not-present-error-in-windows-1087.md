---
title: "Resolving Code 24: 'Device Not Present' Error in Windows 10/8/7"
date: 2024-09-05T10:08:35.759Z
updated: 2024-09-06T10:08:35.759Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Code 24: 'Device Not Present' Error in Windows 10/8/7"
excerpt: "This Article Describes Resolving Code 24: 'Device Not Present' Error in Windows 10/8/7"
thumbnail: https://thmb.techidaily.com/ff2e2b344a8396c6bab8264d1025798025a6c7a29bed97ca0ab60000543775d0.jpg
---

## Resolving 'Problem During Restore' Mistake in Windows 10 – Fixed

![](https://images.drivereasy.com/wp-content/uploads/2017/05/1-18.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123474/16836" target="_top" id="2123474">
  <img src="//a.impactradius-go.com/display-ad/16836-2123474" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123474/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This post is going to tell you how to fix **“There was a problem resetting your PC”**  error on your Windows 10\. It may occur when you try to reset your Windows 10 to its default state. Microsoft also noticed such known error. And they have given the following 4 conditions under which your Windows 10 reset may fail. If unluckily you’re also facing such error, please go on with the fixes step by step to solve the error.

**The 4 conditions:**
 ❶ Your PC came with Windows 10 pre-installed, and was not an upgrade from Windows 7 or Windows 8.1.  
 ❷ The PC manufacturer enabled compression to reduce the disk space required for preinstalled applications.  
 ❸ You created a USB recovery drive using the “Create a recovery drive” feature in Windows 10.  
 ❹ You booted the PC to the USB recovery drive and selected, Troubleshoot > Reset this PC > Remove everything.

 **How to fix the error:**
 Click **Close**  icon of the error notification window and go on with the fix below.

**Fix 1.Check your system file**

 1)  

 Click Power button from Start menu.  
 Then while holding **Shift**  key, click **Restart** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/2-17.jpg)

 2)  

 Click **Troubleshoot**  \>**Advanced options**  \> **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/3-18.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3)  

 Select your administrator account and then enter the password if you set one before.  
 Click **Continue**  to go on.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-20.jpg)

![](https://images.drivereasy.com/wp-content/uploads/2017/05/5-14.jpg)

 4)  

 Wait a few seconds for command prompt window poping-up.  
 Then type the following commands in the window and hit **Enter**  after each.  
 **cd %windir%\\system32\\config**
 **ren system system.001**
**ren software software.001**

![](https://images.drivereasy.com/wp-content/uploads/2017/05/6-15.jpg)

 5)  

 After it’s done, close command prompt window.  
 Then it will be back to boot option page.  
 Click **Continue** to boot into your Windows 10.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/7-9.jpg)

 6)  

 Try to reset your Windows 10 now and see if the error has been solved.

**Fix 2\. Recover your PC from USB recovery USB**

 1)  

 Insert an empty USB Flash drive(16GB recommended) into your computer.

 2)  

 Type **recovery drive**  in the search box from Start menu.  
 Then click **Create a recovery drive**  from the top result.  
 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/8-10.jpg)

 3)  

 Click **Next** .  
**Note:**
 Recover your PC from a drive will remove all your files and apps, you can choose to tick on **Back up system files to the recovery drive** in this step to back up.

![](https://images.drivereasy.com/wp-content/uploads/2017/05/10-7.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4)  

 Select your USB drive and click **Next** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/12-2.jpg)

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5)  

 Click **Create** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/13-1.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When it’s done, click **Finish** .

 6)  

 Now reboot your Windows 10.  
 Press the specific key, like **F12** or any other key your PC tells to enter boot option page.  
 Go on to choose to boot from your USB recovery drive.

 7)  

 Click **Recovery from a drive** .

![](https://images.drivereasy.com/wp-content/uploads/2017/05/14-2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Go on to follow the on-screen instructions to complete the reinstalling.

 That’s all there is to it. Hope the solution here can help you fix the error.  
 Any questions please feel free to leave comment below, thanks.

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


