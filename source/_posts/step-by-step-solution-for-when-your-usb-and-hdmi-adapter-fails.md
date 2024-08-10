---
title: Step-by-Step Solution for When Your USB and HDMI Adapter Fails
date: 2024-08-06 13:59:22
updated: 2024-08-09 10:38:30
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for When Your USB and HDMI Adapter Fails
excerpt: This Article Describes Step-by-Step Solution for When Your USB and HDMI Adapter Fails
thumbnail: https://thmb.techidaily.com/9482ded5e871af812d18f96a64c4deb315943988e9201916667eb608e7a9ffd3.jpg
---

## Step-by-Step Solution to Overcome Windows 1 Nearby as You Go, and It Will Be Easier to Keep Your Balance

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-42-51.jpg)

 If you’re looking for a solution to fix the Windows Update 0x80240034 error, you’ve come to the right place. Here are 4 solutions to try.

## Fixes to try

 You may not have to try them all. Just work your way down the list until you find the one that works for you.

1. **[Disable your antivirus temporarily](#a)**
2. **[Run the Windows Update troubleshooter](#b)**
3. **[Clear the Windows Update cache](#c)**
4. **[Repair corrupted system files using Command Prompt](#d)**

### Fix 1: Disable your antivirus temporarily

 Your problem is sometimes caused by interference from antivirus software. To see if that’s the problem for you, temporarily disable your antivirus program and check if the problem persists. (Consult your antivirus documentation for instructions on disabling it.)

 Try Windows Updates to see if this helped. If it runs correctly after you disable the antivirus software, contact the vendor of your antivirus software and ask them for advice, or install a different antivirus solution.

 Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

If this didn’t work for you, read on and check the fix below.

### Fix 2: Run the Windows Update troubleshooter

 When update errors occur, another quick fix you can choose is running the Windows Update troubleshooter.

**What is the Windows Update troubleshooter?**
 The Windows Update troubleshooter is a Windows built-in utility that can detect and fix common update problems automatically.

Here is how to do it:

**1)** On your keyboard, press the **Windows logo** key, and then click the**Settings**  button.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-43-28.jpg)

**2)**  Select **Update & Security.**

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-43-38.jpg)

**3)**  Select **Troubleshoot.**

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-43-47.jpg)

**4)** Select**Windows Update,** and then click **Run the troubleshooter.**

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-43-55.jpg)

**5)** Wait for the troubleshooter to detect your problem, and then follow the on-screen instructions to fix it automatically.

 If your computer fails to detect the problem, don’t worry! There are still 2 more fixes to try.

### Fix 3: Clear the Windows Update cache

 In many cases, the Windows Update cache could be the cause of your problem. In this case, clearing the cache can help. Follow the instructions below:

**1)** On your keyboard, press the**Windows logo** key and**R** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_14-10-17.jpg)

**2)** Type**services** , then press the**Enter key** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-44-18.jpg)

**3)** Double-click**Windows Update** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-46-02-1.jpg)

**4)** Click**Stop** , and then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-46-54.jpg)

**5)** On your keyboard, press the**Windows logo** key and**R** at the same time to open the Run dialog.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-47-04.jpg)

**6)** Type**%windir%\\SoftwareDistribution** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-47-15.jpg)

**7)** Press and hold the**Shift** key on your keyboard, then click**DataStore** and**Download** to highlight these two folders.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-47-24.jpg)

**8)** Right-click**the highlighted folders,** and then click**Delete** .

 If you’re prompted for permissions, select**Continue** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-47-34.jpg)

**9)** On your keyboard, press the**Windows logo** key and**R** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_14-10-17.jpg)

**10)** Type**services** , then press the**Enter key** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-44-18.jpg)

**11)** Right-click**Windows Update** and select**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2019/06/image-673.png)

**12)** Restart your computer and perform a system update to see if your problem has been resolved.

If not, check the fix below.

### Fix 4: Repair corrupted system files using Command Prompt

 Corrupted or damaged system files on your computer may also be the reason why the update fails. If that’s the problem for you, running Command Prompt can help. Follow the instructions below:

**1)**  On your keyboard, press the **Windows logo** key and **R** at the same time.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-50-59.jpg)

**2)**  Type **cmd,** then press the **Ctrl, Shift**  and **Enter** keys at the same time to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-51-03.jpg)

**3)**  Type **sfc.exe /scannow** , then press the **Enter**  key on your keyboard.

 This process could take several minutes. Please wait for it to be complete.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-51-15.jpg)

**4)** Type **dism.exe /online /cleanup-image /startcomponentcleanup** , then press the **Enter**  key on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-51-23.jpg)

**5)** Type **dism.exe /online /cleanup-image /restorehealth** , then press the **Enter** key on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/2019-12-31_16-51-33.jpg)

**6)** Wait for the process to be complete. Then, try updating your system again to see if this method worked.

 Hopefully, this article helped in resolving your problem. Please leave a comment below if you have any suggestions and questions.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](/tag-search/?tagId=62)

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
