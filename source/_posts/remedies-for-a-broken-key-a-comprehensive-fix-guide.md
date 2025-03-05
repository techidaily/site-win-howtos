---
title: "Remedies for a Broken '@' Key: A Comprehensive Fix Guide"
date: 2025-03-02T16:21:48.680Z
updated: 2025-03-05T17:14:04.800Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Remedies for a Broken '@' Key: A Comprehensive Fix Guide"
excerpt: "This Article Describes Remedies for a Broken '@' Key: A Comprehensive Fix Guide"
thumbnail: https://thmb.techidaily.com/937c541b992b0530a2d9f47c677a74bf9df2301f6046e8bfec9f3c89d8f0ff48.jpg
---

## Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Fix 1: Reset your Windows Update components

 The Windows Update “0x8024002e” error code may occur because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this fixes your problem.

To reset these components:

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “cmd” in the Run box, then, on your keyboard, press the**Ctrl** ,**Shift** and**Enter** keys at the same time.

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-884.png)

3. If prompted, click**Yes** .
4. In Command Prompt, type the following lines of command and press**Enter** on your keyboard after typing each:

net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc

5. Type these lines of command and press**Enter** after typing each in Command Prompt:

ren %systemroot%\softwaredistribution softwaredistribution.old
ren %systemroot%\system32\catroot2 catroot2.old

6. In Command Prompt, type these commands and press**Enter** after each:

net start bits
net start wuauserv
net start appidsvc
net start cryptsvc

7. Try updating your system with Windows Update, and see if the 0x8024002e error is gone.

 If it is, then you’ve solved your problem. But if not, you may need to…

## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .

4. On the Registry Editor, click**File** , then select**Export** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.

7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)

5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .

7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .

9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)

11. Click**Restart** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  

 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)

15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  

 If there’s any startup item that causes the 0x8024002e error, you should see what program is this item related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.

 Hopefully one of the fixes above helped you fix your 0x8024002e error on Windows Update. If you have any questions or suggestions, you’re more than welcome to leave us a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-experts-choice-aspertronics-for-phones/"><u>[New] 2024 Approved Expert's Choice Aspertronics For Phones</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-how-to-schedule-meetings-on-zoom-in-2024/"><u>[New] How to Schedule Meetings on Zoom, In 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-tips-and-tricks-for-locating-recent-videos-youve-liked/"><u>[New] In 2024, Tips & Tricks for Locating Recent Videos You've Liked</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-screen-snip-pro-the-essential-guide-to-win-os-for-2024/"><u>[New] Screen Snip Pro The Essential Guide to Win OS for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-whats-the-price-tag-for-1m-youtube-sights/"><u>[Updated] In 2024, What's the Price Tag for 1M YouTube Sights?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2024mp3-mkv/"><u>2024年に最適な無料MP3変換アプリ: MKVファイル用のベストセレクション</u></a></li>
<li><a href="https://win-howtos.techidaily.com/adobe-premiere-promovmp4/"><u>Adobe Premiere Proを使用したMOVファイルからMP4への変換ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/associated-hyperlinks-uncover-related-content-connections/"><u>Associated Hyperlinks: Uncover Related Content Connections</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avchd-mp4windows-1011/"><u>AVCHDへの変換: MP4ファイルをWindows 10/11環境下でオンラインツールと無料ソフトウェアを使用してどうやったらいいか</u></a></li>
<li><a href="https://win-howtos.techidaily.com/buy-the-ultimate-document-management-system-wonderfox/"><u>Buy the Ultimate Document Management System: WonderFox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comparing-calcium-ion-caplus-and-potassium-ion-kplus/"><u>Comparing Calcium Ion (Ca+) and Potassium Ion (K+):</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-walkthrough-for-installing-the-kodi-magic-content-extension-by-no-limits-quick-and-easy-steps-inside/"><u>Comprehensive Walkthrough for Installing the Kodi Magic Content Extension by No Limits - Quick & Easy Steps Inside!</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-novice-to-pro-periscope-stream-mastery-for-2024/"><u>From Novice to Pro Periscope Stream Mastery for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/personalize-save-location-for-captured-mac-screen-for-2024/"><u>Personalize Save Location for Captured Mac Screen for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210662638-9781633412941-the-evil-eye/"><u>The Evil Eye | Free Book</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721469610161-understanding-your-iphone-screen-freeze-explore-these-7-key-factors/"><u>Understanding Your iPhone Screen Freeze: Explore These 7 Key Factors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/44oe44or44ob44oh44oh44kj44ki44ov44kh44kk44or44gl44kj44gu44k144ow44k44kk44oi44or5oqc44gn5yplusw44kk5pa55rov/"><u>マルチメディアファイルからのサブタイトル抜き取り方法</u></a></li>
</ul></div>

