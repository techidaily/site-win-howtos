---
title: "Breeze Through: Repairing That Incessant Stalled 'Windows Update' Issue"
date: 2024-08-09T01:01:46.230Z
updated: 2024-08-10T01:01:46.230Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Breeze Through: Repairing That Incessant Stalled 'Windows Update' Issue"
excerpt: "This Article Describes Breeze Through: Repairing That Incessant Stalled 'Windows Update' Issue"
thumbnail: https://thmb.techidaily.com/3dc1e13d990f9f4ed1b30979889fa15d157b3da05c97d832955a545581c7804d.jpg
---

## Troubleshooting Persistent Windows Updates Issues - Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fddb113ec0.png)

Window Update is an important component of your Windows system. It helps you install updates on your system. Windows Update is designed to keep your Windows up to date and healthy and it usually does. But unfortunately, in many cases, it fails to do so and instead become the source of multiple annoying problems. Many Windows users have reported that they have got this or that kind of issues with their Windows Update. They have been told that Windows Update “failed to install” certain updates or these updates’ “installation failed”. They’ve got an error popping up with a code and an associated message, which stops them from installing updates. Or they couldn’t download or install the updates with no clear message but get stuck in the update process. No matter how these issues look like, it stops you from installing the updates on your Windows. You can’t fix your system security vulnerabilities, fix bugs, and enjoy new system features without those updates. This can be extremely frustrating. But don’t panic. All Windows Update issues can be fixed. You can fix them by trying the methods below. You don’t have to try them all; just work your way down the list until you find the one that really works for you.**Methods that fix your Windows Update issues:**

1. [**Run Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restart Windows Update related services**](https://tools.techidaily.com/drivereasy/download/)
3. [**Manually download and install updates**](https://tools.techidaily.com/drivereasy/download/)
4. [**Run DISM and System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Disable your antivirus**](https://tools.techidaily.com/drivereasy/download/)
6. [**Update your drivers**](https://tools.techidaily.com/drivereasy/download/)
7. [**Restore your Windows**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## Method 1: Run Windows Update Troubleshooter

Windows Update Troubleshooter is a tool released by Microsoft that can help you troubleshoot issues with your Windows Update. You can run it to check your Windows Update when it fails to work properly. To do so:**1)**Download **[Windows Update Troubleshooter](https://aka.ms/diag%5Fwu)** (the program is from a Microsoft site and it’s verified and safe).**2)** Run the tool you’ve just downloaded and follow the on-screen instructions to complete the troubleshooting process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c046d056cc.png)

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Method 2: Reset the Windows Update related components

Your Windows Update may fail to update your Windows because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this can fix your problem. To reset these components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right-click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)** In Command Prompt, type these commands and press**Enter**after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Check your Windows Update to see if it works fine.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## Method 3: Manually download and install updates

If Windows Update can’t help you download certain system updates, you can try doing so on your own. Microsoft has put all its system updates online, and you can download these updates and install them on your computer without the help of Windows Update. To manually download and install updates:**1)**Click the**Start**button in the lower left corner of your screen. Then type “_**information**_“. In the list of results, click**System Information**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c0faa09e19.png)

**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)

**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

**2)** Click**System Restore**. The System Restore wizard will pop up.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)

**3)** Follow the on-screen instructions to choose a system restore point and restore your Windows.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc712671f3.png)

**4)** Wait for the restore process to complete and then check to see if your Windows Update gets back to normal.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
