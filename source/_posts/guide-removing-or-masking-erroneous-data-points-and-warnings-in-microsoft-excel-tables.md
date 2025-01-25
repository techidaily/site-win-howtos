---
title: "Guide: Removing or Masking Erroneous Data Points and Warnings in Microsoft Excel Tables"
date: 2025-01-23T17:00:18.426Z
updated: 2025-01-25T17:26:58.667Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Background Error Checking

 If Excel suspects an error in your formula, a small green triangle appears in the top-left corner of the cell.

![Green indicator of possible Excel error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/indicator-arrow.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this indicator does not mean that there is definitely an error, but that Excel is querying the formula you're using.

 Excel automatically performs a variety of checks in the background. If your formula fails one of these checks, the green indicator appears.

 When you click on the cell, an icon appears warning you of the potential error in your formula.

![Smart tag for error options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/smart-tag-for-error.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click the icon to see different options for handling the supposed error.

![Options for handling the error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/error-options.png) 

 In this example, the indicator has appeared because the formula has omitted adjacent cells. The list provides options to include the omitted cells, ignore the error, find more information, and also change the error check options.

 To remove the indicator, you need to either fix the error by clicking "Update Formula to Include Cells" or ignore it if the formula is correct.

##  Turn Off the Excel Error Checking

 If you do not want Excel to warn you of these potential errors, you can turn them off.

 Click File > Options. Next, select the "Formulas" category. Uncheck the "Enable Background Error Checking" box to disable all background error checking.

![Error checking options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/error-checking-options.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you can disable specific error checks from the "Error Checking Rules" section at the bottom of the window.

 By default, all of the error checks are enabled except "Formulas Referring to Empty Cells."

![Turn off specific error checking rules](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/error-check-options-2.png) 

 More information about each rule can be accessed by positioning the mouse over the information icon.

![More information on error checks](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/more-information.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-discovering-the-leading-speech-to-text-apps-for-ipads-3/"><u>[Updated] 2024 Approved Discovering the Leading Speech-to-Text Apps for iPads #3</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-effortlessly-download-top-5-chromium-plug-ins-for-fb-video-access-for-2024/"><u>[Updated] Effortlessly Download Top 5 Chromium Plug-Ins for FB Video Access for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-effortlessly-transcribe-sound-without-fee/"><u>[Updated] Effortlessly Transcribe Sound, Without Fee</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-video-editing-basics-on-windows-8-movie-maker/"><u>2024 Approved Mastering Video Editing Basics on Windows 8 Movie Maker</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-and-correcting-insufficient-system-resources-exist-issues-easily/"><u>Addressing and Correcting 'Insufficient System Resources Exist' Issues Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cell-proliferation/"><u>Cell Proliferation</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/cookiebot-your-trusted-automated-marketing-assistant/"><u>Cookiebot - Your Trusted Automated Marketing Assistant</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209064984-fix-rdr2-cannot-load-increase-pagefile-with-easy-steps/"><u>Fix 'RDR2 Cannot Load - Increase Pagefile' With Easy Steps!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-nokia-c210-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Nokia C210 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-a-guide-to-selecting-peak-performance-lipo-tech/"><u>In 2024, A Guide to Selecting Peak-Performance LiPo Tech</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lte-advanced-category-13-with-up-to-600-mbits-download-speeds-using-band-41-2x20-mhz-channel-arrangement-and-up-to-75-mbitn-upload-speeds-also-supports-dl-r99/"><u>LTE Advanced – Category 13 with up to 600 Mbit/S Download Speeds Using Band 41 (2X20 MHz) Channel Arrangement and up to 75 Mbit/N Upload Speeds. Also Supports DL-RevA Protocol Aggregation, but only with Other TANGO Radios on the Network</u></a></li>
<li><a href="https://article-files.techidaily.com/navigating-windows-10s-audio-settings/"><u>Navigating Windows 10'S Audio Settings</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-from-iphone-x-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock from iPhone X</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-high-gpu-usage-from-desktop-window-manager-in-windows-10-and-11-a-step-by-step-guide/"><u>Troubleshooting High GPU Usage From Desktop Window Manager in WINDOWS 10 and 11 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-intense-directx-malfunctions-for-smooth-performance/"><u>Troubleshooting Intense DirectX Malfunctions for Smooth Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-hdmi-connection-solving-windows-11s-tv-detection-problem/"><u>Troubleshooting the HDMI Connection: Solving Windows 11'S TV Detection Problem</u></a></li>
</ul></div>

