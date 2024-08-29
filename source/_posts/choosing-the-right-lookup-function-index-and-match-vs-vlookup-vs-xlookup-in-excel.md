---
title: "Choosing the Right Lookup Function: Index & Match Vs. Vlookup Vs. XLOOKUP in Excel"
date: 2024-08-28T00:18:52.032Z
updated: 2024-08-29T00:18:52.032Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/65e89fa5592e17a634309edf6fa4b1c7a4776f7c9bc581c108157d66f219235d.jpg
---

## Choosing the Right Lookup Function: Index & Match Vs. Vlookup Vs. XLOOKUP in Excel

### Quick Links

* [Using INDEX and MATCH](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-samsung-galaxy-z-flip-5-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [Using VLOOKUP](https://fox-blue.techidaily.com/2024-approved-top-10-jpg-to-gif-converters-online-free/)
* [Using XLOOKUP](https://on-screen-recording.techidaily.com/new-2024-approved-streamline-your-zoom-meetings-screen-sharing-essentials/)
* [Which Is Better?](https://extra-guidance.techidaily.com/updated-quick-fix-techniques-for-social-media-collaborative-art/)

 Lookup [functions in Microsoft Excel](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) are ideal for finding what you need when you have a large amount of data. There are three common ways to do this; INDEX and MATCH, VLOOKUP, and XLOOKUP. But what's the difference?

 INDEX and MATCH, VLOOKUP, and XLOOKUP each serve the purpose of looking up data and returning a result. They each work a bit differently and require a specific syntax for the formula. When should you use which? Which is better? Let's take a look so you know the best option for you.

##  Using INDEX and MATCH

 Obviously, the INDEX and MATCH combination is a mixture of the two named functions. You can take a look at our how-tos for the [INDEX function](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) and [MATCH function](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) for specific details on using them individually.

 To use this duo, the syntax for each is 

        `INDEX(array, row_number, column_number)`
    
 and 

        `MATCH(value, array, match_type)`
    
 .

 When you combine the two, you'll have a syntax like this: 

        `INDEX(return_array, MATCH(lookup_value, lookup_array))`
    
 in its most basic form. It's easiest to look at some examples.

 To find a value in cell G2 in the range A2 through A8 and provide the matching result in the range B2 through B8, you would use this formula:

=INDEX(B2:B8,MATCH(G2,A2:A8))

![INDEX and MATCH with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/IndexMatchCell-ExcelLookupFunctions.png) 

 If you prefer to insert the value you want to find instead of using the cell reference, the formula looks like this where 2B is the lookup value:

=INDEX(B2:B8,MATCH("2B",A2:A8))

 Our result is Houston for both formulas.

![INDEX and MATCH with a value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/IndexMatchValue-ExcelLookupFunctions.png) 

 We also have a tutorial that goes into detail on [using INDEX and MATCH](https://os-tips.techidaily.com/reviving-ipad-connectivity-essential-steps-for-reactivating-the-usb-driver/) should that be your choice.

Related: [How to Use INDEX and MATCH in Microsoft Excel](https://os-tips.techidaily.com/reviving-ipad-connectivity-essential-steps-for-reactivating-the-usb-driver/) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
##  Using VLOOKUP

 VLOOKUP has been a popular reference function in Excel for some time. The V stands for Vertical, so with VLOOKUP, you're doing a vertical lookup and it's from left to right.

 The syntax is `VLOOKUP(lookup_value, lookup_array, column_number, range_lookup)` with the last argument optional as True (approximate match) or False (exact match).

 Using the same data as that for INDEX and MATCH, we'll look up the value in cell G2 in the range A2 through D8 and return the value in the second column that matches. You'd use this formula:

=VLOOKUP(G2,A2:D8,2)

![VLOOKUP with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/VLOOKUPCell-ExcelLookupFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, the result using VLOOKUP is the same as using INDEX and MATCH, Houston. The difference is that VLOOKUP uses a much simpler formula. For more [details on VLOOKUP](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/), check out our how-to.

Related: [How to Use VLOOKUP on a Range of Values](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/) 

 So why would anyone use INDEX and MATCH instead of VLOOKUP? The answer is because VLOOKUP only works when your lookup value is to the left of the return value you want.

 If we did the reverse and wanted to look up a value in the fourth column and return the matching value in the second column, we would not receive the result we want and may even receive an error. As Microsoft [writes](https://support.microsoft.com/en-us/office/vlookup-function-0bbc8083-26fe-4963-8ab8-93a18ad188a1):

> Remember that the lookup value should always be in the first column in the range for VLOOKUP to work correctly. For example, if your lookup value is in cell C2 then your range should start with C.

 INDEX and MATCH covers the entire cell range or array making it a more robust lookup option even if the formula is a bit more complicated.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Using XLOOKUP

 XLOOKUP is a reference function that arrived in Excel after VLOOKUP and the counterpart HLOOKUP (horizontal lookup). The difference between XLOOKUP and VLOOKUP is that XLOOKUP works no matter where the lookup and return values reside in your cell range or array.

 The syntax is `XLOOKUP(lookup_value, lookup_array, return_array, not_found, match_mode, search_mode)`. The first three arguments are required and are similar to that in the VLOOKUP function. XLOOKUP offers three optional arguments at the end for giving a text result if the value isn't found, a mode for the type of match, and a mode for how to perform the search.

 For the purpose of this article, we'll concentrate on the first three required arguments.

 Back to our cell range from earlier, we'll look up the value in G2 in the range A2 through A8 and return the matching value from the range B2 through B8 with this formula:

=XLOOKUP(G2,A2:A8,B2:B8)

![XLOOKUP with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/XLOOKUPCell-ExcelLookupFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And like with INDEX and MATCH as well as VLOOKUP, our formula returned Houston.

 We can also use a value in the fourth column as the lookup value and receive the correct result in the second column:

=XLOOKUP(20745,D2:D8,B2:B8)

![XLOOKUP from right to left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/GoodXLOOKUP-ExcelLookupFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
 With this in mind, you can see that XLOOKUP is a better option than VLOOKUP simply because you can arrange your data any way you like and still receive your desired result. For a full [tutorial on XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/), head over to our how-to.

Related: [How to Use the XLOOKUP Function in Microsoft Excel](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) 

 So now you're wondering, should I use XLOOKUP or INDEX and MATCH, right? Here are some things to consider.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
##  Which Is Better?

 If you already use the INDEX and MATCH functions separately and have used them together to lookup values, then you may be more familiar with how they work. By all means, if it's not broken, don't fix it, and keep using what makes you comfortable.

 And of course, if your data is structured to work with VLOOKUP and you've used that function for years, you can continue using it or make the easy transition to XLOOKUP leaving INDEX and MATCH in the dust.

 If you want to a simple, easy-to-build formula in any direction, XLOOKUP is the way to go and can replace INDEX and MATCH. You don't have to worry about combining arguments from two functions into one or rearranging your data.

 One last consideration, [XLOOKUP does offer those three optional arguments](https://support.microsoft.com/en-us/office/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929) which may come in handy for your needs.

 Over to you! Which lookup option will you use in Microsoft Excel? Or maybe, you'll use all three depending on your needs? No matter what, it's nice to have options!

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-expert-recommendations-the-finest-skype-recorders-of-2023/"><u>[New] In 2024, Expert Recommendations  The Finest Skype Recorders of 2023</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-mastering-aspect-ratios-for-youtube-videos-shorts-and-ads-guide/"><u>[Updated] Mastering Aspect Ratios for YouTube Videos, Shorts & Ads Guide</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-discover-the-leading-no-cost-film-enhancement-platforms/"><u>2024 Approved  Discover the Leading No-Cost Film Enhancement Platforms</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pioneering-flight-paths-with-gopro-karma-technology/"><u>2024 Approved  Pioneering Flight Paths with GoPro Karma Technology</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-werfaultexe-hurdle-tips-and-tricks-for-stable-windows/"><u>Bypassing the werFault.exe Hurdle: Tips & Tricks for Stable Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comparative-costs-yt-vs-other-platforms-for-2024/"><u>Comparative Costs  YT vs Other Platforms for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-repairing-incomplete-or-damaged-registry-issues-causing-dvdcd-rom-errors-on-windows-10/"><u>Comprehensive Guide: Repairing Incomplete or Damaged Registry Issues Causing DVD/CD-ROM Errors on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-2-initializing-problem-solved-a-comprehensive-guide/"><u>Destiny 2 Initializing Problem Solved - A Comprehensive Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/dont-miss-out-grab-your-20-off-driver-easy-offer-with-the-official-coupon/"><u>Don't Miss Out: Grab Your 20%% Off Driver Easy Offer with the Official Coupon</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-11-webcam-problem-a00f4289-expedition/"><u>Eradicating Windows 11 Webcam Problem: A00F4289 Expedition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-pc-restoration-in-windows-11-heres-how-you-can-fix-the-problem-encountered-during-setup/"><u>Error-Free PC Restoration in Windows 11? Here's How You Can Fix the 'Problem Encountered During Setup'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-to-fixing-a-faulty-igfxem-chip-on-your-pc/"><u>Expert Guide to Fixing a Faulty Igfxem Chip on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-address-windows-resource-protection-cannot-complete-the-task-error/"><u>Expert Tips to Address 'Windows Resource Protection' Cannot Complete the Task Error</u></a></li>
<li><a href="https://win-solutions.techidaily.com/five-essential-tips-to-get-your-evil-genius-2-up-and-running/"><u>Five Essential Tips to Get Your Evil Genius 2 Up and Running</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-responsive-wacom-pen-on-windows-11-and-10-troubleshooting-guide/"><u>Fixing a Non-Responsive Wacom Pen on Windows 11 and 10: Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-darkness-to-light-solutions-for-overcoming-the-windows-11-screen-blackout-challenge/"><u>From Darkness to Light: Solutions for Overcoming the Windows 11 Screen Blackout Challenge</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-overcome-the-persistent-windows-update-issue-error-0x80070652/"><u>How to Easily Overcome the Persistent Windows Update Issue (Error 0X80070652)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-restore-skype-video-functionality-on-your-pc-running-windows/"><u>How to Easily Restore Skype Video Functionality on Your PC Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-enable-interaction-when-your-screen-has-no-pentouch-input/"><u>How to Enable Interaction When Your Screen Has No Pen/Touch Input</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-iphone-7-plus-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or iPhone 7 Plus without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-stagnant-windows-update-process-resolved/"><u>How to Fix a Stagnant Windows Update Process: Resolved</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-honor-magic-5-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Honor Magic 5 Phone When You Forget the Password</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-cut-the-chatter-capture-game-moments-easily/"><u>In 2024, Cut the Chatter  Capture Game Moments Easily</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-xiaomi-redmi-note-13-proplus-5g-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Xiaomi Redmi Note 13 Pro+ 5G</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-honor-90-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Honor 90 to Another | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-zipping-up-an-enthralling-tiktok-credit-sequence/"><u>In 2024, Zipping Up an Enthralling TikTok Credit Sequence</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-bluetooth-technology-overcoming-pairing-obstacles-with-windows-11/"><u>Mastering Bluetooth Technology : Overcoming Pairing Obstacles with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202873075-mastering-the-art-of-fast-shutdowns-in-windows-11-top-strategies-to-try-now/"><u>Mastering the Art of Fast Shutdowns in Windows 11: Top Strategies to Try Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-wdf-performance-to-reduce-system-cpu-usage/"><u>Optimizing WDF Performance to Reduce System CPU Usage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/preserve-file-locations-seamless-booting-and-access-in-windows-11/"><u>Preserve File Locations: Seamless Booting and Access in Windows 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/ps4-pro-and-its-journey-towards-4k-graphics-mastery-reviewed/"><u>PS4 Pro and Its Journey Towards 4K Graphics Mastery Reviewed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-steps-to-correctly-address-error-code-0x800f081f-in-net-framework-35-setup/"><u>Resolving the Issue: Steps to Correctly Address Error Code 0X800F081F in .NET Framework 3.5 Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/scrolling-malfunctions-on-touchpad-heres-how-to-resolve-the-problem/"><u>Scrolling Malfunctions on Touchpad? Here's How to Resolve the Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-msmpengineexe-from-hogs-up-cpu-resources-in-windows-10-fixed/"><u>Stop MsMpEngine.exe From Hogs Up CPU Resources in Windows 10 – FIXED</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-and-high-cpu-use-in-windows-11-step-by-step-fix-guide/"><u>Svchost.exe & High CPU Use in Windows 11: Step-by-Step Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-guide-dealing-with-undetectable-system-modules/"><u>The Ultimate Fix Guide: Dealing With Undetectable System Modules</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-list-of-8-ai-driven-chrome-tools-to-supercharge-your-workday/"><u>The Ultimate List of 8 AI-Driven Chrome Tools to Supercharge Your Workday</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-sporadic-pc-power-off-issue-solutions-at-hand/"><u>Troubleshooting a Sporadic PC Power-Off Issue – Solutions at Hand</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-has-occurred-error-in-windows-10-7-and-8-successfully/"><u>Troubleshooting and Fixing 'Has Occurred Error' In Windows 10, 7 & 8 Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successful-surge-incident-on-transmission-node/"><u>Troubleshooting Successful: Surge Incident on Transmission Node</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcome-audio-issues-with-your-logitech-g930-headset/"><u>Troubleshooting Tips: Overcome Audio Issues with Your Logitech G930 Headset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-repairing-damaged-registry-and-system-files-in-windows-1011/"><u>Ultimate Guide: Repairing Damaged Registry and System Files in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsticking-the-steelseries-arctis-5-mic-effective-strategies-for-audio-recovery/"><u>Unsticking the SteelSeries Arctis 5 Mic: Effective Strategies for Audio Recovery</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-filmora-coupon-code-2022-7-ways-to-find2022-full-list/"><u>Updated 2024 Approved Filmora Coupon Code 2022 - 7 Ways to Find(2022 Full List)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-inkjet-fix-successful/"><u>Win7 Inkjet Fix Successful</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-hello-ready-cameras-identified/"><u>Windows Hello Ready Cameras Identified</u></a></li>
</ul></div>
