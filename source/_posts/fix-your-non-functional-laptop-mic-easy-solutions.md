---
title: "Fix Your Non-Functional Laptop Mic: Easy Solutions"
date: 2024-12-11T21:13:30.271Z
updated: 2024-12-13T20:24:11.182Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fix Your Non-Functional Laptop Mic: Easy Solutions"
excerpt: "This Article Describes Fix Your Non-Functional Laptop Mic: Easy Solutions"
thumbnail: https://thmb.techidaily.com/18c9dd2cba19f0ecf97513cafd5088c9e4acab9c65510cdf2678db2edca6954d.jpg
---

## Innovative Solutions: Stop the Halt on Your Hamachi Connection Now

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap69-1.jpg)

 If you’re running the LogMeIn Hamachi software and you meet the “**Hamachi service stopped** ” error, you’ve come to the right place.  
 Don’t worry, you’re not alone. Fortunately, it’s usually not too hard to fix.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Try these fixes

 There are 5 fixes for you to try. You may not need to try them all, just work your way down until you find the one that works for you.

1. **[Enable the Windows Management Instrumentation (WMI) Service](https://www.drivereasy.com/knowledge/solved-how-to-solve-hamachi-service-stopped-error/#m2)**
2. **[Configure the LogMeIn Hamachi Tunneling Engine](https://tools.techidaily.com/drivereasy/download/)**
3. **[Check your antivirus software](https://tools.techidaily.com/drivereasy/download/)**
4. **[Reinstall LogMeIn Hamachi](https://tools.techidaily.com/drivereasy/download/)**
5. **[Create a startup to automatically restart the Hamachi service](https://tools.techidaily.com/drivereasy/download/)**
6. **[Bonus: Update your drivers by 2 clicks](https://tools.techidaily.com/drivereasy/download/)**

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Method 1: Enable the Windows Management Instrumentation (WMI) Service

 LogMeIn Hamachi is a certain type of application that needs the Windows Management Instrumentation service (WMI)’s help to run properly in the Windows system.  
 Therefore, if WMI was disabled, the Hamachi service stopped error would appear.

 1) On your keyboard, press the**Windows Key** (with Windows logo on it) +**R** together to open the Run box.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap54.jpg)

 3) Right-click on**Windows Management Instrumentation** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap55.jpg)

 4) Click the**Start** button to start it if it’s not running and set the Startup type to**Automatic** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap58.jpg)

 5) Click the**Apply** \>**OK** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap52.jpg)

6) Run Hamachi to check the problem is still there or not.

---

### Method 2: Configure the LogMeIn Hamachi Tunneling Engine

 1) On your keyboard, press the**Windows Key** (with Windows logo on it) +**R** together to open the Run box.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap54-1.jpg)

 3) Right-click on**LogMeIn Hamachi Tunneling Engine** and click the**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap47-1.jpg)

 4) Set the Startup type to**Automatic** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap49.jpg)

 5) Move to**Log On** tab, make sure**Local System account** and**Allow service to interact with desktop** box has been checked. Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap50.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Open the**File Explorer** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap62.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) In the address box, type “C:\\Program Files (x86)\\LogMeIn Hamachi”.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap51.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 8) Right-click on**hamachi-2-ui.exe** and open**Properties** .

 9) Under the**Security** tab, ensure the Users group permissions are set to “Read & execute”. If it’s not, you can click**Edit** to change permissions.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap60.jpg)

 10) Click**OK** to finish settings.

 11) Run Hamachi to check the problem.  

---

### Method 3: Check your antivirus software

 The “Hamachi service stopped” error may be caused by your antivirus software. When Hamachi was blocked by your antivirus software, the error will appear.  
 To solve it, you can change your antivirus software settings to make sure Hamachi won’t be blocked. If you don’t know how to do it, you can consult your antivirus software official customer service.

 There’s another situation that Hamachi isn’t blocked by antivirus software. Hamachi may have a conflict with your antivirus software. Therefore, uninstall the antivirus software and restart your computer can help you solve the error.

 If this resolves the problem, you can install another antivirus software. But if you are fond of the old one, contact the vendor of your antivirus software and ask them for advice.

**IMPORTANT:** Be extra careful in using the Internet after uninstalled your antivirus.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Method 4: Reinstall LogMeIn Hamachi

 The “Hamachi service stopped” error can be caused by inappropriate configuration when you installed Hamachi.  
 You can reinstall the program to solve the problem.

 1) Click the Windows start button (if you hide the search field), type**control panel** in the search box and open the**Control Panel** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap66.jpg)

 2) On the open window, choose to view by**Catalog** , then click**Uninstall a program** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap67-1-1024x593.jpg)

 3) Right-click on**LogMeIn Hamachi** and click**Uninstall** .  
 Follow the on-screen instructions to finish the process.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap68.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Download the program from LogMeln Hamachi official website.

5) Double click the program and follow the on-screen instructions to complete the installation.

6) Run Hamachi to check the problem.

---

### Method 5: Create a startup to automatically restart the Hamachi service

 This method will lead you to create a script that helps you restart the Hamachi service automatically.

 1) Click the Windows start button (if you hide the search field), type**notepad** in the search box and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap70.jpg)

2) Copy and paste below lines into Notepad.

net stop Hamachi2Svc  
net start Hamachi2Svc  
start "C:\Program Files (x86)\LogMeIn Hamachi\hamachi-2-ui.exe"  
exit

 To make it work, you have to make sure you are using the correct path to hamachi-2-ui.exe.

 3) Click**File** and click**Save as** .

 4) Type**HamachiReload.cmd** as a file name.  
 Next, change the**Save as type** into**All Files** .  
 Choose_C:WindowsSystem32_ as the save location and click**Save** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap71.jpg)

 5) On your keyboard, press the**Windows key** (with Windows logo on it) +**R** together to open the Run box.  
 Type**taskschd.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap74.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Click**Create Task** under the Actions menu.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap81.jpg)

 7) Under the**General** tab, set a name for the task.  
 Then go down to Security options to check it’s**Run only when the user is logged on** .  
 Third, change the Configure into**Windows 10** . After that, click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap77.jpg)

 8) Click the**Triggers** tab, and click the**New…** button.

 9) Change the**Begin the task** into**At startup** .  
 Then make sure the**Enabled** box is checked. Finally, click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap82.jpg)

 10) Click the**Actions** tab and click the**New…** button.

 11) Set Action into**Start a program** .  
 Then click Browse and navigate to_C:\\Windows\\System32_ , find**HamachiReload.cmd** and press**Open** .  
 Click**OK** to save changes.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap79.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 12) Click the**Conditions** tab and unchecked everything. Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap80.jpg)

 13) Next time you start your computer, Hamachi will restart the service automatically.

---

## Bonus: Update your drivers by 2 clicks

 In order to improve your VPN work performance, it’s important to keep your network adapter drivers up-to-date.  
 There are two ways you can update your network adapters drivers.

**[Option 1 – Manually](https://tools.techidaily.com/drivereasy/download/)**  – You’ll need some computer skills and patience to update your drivers this way, because you need to find exactly the right the driver online, download it and install it step by step.

OR

**[Option 2 – Automatically (Recommended)](https://tools.techidaily.com/drivereasy/download/)**  – This is the quickest and easiest option. It’s all done with just a couple of mouse clicks – easy even if you’re a computer newbie.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Option 1 –** **Download and install the driver manually**

 You can download drivers from the manufacturer official website. Go to the website to find the correct model and choose your specific flavor of Windows system (Window 10 64-bits or etc.). Then download the driver manually.

### **Option 2 – Automatically update drivers**

 If you don’t have the time, patience or computer skills to update the driver manually, you can do it automatically with Driver Easy.

[Driver Easy](https://tools.techidaily.com/drivereasy/download/) will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the [Pro version](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. But with the [Pro version](https://tools.techidaily.com/drivereasy/download/) it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[Download](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2019/04/network1.jpg)

 3) Click the**Update**  button next to the flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the FREE version).  
 Or click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)![](https://images.drivereasy.com/wp-content/uploads/2019/04/network.jpg)

---

 Thanks for reading. Hope this article meets your need. And you are welcome to leave comments below.

* [error](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://extra-guidance.techidaily.com/new-simplifying-complexity-essential-gs-tutorials-kinemaster/"><u>[New] Simplifying Complexity Essential GS Tutorials (KineMaster)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-transparency-in-tracking-youtube-viewers/"><u>[New] Transparency in Tracking YouTube Viewers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-revealed-top-10-powerful-fcp-plugin-tools/"><u>[Updated] Revealed Top 10 Powerful FCP Plugin Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2023-how-to-watch-facebook-live-in-2024/"><u>2023 | How to Watch Facebook Live, In 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-xiaomi-redmi-note-13-proplus-5g-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on Xiaomi Redmi Note 13 Pro+ 5G.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-to-connect-airpods-to-windows-11-expert-advice/"><u>Easy Fixes to Connect AirPods to Windows 11 - Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correcting-user-profile-service-logon-failure-a-detailed-walkthrough/"><u>Guide to Correcting 'User Profile Service Logon Failure' - A Detailed Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-volume-shadow-copy-service-not-working-in-windows/"><u>How to Fix the Volume Shadow Copy Service Not Working in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-video-playback-issue-with-error-224003/"><u>How To Fix: Video Playback Issue with Error 224003</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-navigating-instagrams-algorithm-for-better-engagement/"><u>In 2024, Navigating Instagram's Algorithm for Better Engagement</u></a></li>
<li><a href="https://youtube-help.techidaily.com/leveraging-youtube-content-for-igtv-prominence-for-2024/"><u>Leveraging YouTube Content for IGTV Prominence for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revolutionize-your-gaming-experience-with-smooth-120fps-gameplay-on-ps5/"><u>Revolutionize Your Gaming Experience with Smooth 120Fps Gameplay on PS5</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-troubleshooting-techniques-for-compromised-windows-store-caches/"><u>Solved: Troubleshooting Techniques for Compromised Windows Store Caches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-troubleshooting-your-hp-laptops-nonfunctioning-camera-in-windows-1/"><u>Step-by-Step Guide: Troubleshooting Your HP Laptop's Nonfunctioning Camera in Windows 1</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-windows-10-sound-settings-issue-a-complete-guide/"><u>Troubleshoot and Fix Windows 10 Sound Settings Issue - A Complete Guide</u></a></li>
</ul></div>

