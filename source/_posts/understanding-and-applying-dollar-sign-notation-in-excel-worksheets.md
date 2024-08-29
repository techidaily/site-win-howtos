---
title: Understanding and Applying Dollar Sign Notation in Excel Worksheets
date: 2024-08-28T00:20:07.018Z
updated: 2024-08-29T00:20:07.018Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/microsoft-excel-logo-3.jpg
---

## Understanding and Applying Dollar Sign Notation in Excel Worksheets

### Quick Links

* [What Are Excel Cell References?](https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-oneplus-ace-2v-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [How to Use Relative References in Excel](https://screen-sharing-recording.techidaily.com/updated-smooth-sailing-easy-recording-tips-for-your-logitech-cam/)
* [How to Use Absolute References in Excel](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/)
* [How to Use Mixed References in Excel](https://screen-mirror.techidaily.com/how-realme-note-50-mirror-screen-to-pc-drfone-by-drfone-android/)
* [How to Switch Between Different Types of Cell References in Excel](https://visual-screen-recording.techidaily.com/in-2024-capturing-clarity-a-look-at-screensnapelite/)

### Key Takeaways

* Excel cell references can be relative, absolute, or mixed to achieve specific outcomes in formulas.
* Relative references change when copied to another cell, while absolute references stay the same.
* Mixed references lock either the column or row in a formula.

 When dealing with lots of data in Excel, you can use relative, absolute, or mixed references to save repetitive manual work, ensure your formulas work correctly, and capture large volumes of data in just a few quick actions. Let's explore how to use these Excel reference types.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
##  What Are Excel Cell References?

 You use a cell reference when you want to capture information that is contained within another cell or range of cells. For example, the following formula references cells A1 and A2, and will add their contents together to produce a result.

=SUM(A1+A2)

 You can use the following types of cell references to achieve specific outcomes:

* By default, references in Excel are **relative**, which refers to the relative position of the cell. If you are typing a formula in cell A1 that involves cell A2, you are referencing the cell that is one cell below where you are typing. If you were to copy the formula into another cell, the reference would automatically perform the same relative action as in its previous location.
* You can also use an **absolute** reference, which does not change if you copy the formula into another cell. If you create a formula that refers to a cell using an absolute reference, that same cell will be referred to wherever the formula is used.
* Finally, you can use a **mixed** reference, which is a combination of the two.

 Let's look into these in more detail.

##  How to Use Relative References in Excel

 In the example shown here, you can see how much the person has spent on each item in each month. What they now want to do is work out the total spend for each month.

![Microsoft Excel sheet showing data relating to three items and a blank 'Total' table where the totals will be added together using relative references.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/relative-blank-results.png) 

 First, click the cell where you want the first calculation to be made (in this case, H2), and type the formula to create this calculation. In this example, you would use the following formula:

=SUM(E2+E12+E22)

![Microsoft Excel sheet showing the formula and results when the January spending totals are added together.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/relative-first-formula.png) 

 This has now referenced cells E2, E12, and E22 within the calculation, adding them together. This is a relative reference—the formula in cell H2 has referenced the cells that are three columns to the left (E2), three columns to the left and ten rows down (E12), and three columns to the left and twenty rows down (E22), respectively.

 Now, if you were to copy and paste that same formula elsewhere, it would pick up the values that are in the same relative positions to where you paste it. You can also [use Excel's AutoFill function](https://tech-haven.techidaily.com/top-5-ai-generated-text-prompts-that-could-lead-to-fraud/) to complete the rest of your data with the same relative reference.

![Microsoft Excel sheet containing all results for each month after using relative referencing and AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/relative-autofilled.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 As you can see here, the formula in cell H11 is:

=SUM(E11+E21+E31)

 This is because the relative reference is placed nine rows down from where it was originally. Now, rather than typing the formula for each month, you only have to type it once and then apply the same relative reference wherever you want on your Excel worksheet.

##  How to Use Absolute References in Excel

 In this example, the company accountant wants to work out how much to pay the employees based on the number of hours they have worked and a fixed hourly rate.

![Microsoft Excel sheet showing data relating to several employees and a blank 'Total' table where their total pay will be added together using absolute references.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/absolute-blank-results.png) 

 Start by clicking the cell where you want the first total to be calculated (in this case, E2), and begin to type the appropriate formula. In this example, the accountant wants to multiply the hourly rate in cell A2 by the total hours worked by Jacinda in D2.

=SUM(A2

 However, if we use a relative reference here, when we apply the formula to the other employees' totals, the formula will reference cell A3 for Raul, A4 for Lucy, and so on, meaning you will not get the results you want.

![Microsoft Excel sheet showing what happens when absolute referencing is not used when it should be.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/absolute-not-working.png) 

 So, we need to make sure that Excel continues to refer to the correct cell, which, in this case, is A2\. To do this, you need to insert the dollar symbol before each part of your reference:

=SUM($A$2

 This now tells Excel that if we use the same formula elsewhere, A2 will always be referenced.

 Instead of typing the dollar symbols manually, after typing the cell reference, hit F4 (you might need to [learn what the Function key does](https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-14-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/), depending on your keyboard), and the dollar symbols will appear automatically.

 You can now complete your formula. In this case, it will be as follows:

=SUM($A$2*D2)

![Microsoft Excel sheet showing the formula and result after absolute referencing has been applied.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/absolute-first-formula.png) 

 Note how the second part of the formula (D2) does not use an absolute reference. This is because we want to multiply cell A2 by each employee's respective hours, so that needs to be relative to each person's hours in column D.

 You can now apply the formula to the other cells by [copying and pasting](https://facebook-videos.techidaily.com/updated-in-2024-2023s-top-no-cost-fb-photo-and-video-crafting/) it or using Excel's AutoFill function, knowing that cell A2 is referenced absolutely.

![Microsoft Excel sheet containing all results for each employee after using absolute referencing and AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/absolute-autofilled.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use Mixed References in Excel

 There may be occasions when you need to lock the row but not the column within your formula, or vice versa. For example, in this case, the accountant wants to work out how much tax each employee has to pay based on their individual tax rates.

![Microsoft Excel sheet showing data relating to several employees and blank 'tax payable' tables where their total tax bill will be calculated using mixed references.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/mixed-blank-results.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 Therefore, we need to lock the values in column E (the tax rates), but not the rows, as they are different for each employee, and not the references to the years, as they need to be adaptable.

 Click the cell where you want the first calculation to be made (in this case, cell G2) and input your formula. In the example above, the accountant wants to begin by working out Arjun's 2021 tax payable, so they would type the following formula:

=SUM(B2*E2)

 We now need to lock column E. If we were to AutoFill to the right without the formula being amended, it wouldn't correctly calculate Arjun's 2022 tax payable; while it would accurately pick up the correct yearly income totals (because we are not locking cell B2), the formula would also reference cell F2\. To do this, add a dollar symbol before the reference to column E in your formula:

=SUM(B2*$E2)

 We don't want to use an absolute reference here because that would mean that, when we work out the tax payable for the other employees, Arjun's tax rate would be used instead of each employees' individual rates. In essence, locking only column E means that we will stay on the tax rates but can relatively adjust to each person's different rates.

![Microsoft Excel sheet showing the formula and result after mixed referencing has been applied.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/mixed-first-formula.png) 

 We can now use the AutoFill function to complete Arjun's tax payable totals, knowing that column E will remain locked in our calculations, whilst the totals for each year will move relative to where the formula is placed.

![Microsoft Excel sheet containing all results for Arjun after using mixed referencing and AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/mixed-autofilled-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Because we have locked column E but left the rows relative within our formula, we can confidently complete the remaining employees' totals based on their individual tax rates. Remember, you can click any cell within your results and see the formula in the formula bar to check the correct cells are referenced.

![Microsoft Excel sheet containing all results for all employees after using mixed referencing and AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/mixed-autofilled-2.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
##  How to Switch Between Different Types of Cell References in Excel

 If you want to easily toggle between relative, absolute, and mixed references in your Excel sheet, you don't need to type the dollar symbol each time. Instead, click the cell you want to amend and then, in the formula bar, click the part of the formula you want to switch (clicking directly before the reference, in the middle of the reference, or directly after the reference will work).

 In this case, we want to toggle between the cell reference types for cell G11, so we need to make sure to click somewhere on or next to that cell reference.

![Excel workbook showing the formula bar and the reference to cell G11 highlighted with an arrow.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/switching.png) 

 Then, press F4 and you will see the cell reference type change.

 It will first switch to an absolute reference:

$G$11

 Then a mixed reference with the row locked:

G$11

 Then a mixed reference with the column locked:

$G11

 And, finally, it will revert to the default, a relative reference:

G11

 If you want to toggle several references in the same formula at the same time, simply highlight the relevant references in the formula and follow the same steps.

---

 And you're done! Who knew that the mere presence of a dollar symbol can help you to quickly and accurately organize your cell references in Excel?

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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-mastering-live-streamed-gaming-sessions/"><u>[Updated] Mastering Live-Streamed Gaming Sessions</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-optimizing-hashtag-performance-on-facebook-ads-for-2024/"><u>[Updated] Optimizing Hashtag Performance on Facebook Ads for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-elevate-your-instagram-game-with-unique-highlight-images/"><u>2024 Approved  Elevate Your Instagram Game with Unique Highlight Images</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-on-iphone-12-pro-max-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock on iPhone 12 Pro Max</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ace-the-fix-troubleshooting-and-repairing-0x80070643-error-during-windows-updates/"><u>Ace the Fix: Troubleshooting and Repairing 0X80070643 Error During Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204227541-breeze-through-high-wmi-cpu-usage-woes-on-win11/"><u>Breeze Through High WMI CPU Usage Woes on Win11!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-irksome-issue-of-error-code-0x800704cf-on-your-windows-pc/"><u>Fixing the Irksome Issue of Error Code 0X800704CF on Your Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-world-of-warcrafts-slowdowns-a-comprehensive-solution-overview/"><u>Fixing World of Warcraft's Slowdowns: A Comprehensive Solution Overview</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-your-touchpad-cursor-remains-active-in-windows-11/"><u>How To Ensure Your Touchpad Cursor Remains Active In Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-freezing-or-unresponsive-windows-10-system/"><u>How to Fix a Freezing or Unresponsive Windows 10 System</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-itel-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Itel Phone Screen?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-tiny-tycoons-trail-to-treasure-ryan-kaji-and-youtube-earnings/"><u>In 2024, Tiny Tycoon’s Trail to Treasure  Ryan Kaji and YouTube Earnings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-of-x0x80070-652-windows-update-issue-with-simple-steps/"><u>Mastering the Fix of X0X80070 652-Windows Update Issue with Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mystery-of-the-asleep-pc-wake-failure-in-windows/"><u>Mystery of the Asleep PC: Wake Failure in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-the-process-how-to-get-clearance-from-trustedinstaller-for-file-changes/"><u>Navigating the Process: How to Get Clearance From TrustedInstaller for File Changes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-techniques-for-when-your-computer-wont-start-due-to-no-boot-error/"><u>Quick Fix Techniques for When Your Computer Won't Start Due to No Boot Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/regain-control-of-missing-icons-4-proven-solutions-to-restore-windows-11s-taskbar-functionality/"><u>Regain Control of Missing Icons: 4 Proven Solutions to Restore Windows 11'S Taskbar Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-steps-when-cant-reach-the-dhcp-server/"><u>Resolved: Troubleshooting Steps When Can't Reach the DHCP Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/say-goodbye-to-drawn-out-closures-solving-the-puzzle-of-a-lethargic-windows-10-shutdown/"><u>Say Goodbye to Drawn-Out Closures: Solving the Puzzle of a Lethargic Windows 10 Shutdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/shockwave-flash-and-google-chrome-collision-solutions-to-get-them-running-smoothly/"><u>Shockwave Flash and Google Chrome Collision – Solutions to Get Them Running Smoothly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-touchscreen-problems-on-windows-10-a-guide-to-five-reliable-solutions/"><u>Solving Common Touchscreen Problems on Windows 10: A Guide to Five Reliable Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-non-functional-usb-mouse-issue-top-solutions-for-laptops/"><u>Solving Your Non-Functional USB Mouse Issue: Top Solutions for Laptops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-the-modify-rendering-api-issue-causing-dota-2-error-202/"><u>Step-by-Step Fix for the 'Modify Rendering API' Issue Causing Dota 2 Error 202</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-scrolling-issue-on-synaptics-touchpad-under-windows-ten/"><u>Step-by-Step Guide to Fix Scrolling Issue on Synaptics Touchpad Under Windows # Ten</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-iosandroid-apps-for-mobile-friendly-youtube-streaming/"><u>Top 7 iOS/Android Apps for Mobile-Friendly YouTube Streaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-windows-camera-failure-error-0xa00f4292-explained/"><u>Troubleshooting Guide for Windows Camera Failure - Error 0xA00F4292 Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-to-eliminate-screen-stuttering-on-windows-11-devices/"><u>Troubleshooting Techniques to Eliminate Screen Stuttering on Windows 11 Devices</u></a></li>
<li><a href="https://techidaily.com/ultimate-guide-setting-up-your-triple-monitor-display/"><u>Ultimate Guide: Setting Up Your Triple-Monitor Display</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-a-new-self-the-art-of-changing-your-fb-photo/"><u>Unveiling a New Self: The Art of Changing Your FB Photo</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-the-best-of-the-rest-10-final-cut-pro-x-alternatives-for-video-editors/"><u>Updated The Best of the Rest 10 Final Cut Pro X Alternatives for Video Editors</u></a></li>
<li><a href="https://activate-lock.techidaily.com/what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-14-plus-by-drfone-ios/"><u>What You Want To Know About Two-Factor Authentication for iCloud From your Apple iPhone 14 Plus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-does-my-windows-11-computer-activate-alone-and-how-to-fix-it/"><u>Why Does My Windows 11 Computer Activate Alone and How to Fix It?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-wont-my-computer-shut-down-on-windows-11-proven-methods-to-fix-and-restart-safely/"><u>Why Won't My Computer Shut Down on Windows 11? Proven Methods to Fix and Restart Safely</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-automatic-repair-loop-solved/"><u>Windows 11 Automatic Repair Loop [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-update-issue-overcome-the-0x800705b4-setup-failure-with-easy-fixes/"><u>Windows 11 Update Issue? Overcome the 0X800705b4 Setup Failure with Easy Fixes</u></a></li>
</ul></div>
