---
title: "Guide: Removing or Masking Erroneous Data Points and Warnings in Microsoft Excel Tables"
date: 2024-08-28T00:18:10.027Z
updated: 2024-08-29T00:18:10.027Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3e4359dd584ef6e6b8909874d88727d66b87bd9dc8bc7dbf15b341990bd1a4b9.jpg
---

## Guide: Removing or Masking Erroneous Data Points and Warnings in Microsoft Excel Tables

### Quick Links

* [Hide Errors with the IFERROR Function](https://facebook-clips.techidaily.com/how-to-view-facebook-content-on-your-home-theater/)
* [Background Error Checking](https://os-tips.techidaily.com/troubleshooting-failed-passwords-on-your-apple-devices-solutions-for-macbooks-and-imac/)
* [Turn Off the Excel Error Checking](https://hardware-updates.techidaily.com/how-to-install-hp-officejet-3830-printer-drivers-on-windows-pcs/)

 Your Excel formulas can occasionally produce errors that don't need fixing. However, these errors can look untidy and, more importantly, stop other formulas or Excel features from working correctly. Fortunately, there are ways to hide these error values.

##  Hide Errors with the IFERROR Function

 The easiest way to hide error values on your spreadsheet is with the IFERROR function. Using the IFERROR function, you can replace the error that's shown with another value, or even an alternative formula.

 In this example, a VLOOKUP function has returned the #N/A error value.

![#N/A error shown from VLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/vlookup-error.png) 

 This error is due to there not being an office to look for. A logical reason, but this error is causing problems with the total calculation.

 The IFERROR function can handle any error value including #REF!, #VALUE!, #DIV/0!, and more. It requires the value to check for an error and what action to perform instead of the error if found.

![Requirements of the IFERROR function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/iferror-arguments.png) 

 In this example, the VLOOKUP function is the value to check and "0" is displayed instead of the error.

![IFERROR function to display 0 instead of error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/iferror-to-display-0.png) 

 Using "0" instead of the error value ensures the other calculations and potentially other features, such as charts, all work correctly.

![Error values hidden with IFERROR](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/error-values-hidden.png) 

##  Background Error Checking

 If Excel suspects an error in your formula, a small green triangle appears in the top-left corner of the cell.

![Green indicator of possible Excel error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/indicator-arrow.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 Note that this indicator does not mean that there is definitely an error, but that Excel is querying the formula you're using.

 Excel automatically performs a variety of checks in the background. If your formula fails one of these checks, the green indicator appears.

 When you click on the cell, an icon appears warning you of the potential error in your formula.

![Smart tag for error options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/smart-tag-for-error.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click the icon to see different options for handling the supposed error.

![Options for handling the error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/error-options.png) 

 In this example, the indicator has appeared because the formula has omitted adjacent cells. The list provides options to include the omitted cells, ignore the error, find more information, and also change the error check options.

 To remove the indicator, you need to either fix the error by clicking "Update Formula to Include Cells" or ignore it if the formula is correct.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
##  Turn Off the Excel Error Checking

 If you do not want Excel to warn you of these potential errors, you can turn them off.

 Click File > Options. Next, select the "Formulas" category. Uncheck the "Enable Background Error Checking" box to disable all background error checking.

![Error checking options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/error-checking-options.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Alternatively, you can disable specific error checks from the "Error Checking Rules" section at the bottom of the window.

 By default, all of the error checks are enabled except "Formulas Referring to Empty Cells."

![Turn off specific error checking rules](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/error-check-options-2.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
 More information about each rule can be accessed by positioning the mouse over the information icon.

![More information on error checks](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/more-information.png) 

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Check and uncheck the boxes to specify which rules you would like Excel to use with the background error checking.

 When formula errors do not need fixing, their error values should be hidden or replaced with a more useful value.

 Excel also performs background error checking and queries mistakes it thinks you've made with your formulas. This is useful but specific or all error checking rules can be disabled if they interfere too much.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-essential-guide-to-creating-effective-video-loops-on-instagram/"><u>[New] 2024 Approved  The Essential Guide to Creating Effective Video Loops on Instagram</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-pro-tips-securely-preserving-whatsapp-call-recordings-for-2024/"><u>[New] Pro Tips  Securely Preserving WhatsApp Call Recordings for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-enhancing-engagement-sound-synchronization-for-fb-video-posts-for-2024/"><u>[Updated] Enhancing Engagement  Sound Synchronization for FB Video Posts for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-capture-breathtaking-scenes-on-iphone-with-ease/"><u>[Updated] In 2024, Capture Breathtaking Scenes on iPhone with Ease</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-perfecting-the-art-of-facebook-live-recording-for-2024/"><u>[Updated] Perfecting the Art of Facebook Live Recording for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-podcast-perfection-best-timing-strategy-for-2024/"><u>[Updated] Podcast Perfection  Best Timing Strategy for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bring-life-to-your-race-a-step-by-step-fix-for-silent-gameplay-in-forza-horizon-4/"><u>Bring Life to Your Race: A Step-by-Step Fix for Silent Gameplay in Forza Horizon 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-repairing-incomplete-or-damaged-registry-issues-causing-dvdcd-rom-errors-on-windows-10/"><u>Comprehensive Guide: Repairing Incomplete or Damaged Registry Issues Causing DVD/CD-ROM Errors on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-2-initializing-problem-solved-a-comprehensive-guide/"><u>Destiny 2 Initializing Problem Solved - A Comprehensive Guide</u></a></li>
<li><a href="https://article-tips.techidaily.com/dusk-rising-the-fade-out-process/"><u>Dusk Rising  The Fade Out Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-pc-restoration-in-windows-11-heres-how-you-can-fix-the-problem-encountered-during-setup/"><u>Error-Free PC Restoration in Windows 11? Here's How You Can Fix the 'Problem Encountered During Setup'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-to-fixing-a-faulty-igfxem-chip-on-your-pc/"><u>Expert Guide to Fixing a Faulty Igfxem Chip on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-address-windows-resource-protection-cannot-complete-the-task-error/"><u>Expert Tips to Address 'Windows Resource Protection' Cannot Complete the Task Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-responsive-wacom-pen-on-windows-11-and-10-troubleshooting-guide/"><u>Fixing a Non-Responsive Wacom Pen on Windows 11 and 10: Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-darkness-to-light-solutions-for-overcoming-the-windows-11-screen-blackout-challenge/"><u>From Darkness to Light: Solutions for Overcoming the Windows 11 Screen Blackout Challenge</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-guide-to-unlock-your-meizu-21-pro-by-drfone-android/"><u>Full Guide to Unlock Your Meizu 21 Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-overcome-the-persistent-windows-update-issue-error-0x80070652/"><u>How to Easily Overcome the Persistent Windows Update Issue (Error 0X80070652)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-restore-skype-video-functionality-on-your-pc-running-windows/"><u>How to Easily Restore Skype Video Functionality on Your PC Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-enable-interaction-when-your-screen-has-no-pentouch-input/"><u>How to Enable Interaction When Your Screen Has No Pen/Touch Input</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-stagnant-windows-update-process-resolved/"><u>How to Fix a Stagnant Windows Update Process: Resolved</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-a-found-iphone-13-pro-drfone-by-drfone-ios/"><u>In 2024, How To Unlock A Found iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-depth-insights-for-youtube-sound-enhancement/"><u>In-Depth Insights for YouTube Sound Enhancement</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-wdf-performance-to-reduce-system-cpu-usage/"><u>Optimizing WDF Performance to Reduce System CPU Usage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/preserve-file-locations-seamless-booting-and-access-in-windows-11/"><u>Preserve File Locations: Seamless Booting and Access in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-remote-server-connection-failures-a-step-by-step-guide/"><u>Resolving Issues with Remote Server Connection Failures: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-steps-to-correctly-address-error-code-0x800f081f-in-net-framework-35-setup/"><u>Resolving the Issue: Steps to Correctly Address Error Code 0X800F081F in .NET Framework 3.5 Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-msmpengineexe-from-hogs-up-cpu-resources-in-windows-10-fixed/"><u>Stop MsMpEngine.exe From Hogs Up CPU Resources in Windows 10 – FIXED</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-and-high-cpu-use-in-windows-11-step-by-step-fix-guide/"><u>Svchost.exe & High CPU Use in Windows 11: Step-by-Step Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-guide-dealing-with-undetectable-system-modules/"><u>The Ultimate Fix Guide: Dealing With Undetectable System Modules</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-ultimate-review-of-offworld-trading-company-secrets-to-successful-merchant-dominance-revealed/"><u>The Ultimate Review of Offworld Trading Company: Secrets to Successful Merchant Dominance Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-sporadic-pc-power-off-issue-solutions-at-hand/"><u>Troubleshooting a Sporadic PC Power-Off Issue – Solutions at Hand</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-has-occurred-error-in-windows-10-7-and-8-successfully/"><u>Troubleshooting and Fixing 'Has Occurred Error' In Windows 10, 7 & 8 Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-restoring-your-lost-desktop-icons-on-windows-10-fixed/"><u>Troubleshooting Guide: Restoring Your Lost Desktop Icons on Windows 10 [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successful-surge-incident-on-transmission-node/"><u>Troubleshooting Successful: Surge Incident on Transmission Node</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcome-audio-issues-with-your-logitech-g930-headset/"><u>Troubleshooting Tips: Overcome Audio Issues with Your Logitech G930 Headset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-repairing-damaged-registry-and-system-files-in-windows-1011/"><u>Ultimate Guide: Repairing Damaged Registry and System Files in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-the-secret-to-fixing-error-code-0x80070002-in-windows-update-expert-advice/"><u>Unlock the Secret to Fixing Error Code 0X80070002 in Windows Update - Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsticking-the-steelseries-arctis-5-mic-effective-strategies-for-audio-recovery/"><u>Unsticking the SteelSeries Arctis 5 Mic: Effective Strategies for Audio Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-hello-ready-cameras-identified/"><u>Windows Hello Ready Cameras Identified</u></a></li>
</ul></div>
