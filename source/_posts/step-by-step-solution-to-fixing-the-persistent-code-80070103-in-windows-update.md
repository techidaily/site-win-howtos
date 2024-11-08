---
title: Step-by-Step Solution to Fixing the Persistent Code 80070103 in Windows Update
date: 2024-11-07T04:03:08.365Z
updated: 2024-11-08T07:02:28.019Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution to Fixing the Persistent Code 80070103 in Windows Update
excerpt: This Article Describes Step-by-Step Solution to Fixing the Persistent Code 80070103 in Windows Update
thumbnail: https://thmb.techidaily.com/e16b75fed413636ad54c914cb03e40ea47ab207cb6190aa0c6171995d867746d.jpg
---

## Step-by-Step Solution for Windows's Persistent Network Error: 0X800704cf - Now Resolved

When you fail to access another computer of the same network, or when you cannot log in to the Microsoft Store, you may see the 0x800704cf error code. This string seems quite confusing, but in fact it’s not hard to solve the problem.

 We cover solutions for both situations listed above. You may not try them all; simply work down the list until you find the one that does the trick.

* **[If you see 0x800704cf error when connecting to a network PC](https://tools.techidaily.com/drivereasy/download/)**
* **[If you see 0x800704cf error when accessing Microsoft Store](https://tools.techidaily.com/drivereasy/download/)**
* **[Bonus tips: Update your network driver](https://tools.techidaily.com/drivereasy/download/)**

---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## **Fix 0x800704cf error when connecting to a network PC**

![Fix 0x800704cf error when connecting to a network PC](https://images.drivereasy.com/wp-content/uploads/2020/08/case1.jpg)

 It’s very frustrating when you want to access another network PC to share files or perform specific tasks but are interrupted by the 0x800704cf error. No worries. You can follow the guide below to put things back on track.

1. **[Change adapter options](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset TCP/IP](https://tools.techidaily.com/drivereasy/download/)**
3. **[Reinstall the network adapter](https://tools.techidaily.com/drivereasy/download/)**

 The screenshot below comes from Windows 10, but the fixes also apply to Windows 7/8/11.

### Fix 1 – Change adapter options

 The network adapter enables your computer to transmit and receive data on a local area network. If you’re having the 0x800704cf error, try changing the adapter settings to see if that resolves the problem.

**1)** Right-click the**network icon** in the notification area.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-1-5.jpg)

**2)** Click**Open Network & Internet settings** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-2-8.jpg)

**3)** Select**Status** . Then, click**Change adapter options** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-3-2.jpg)

**4)** Right-click the network you’re currently using, and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-4.jpg)

**5)** Uncheck**Client for Microsoft Networks** , and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-5.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your device and check if the 0x800704cf goes away. If not, continue with the next fix below.

---

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 2 – Reset TCP/IP

 TCP/IP is a suite of rules that allow computers to communicate on a network. So if there’s something wrong with the[TCP/IP](https://en.wikipedia.org/wiki/Internet%5Fprotocol%5Fsuite) settings, the 0x800704cf error may occur. To see if that’s the case, you can simply do a reset.

**1)** Type**cmd** in the search box. Then, right-click**Command Prompt** and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-1-7.jpg)

**2)** Click**Yes** when you’re prompted to continue.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-3-2.jpg)

**3)** In the command prompt window, type in the following commands and press the **Enter** key after each command.

ipconfig /flushdns

nbtstat -RR

netsh winsock reset

netsh int ip reset

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-2-4.jpg)

 Now that the DNS cache is cleared, NetBIOS entries are refreshed, and both the IP settings and Winsock catalog is reset, you should reboot your computer for the changes to take effect. After that, check if the issue persists; if yes, head towards the last fix.

---

### Fix 3 – Reinstall the network adapter

 If all the methods above ended nowhere, you should reinstall the network adapter in case it’s corrupted and causes the 0x800704cf error.

**1)** On your keyboard, press the**Windows logo key** and**R** at the same time to open the Run box. Then, type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-1-6.jpg)

**2)** Select the**View** tab, and click**Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-2-8.jpg)

**3)** Double-click**Network adapters** to view all the devices under this category.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-3-4.jpg)

**4)** Right-click a device and click**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-5-1.jpg)

**5)** Click**Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-4-3.jpg)

**6)** Delete all the devices one by one under Network adapters.

 After completing the steps above, restart your machine, and Windows will automatically reinstall the network adapters. The 0x800704cf error should be gone now and you can connect to another network PC without hassle.

---

## **Fix 0x800704cf error when accessing the Microsoft Store**

![Fix 0x800704cf error when accessing the Microsoft Store on Windows 10](https://images.drivereasy.com/wp-content/uploads/2020/08/error-case-2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When you fail to access the Microsoft Store on Windows 10 or 11, this 0x800704cf error will appear. It implies you’re not connected to the Internet, even though you are, as you can use the browser and other applications normally. But don’t worry; here’s a list of fixes that can help.

1. **[Sign in with Microsoft account](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the Windows troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
3. **[Reset the Microsoft Store](https://tools.techidaily.com/drivereasy/download/)**

### Fix 1 – Sign in with Microsoft account

 The 0x800704cf error can arise when you’re logged in using a local account. Try signing in to your Microsoft account and see if the issue is resolved.

**1)** Click the**Start** button and click the**Settings icon** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-1-9.jpg)

**2)** Click**Accounts** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-2-7.jpg)

**3)** Select**Your info** in the left pane. Then, click**Sign in with a Microsoft account instead** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-3-9.jpg)

**4)** Enter your**account** and**password** to sign in.

**5)** Go back to**Your info** , and click**Verify** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-4-5.jpg)

 Follow the on-screen instruction to verify your identity. Then, open your Microsoft Store and see whether the 0x800704cf code still pops up or not. If this method isn’t helpful, don’t despair. Have a look at more fixes below.

---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 2 – Run the Windows troubleshooter

 If the 0x800704cf error keeps appearing when you’re using the Microsoft Store, the Windows built-in troubleshooter is an effective tool that may help you out.

**1)** Type**troubleshoot** in the search box and click**Troubleshooting settings** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-1-3.jpg)

**2)** Scroll down to click**Network Adapter** . Then, click**Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-2-3.jpg)

**3)** Select**All network adapters** , and click**Next** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-3-2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**4)** Wait for the troubleshooting process to complete, and close the troubleshooter.

**5)** Click**troubleshoot** in the search box and click**Troubleshooting settings** to open the troubleshoot menu again.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-1-4.jpg)

**6)** Scroll down to click**Windows Store Apps** and click**Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-4-2.jpg)

 Follow the on-screen instruction to fix any detected issues. Then, launch the Microsoft Store and check if it works without error. If not, please try the Fix 3 below.

---

### Fix 3 – Reset the Microsoft store

 If your Microsoft isn’t working properly for whatever reason, one of the solutions is clearing the stored data and resetting it back to the default.

**1)** Click the**Start** button and click the**Settings icon** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-1-10.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134499/19576" target="_top" id="2134499">
  <img src="//a.impactradius-go.com/display-ad/19576-2134499" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134499/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** Click**Apps** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-2-4.jpg)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Select**Apps & features** . Then, scroll down to click**Microsoft Store** , and click**Advanced options** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-3-2.jpg)

**4)** Scroll down and click**Reset** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-4-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**5)** Click**Reset** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-5-1.jpg)

 Open your Microsoft Store, and the 0x800704cf error won’t be disturbing you anymore.

 Network issue like 0x800704cf error is a common PC problem but it’s insufferable. There’s so much you can’t do without the Internet, and even worse, you can’t search a solution to fix it. If you’ve frequently run into this kind of issues such as no or slow Internet access, be sure to check our bonus tips below.

---

## Bonus tips: Update your network driver

 An outdated or a faulty network driver is known to be the culprit of most network problems. To keep your network connection smooth and strong, you should check if you install the up-to-date network adapter driver. If not, update them, in either way you want.

**Manual driver update** – You can update your network adapter driver manually by going to the manufacturer’s website, and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly:

**1)** **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

**2)** Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/de-1-5.jpg)

**3)** Click the**Update** button next to the flagged network driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the**FREE version** ).

 Or click**Update All** to automatically download and install the correct version of_all_ the drivers that are missing or out of date on your system. (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click**Update All** ).

![](https://images.drivereasy.com/wp-content/uploads/2020/08/de-2-7.jpg)

 You can do it for free if you like, but it’s partly manual.

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://tools.techidaily.com/drivereasy/download/) .**

---

 Hopefully this post helped you get rid of the 0x800704cf error. If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [network adapter](https://tools.techidaily.com/drivereasy/download/)
* [network issue](https://tools.techidaily.com/drivereasy/download/)
* [network problem](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-deciding-on-a-screen-projectors-and-tvs-at-the-forefront-of-4k-technology/"><u>[New] 2024 Approved Deciding on a Screen Projectors & TVs at the Forefront of 4K Technology</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-easy-iphonesideways-capturing-the-moment/"><u>[New] In 2024, Easy iPhonesideways Capturing the Moment</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-in-depth-guide-to-installing-microsofts-movie-maker/"><u>2024 Approved In-Depth Guide to Installing Microsoft's Movie Maker</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-unintended-automatic-turn-on-in-windows-11-computers/"><u>Diagnosing and Fixing Unintended Automatic Turn On in Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-for-unfreezing-a-stuck-laptop-or-desktop-computer/"><u>Expert Advice for Unfreezing a Stuck Laptop or Desktop Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-hp-laptops-nonfunctional-usb-port-a-step-by-step-guide/"><u>How To Fix HP Laptop's Nonfunctional USB Port: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-recover-missing-desktop-icons-on-windows-10-a-step-by-step-guide/"><u>How to Recover Missing Desktop Icons on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-vivo-t2x-5g-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Vivo T2x 5G</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-honor-x7b-phone-by-drfone-android/"><u>How to Unlock a Network Locked Honor X7b Phone?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-itel-a60s-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Itel A60s? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-interlace-snaps-a-guide-to-crafting-picture-panoramas/"><u>In 2024, Interlace Snaps A Guide to Crafting Picture Panoramas</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-0x80070002-update-issues-on-your-pc-with-ease/"><u>Resolving 0X80070002 Update Issues on Your PC with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-auto-start-issues-the-reasons-behind-unexpected-windows-10-power-ups/"><u>Solving Auto-Start Issues: The Reasons Behind Unexpected Windows 10 Power-Ups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-troubleshooting-of-windows-10-system-restore-problem-error-0x80070091/"><u>Successful Troubleshooting of Windows 10 System Restore Problem (Error 0X80070091)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-non-functioning-laptop-screen-answers-within-reach/"><u>The Non-Functioning Laptop Screen: Answers Within Reach</u></a></li>
</ul></div>

