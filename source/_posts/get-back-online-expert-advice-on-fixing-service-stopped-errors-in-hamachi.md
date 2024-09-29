---
title: "Get Back Online: Expert Advice on Fixing 'Service Stopped' Errors in Hamachi"
date: 2024-08-23T14:03:32.857Z
updated: 2024-08-24T14:03:32.857Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Get Back Online: Expert Advice on Fixing 'Service Stopped' Errors in Hamachi"
excerpt: "This Article Describes Get Back Online: Expert Advice on Fixing 'Service Stopped' Errors in Hamachi"
thumbnail: https://thmb.techidaily.com/3a8d29dc752129bc6cecd890184a07ba60927370b95afc8af67003c49b108b72.jpg
---

## Hamachi Trouble? Here's How You Can Fix a Stopped Service Error

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap69-1.jpg)

 If you’re running the LogMeIn Hamachi software and you meet the “**Hamachi service stopped** ” error, you’ve come to the right place.  
 Don’t worry, you’re not alone. Fortunately, it’s usually not too hard to fix.

## Try these fixes

 There are 5 fixes for you to try. You may not need to try them all, just work your way down until you find the one that works for you.

1. **[Enable the Windows Management Instrumentation (WMI) Service](https://www.drivereasy.com/knowledge/solved-how-to-solve-hamachi-service-stopped-error/#m2)**
2. **[Configure the LogMeIn Hamachi Tunneling Engine](https://tools.techidaily.com/drivereasy/download/)**
3. **[Check your antivirus software](https://tools.techidaily.com/drivereasy/download/)**
4. **[Reinstall LogMeIn Hamachi](https://tools.techidaily.com/drivereasy/download/)**
5. **[Create a startup to automatically restart the Hamachi service](https://tools.techidaily.com/drivereasy/download/)**
6. **[Bonus: Update your drivers by 2 clicks](https://tools.techidaily.com/drivereasy/download/)**

---

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

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
### Method 2: Configure the LogMeIn Hamachi Tunneling Engine

 1) On your keyboard, press the**Windows Key** (with Windows logo on it) +**R** together to open the Run box.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap54-1.jpg)

 3) Right-click on**LogMeIn Hamachi Tunneling Engine** and click the**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap47-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Set the Startup type to**Automatic** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap49.jpg)

 5) Move to**Log On** tab, make sure**Local System account** and**Allow service to interact with desktop** box has been checked. Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap50.jpg)

 6) Open the**File Explorer** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap62.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 7) In the address box, type “C:\\Program Files (x86)\\LogMeIn Hamachi”.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap51.jpg)

 8) Right-click on**hamachi-2-ui.exe** and open**Properties** .

 9) Under the**Security** tab, ensure the Users group permissions are set to “Read & execute”. If it’s not, you can click**Edit** to change permissions.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap60.jpg)

 10) Click**OK** to finish settings.

 11) Run Hamachi to check the problem.  

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
### Method 3: Check your antivirus software

 The “Hamachi service stopped” error may be caused by your antivirus software. When Hamachi was blocked by your antivirus software, the error will appear.  
 To solve it, you can change your antivirus software settings to make sure Hamachi won’t be blocked. If you don’t know how to do it, you can consult your antivirus software official customer service.

 There’s another situation that Hamachi isn’t blocked by antivirus software. Hamachi may have a conflict with your antivirus software. Therefore, uninstall the antivirus software and restart your computer can help you solve the error.

 If this resolves the problem, you can install another antivirus software. But if you are fond of the old one, contact the vendor of your antivirus software and ask them for advice.

**IMPORTANT:** Be extra careful in using the Internet after uninstalled your antivirus.

---

### Method 4: Reinstall LogMeIn Hamachi

 The “Hamachi service stopped” error can be caused by inappropriate configuration when you installed Hamachi.  
 You can reinstall the program to solve the problem.

 1) Click the Windows start button (if you hide the search field), type**control panel** in the search box and open the**Control Panel** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap66.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
 2) On the open window, choose to view by**Catalog** , then click**Uninstall a program** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap67-1-1024x593.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 3) Right-click on**LogMeIn Hamachi** and click**Uninstall** .  
 Follow the on-screen instructions to finish the process.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap68.jpg)

4) Download the program from LogMeln Hamachi official website.

5) Double click the program and follow the on-screen instructions to complete the installation.

6) Run Hamachi to check the problem.

---

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
### Method 5: Create a startup to automatically restart the Hamachi service

 This method will lead you to create a script that helps you restart the Hamachi service automatically.

 1) Click the Windows start button (if you hide the search field), type**notepad** in the search box and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap70.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
 5) On your keyboard, press the**Windows key** (with Windows logo on it) +**R** together to open the Run box.  
 Type**taskschd.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap74.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
 6) Click**Create Task** under the Actions menu.

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap81.jpg)

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

 12) Click the**Conditions** tab and unchecked everything. Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap80.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 13) Next time you start your computer, Hamachi will restart the service automatically.

---

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## Bonus: Update your drivers by 2 clicks

 In order to improve your VPN work performance, it’s important to keep your network adapter drivers up-to-date.  
 There are two ways you can update your network adapters drivers.

**[Option 1 – Manually](https://tools.techidaily.com/drivereasy/download/)**  – You’ll need some computer skills and patience to update your drivers this way, because you need to find exactly the right the driver online, download it and install it step by step.

OR

**[Option 2 – Automatically (Recommended)](https://tools.techidaily.com/drivereasy/download/)**  – This is the quickest and easiest option. It’s all done with just a couple of mouse clicks – easy even if you’re a computer newbie.

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


