---
title: Decrease Windows WMi Usage on PCs
date: 2024-08-07 19:36:35
updated: 2024-08-09 12:32:31
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Decrease Windows WMi Usage on PCs
excerpt: This Article Describes Decrease Windows WMi Usage on PCs
thumbnail: https://thmb.techidaily.com/b5412951ba4c980abeddb9801e54de1f43b896bc3e121a51c5e15daf74ce2873.jpg
---

## [SOLVED] 100% Disk Usage in Windows 11

**100% disk usage** (or high disk usage) always hampers your Windows 11 experience. If Windows 11 Task Manager shows 100% disk usage, something is causing your hard drive to over-work.

 This complete guide includes the most effective fixes for you to try. After reading it, you should be able to fix the Windows 11 100% disk usage issue on your own quickly & easily!

## Try these fixes

 Here are the most effective fixes that have helped other users resolve their Windows 11 100% disk usage issue. You may not need to try them all; just work your way down the list until you find the one that works for you.

1. **[Stop SuperFetch service (Sysmain)](#h-fix-1-stop-superfetch-service-sysmain)**
2. **[Update your device drivers](#h-fix-2-update-your-device-drivers)**
3. **[Reset virtual memory](#h-fix-3-reset-virtual-memory)**
4. **[Perform a disk check](#h-fix-4-perform-a-disk-check)**
5. **[Clean boot Windows 11](#h-fix-5-clean-boot-windows-11)**

## Fix 1: Stop SuperFetch service (Sysmain)

 Introduced in Windows Visita, Superfetch is now known as Sysmain in the latest version of Windows 11 and Windows 10\. The official description of the Superfetch (Sysmain) service says that it “maintains and improves system performance over time”. It’s a Windows service running in the background that can predict which applications you’ll run next and pre-load the necessary data into your memory.

 According to many Windows users, SuperFect often slows down the SSD and causes high disk usage issue. If you’re experiencing the 100% disk usage issue, you should stop this service:

1. On your keyboard, press**the Windows logo key** and**R** at the same time to invoke the**Run** dialog. Type**`services.msc`** and press**Enter** to open the Services window.  
![Run services.msc](https://images.drivereasy.com/wp-content/uploads/2021/11/Run-services.msc_.jpg)
2. Scroll down to locate the**Sysmain** service. Right-click on it and select**Stop** to stop the Sysmain service.  
![Stop the Sysmain service](https://images.drivereasy.com/wp-content/uploads/2021/11/Stop-the-Sysmain-service.jpg)
3. Wait a few minutes and then press**ESC** ,**Shift,** and**Ctrl** on your keyboard at the same time to open**Task Manager** . See if the 100% disk usage issue persists.  
![Task Manager](https://images.drivereasy.com/wp-content/uploads/2021/11/Task-Manager.jpg)

 If it’s no longer 100%, congratulations! You’ve resolved this issue! If the 100% disk usage persists, try the next fix, below.

## Fix 2: Update your device drivers

 Your 100% disk usage issue may also be caused by a device driver. If the steps above didn’t fix your 100% disk usage issue in Windows 11, you should update your drivers.

 You can automatically update all your device drivers to the latest correct version with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the [**7 days free trial**](https://tools.techidaily.com/drivereasy/download/) or the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. It takes just 2 clicks, and you get full support and a 30-day money-back guarantee with the Pro version:

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2020/10/6_0_scan-now.jpg)
3. Click the**Activate & Update** button next to the flagged device to automatically download and install the correct version of this driver.  

 Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (You’ll need the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  for this – when you select Update All, you’ll get a prompt to upgrade. If you’re not prepared to purchase the Pro version yet, Driver Easy provides a 7-day trial at no cost, granting access to all Pro features like fast downloads and easy installation. No charges will occur until after your 7-day trial period ends.)  
![](https://www.drivereasy.com/wp-content/uploads/2021/05/NVIDIA-GeForce-RTX-3090-Ti-3.jpg)
4. Open Task Manager and look at the % at the top of the Disk column. See if the disk usage on your Windows 11 computer is 100%. If it’s no longer 100%, you’ve fixed this issue.  
![Task Manager](https://images.drivereasy.com/wp-content/uploads/2021/11/Task-Manager.jpg)

If the 100% disk usage problem persists, try the next fix, below.

## Fix 3: Reset virtual memory

 Virtual memory, or the paging file, is an area on the hard drive that Windows uses as if it were RAM. When your physical memory is running low, Windows will temporarily store files in virtual memory, then swap them back to RAM when required.

 Some Windows 11 users find that the 100% disk usage issue can be resolved by resetting virtual memory. To reset virtual memory:

1. On your keyboard, press**the Windows logo key** and**R** at the same time to invoke the**Run** dialog. Type`**SystemPropertiesAdvanced**` and press**Enter** to open**the System Properties window** .  
![run SystemPropertiesAdvanced](https://images.drivereasy.com/wp-content/uploads/2021/11/run-SystemPropertiesAdvanced.png)
2. Click on the**Settings…** button in the**Performance** section to view performance options.  
![System Properties window](https://images.drivereasy.com/wp-content/uploads/2021/11/System-Properties-window.png)
3. In the Performance Options window, navigate to the**Advanced** tab. Then click**the Change… button** in the**Virtual memory** section.  
![Change virtual memory](https://images.drivereasy.com/wp-content/uploads/2021/11/Change-virtual-memory.png)
4. **Uncheck the box** next to**Automatically manage paging file size for all drives** . Select your window drive (the drive or partition that has Windows 11 installed on it – usually**C:** ). Select**Custom size** to enter an Initial size and Maximum size for your virtual memory:  

**– Initial size** – If you’re not sure what value to use, just enter whatever the number is in the **Recommended** category.  

**– Maximum size** – The maximum size should be about 1.5 times the size of your physical RAM. For example, a PC with 8 GB (8,192 MB) of RAM should have no more than about 12,288 MB virtual memory (8192 MB x 1.5).
5. Once you’ve entered your virtual memory values, click **Set** , then click **OK**  to continue.  
![reset virtual memory](https://images.drivereasy.com/wp-content/uploads/2021/11/reset-virtual-memory.png)
6. Clear the temp files on your computer. To do so, on your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**`temp`** and press**Enter** . This will invoke Windows Explorer with your Temp folder open.  
![run temp](https://images.drivereasy.com/wp-content/uploads/2021/11/run-temp.png)
7. Select all the files in the Temp folder and delete them.  
![delete temp files](https://images.drivereasy.com/wp-content/uploads/2021/11/delete-temp-files.png)
8. Check the disk usage on your computer again. If it’s not 100%, it suggests that this issue has been fixed.

If the 100% disk usage issue remains, try the next fix, below.

## Fix 4: Perform a disk check

 Hard drive errors may also lead to the 100% disk usage issue. If you are not sure whether there are errors on your hard drive, you can use the built-in CHKDSK (Check Disk) feature to analyze hard drive errors and run repairs automatically.

To perform a disk check, follow the steps below:

1. On your keyboard, press**the Windows logo key** and**X** at the same time and choose**Windows Terminal (Admin)** to open Windows Terminal as administrator.  
![Windows Terminal admin](https://images.drivereasy.com/wp-content/uploads/2021/11/Windows-Terminal-admin.png)
2. In the Windows Terminal window, type in the following command:  
**`chkdsk.exe /f /r`**
3. Press Enter on your keyboard, then type Y to confirm that you’d like to perform the disk check the next time you restart your computer.  
![perform the disk check](https://images.drivereasy.com/wp-content/uploads/2021/11/perform-the-disk-check.png)  
**NOTE:** Disk check might take some time to complete. When you restart, if you don’t have time to wait for the disk check to complete, you can skip it. You’ll need to reschedule it again, as described above, though.
4. Once you restart your computer and complete the disk check, open Task Manager to check the disk usage again.

 See if the disk usage is still 100% after the disk check, don’t worry. Try the next fix below to

## Fix 5: Clean boot Windows 11

 The 100% disk usage issue may also be caused by some problematic applications or services. If you don’t know which application is causing this issue, you can perform a clean boot to find it out.

 A clean boot starts the Windows 11 OS with just the required programs and drivers, which helps you identify the cause behind the 100% disk usage.

 This fix may be time-consuming, so it is mentioned as the last fix.

To clean boot Windows 11, follow the instructions below:

1. On your keyboard, press**the Windows logo key** and**R** at the same time to invoke the**Run** dialog. Type`**msconfig**` and press**Enter** to open the**System Configuration** window.  
![run msconfig](https://images.drivereasy.com/wp-content/uploads/2021/11/run-msconfig.png)
2. Navigate to the **Services** tab, check **Hide all Microsoft services,** and then click **Disable all** .  
![System Configuration services](https://images.drivereasy.com/wp-content/uploads/2021/11/System-Configuration-services.png)
3. Select the **Startup** tab and click **Open Task Manager** .  
![System Configuration startup](https://images.drivereasy.com/wp-content/uploads/2021/11/System-Configuration-startup.png)
4. On the **Startup** tab in **Task Manager** , disable the programs you believe may be leading to the 100% disk usage issue. Once done, close Task Manager.  
![Disable startup in Task Manager](https://images.drivereasy.com/wp-content/uploads/2021/11/Disable-startup-in-Task-Manager.png)
5. Go back to the **System Configuration** window and click **OK** .  
![System Configuration startup 1](https://images.drivereasy.com/wp-content/uploads/2021/11/System-Configuration-startup-1.png)
6. Click **Restart** to restart your PC.  
![System Configuration restart](https://images.drivereasy.com/wp-content/uploads/2021/11/System-Configuration-restart.png)

**Restart** your PC and open Task Manager to check if the 100% disk usage persists. If the high disk usage issue reappears, it suggests that it’s not the programs or drivers, but something else that is causing this issue.

 However, if the disk usage remains under normal levels most of the time, it may be one of the services or programs you earlier disabled that triggered this issue. In that case, you need to enable them one at a time until you identify the problematic one.

 Once you find out the problematic program that is causing the 100% disk usage issues, you can **uninstall** it to avoid this issue in the future.

---

 Hopefully, one of the fixes above helped you resolve the 100% disk usage issues on your Windows 11 computer. If you have any suggestions or questions, feel free to drop a line in the comment area below. Thanks for reading!

* [windows 11](https://tools.techidaily.com/drivereasy/download/)

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
