---
title: Computer Won't Shut Down Windows 11 [SOLVED]
date: 2024-08-08 23:45:25
updated: 2024-08-09 12:51:10
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Computer Won't Shut Down Windows 11 [SOLVED]
excerpt: This Article Describes Computer Won't Shut Down Windows 11 [SOLVED]
thumbnail: https://thmb.techidaily.com/6be5b234be2302864f9331a3a3d7aaacb0018bce1f2511014ae677fbeed4c8da.jpg
---

## How to Overcome Unexpected Shutdown (Error 1067) on Your Windows PC - Now Solved

 Windows background services enable Windows features function properly. If some errors happen to services, you will face trouble then. Here in this article, we will be telling you how to fix one of the errors occurring to Windows services — **Error 1067: The process terminated unexpectedly** . Follow the tried-and-true solution below.

## Step 1

 On you keyboard, press**Windows** key +**R** key together to open Run box.  
 Type**regedit** in the box and hit**Enter** to open Registry Editor window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/2-1.png)

## Step 2

 Click **Yes**  when prompted by UAC (User Account Control).

![](https://images.drivereasy.com/wp-content/uploads/2017/06/3-2.png)

## Step 3\

 On Registry Editor window, expand **HKEY\_LOCAL\_MACHINE**  \> **SYSTEM**  \> **CurrentControlSet**  \> **Services** .

![](https://images.drivereasy.com/wp-content/uploads/2017/06/4-1.png)

## **Step 4.**

 Find and**right-click** on your service with error 1067 under Services dialog.  
 Then choose**Export** .  
 Choose a place to save it on the pop-up window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/5-1.png)

## **Step 5.**

 Back on Registry Editor window,**right-click** on the same service.  
 This time choose**Delete** .  
 Then close the window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/6-2.png)

## **Step 6.**

 Type**cmd** in the search box.  
 Right-click on**Command Prompt** to choose**Run as administrator** .

![](https://www.drivereasy.com/wp-content/uploads/2023/12/win11-cmd-Run-as-administrator.jpg)

## **Step 7.**

 Click **Yes**  when prompted by UAC.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/10-1.jpg)

## **Step 8.**

 Type**sfc /scannow** in the pop-up window.  
 Press**Enter** to run it.  
 Wait till verification**100%** complete.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/11-1.jpg)

## **Step 9.**

 Close the window and**restart** your computer.  
 Then find your service file saved at Step 4.  
 Right-click on it to choose**Merge** .  
 Click **Yes**  when prompted by UAC.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/7-1.png)

## **Step 10.**

 Open a Run box to type **services.msc**  in it and press **Enter**  to open Services window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/8.png)

## **Step 11.**

 On Services window, find and right-click on your service.  
 Then click**Start** and close the window.  
 See if the error still exists.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/9.png)

That’s it. Hope it did help you.

For any confusion, please feel free to leave your comment below, thanks.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
