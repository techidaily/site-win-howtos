---
title: "How To Successfully Patch Your System: Fixing The Windows 10 0X80nf0922 Setback"
date: 2024-09-01T05:00:20.849Z
updated: 2024-09-02T05:00:20.849Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How To Successfully Patch Your System: Fixing The Windows 10 0X80nf0922 Setback"
excerpt: "This Article Describes How To Successfully Patch Your System: Fixing The Windows 10 0X80nf0922 Setback"
thumbnail: https://thmb.techidaily.com/2d67e14b0eb8d4077153a676b64f0ce1665316566b80f80c4fccfcd9a772edaa.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://some-techniques.techidaily.com/updated-image-edition-excellence-tutorial-insights/"><u>[Updated] Image Edition Excellence  Tutorial Insights</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-nintendos-best-hd-recorders-for-enthusiasts/"><u>[Updated] Nintendo's Best HD Recorders for Enthusiasts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-mastering-spreadsheet-management-a-step-by-step-guide-to-addingremoving-columns-and-rows-in-excel/"><u>1. Mastering Spreadsheet Management: A Step-by-Step Guide to Adding/Removing Columns & Rows in Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-seamless-steps-embedding-pdf-documents-into-microsoft-excel/"><u>1. Seamless Steps: Embedding PDF Documents Into Microsoft Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/12-essential-microsoft-excel-configuration-tweaks-for-optimal-performance/"><u>12 Essential Microsoft Excel Configuration Tweaks for Optimal Performance</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-boost-engagement-with-clearly-marked-time-points/"><u>2024 Approved  Boost Engagement with Clearly Marked Time Points</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-facebooks-guide-to-enhancing-past-recordings-for-live-streaming/"><u>2024 Approved  Facebook's Guide to Enhancing Past Recordings for Live Streaming</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-xiaomi-14-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/6-powerful-strategies-to-create-stunning-microsoft-excel-charts/"><u>6 Powerful Strategies to Create Stunning Microsoft Excel Charts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/boost-your-productivity-a-complete-guide-to-using-flash-fill-and-autofill-features-in-excel/"><u>Boost Your Productivity: A Complete Guide to Using Flash Fill & Autofill Features in Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/choosing-the-right-lookup-function-index-and-match-vs-vlookup-vs-xlookup-in-excel/"><u>Choosing the Right Lookup Function: Index & Match Vs. Vlookup Vs. XLOOKUP in Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/choosing-the-right-spreadsheet-google-sheets-vs-microsoft-excel-compared/"><u>Choosing the Right Spreadsheet: Google Sheets Vs. Microsoft Excel Compared</u></a></li>
<li><a href="https://article-helps.techidaily.com/complete-narrative-deconstructing-googles-podcast-application-for-2024/"><u>Complete Narrative  Deconstructing Google's Podcast Application for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-automatic-resizing-cells-in-excel-for-effortless-data-management/"><u>Comprehensive Guide to Automatic Resizing Cells in Excel for Effortless Data Management</u></a></li>
<li><a href="https://win-howtos.techidaily.com/daily-productivity-boost-top-7-uses-for-microsoft-office-suite/"><u>Daily Productivity Boost: Top 7 Uses for Microsoft Office Suite</u></a></li>
<li><a href="https://win-howtos.techidaily.com/desktop-printers-or-print-shops-which-offers-better-value-for-money-in-the-long-run/"><u>Desktop Printers or Print Shops – Which Offers Better Value for Money in the Long Run?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discover-new-features-in-the-updated-web-based-microsoft-excel-suite/"><u>Discover New Features in the Updated Web-Based Microsoft Excel Suite!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easily-calculate-totals-with-our-simple-method-for-including-a-final-row-in-excel-spreadsheets/"><u>Easily Calculate Totals with Our Simple Method for Including a Final Row in Excel Spreadsheets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easily-integrate-microsofts-no-cost-web-plugins-into-your-blog/"><u>Easily Integrate Microsoft's No-Cost Web Plugins Into Your Blog</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-guide-calculating-the-number-of-colored-cells-in-excel/"><u>Easy Guide: Calculating the Number of Colored Cells in Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-tutorial-on-implementing-cell-based-select-options-in-microsoft-excel/"><u>Easy Tutorial on Implementing Cell-Based Select Options in Microsoft Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-for-implementing-user-tags-in-office-365-team-chats-and-comments/"><u>Effective Strategies for Implementing User Tags in Office 365 Team Chats and Comments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effectively-embedding-or-linking-excel-data-in-your-presentations-with-these-easy-steps/"><u>Effectively Embedding or Linking Excel Data in Your Presentations with These Easy Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-data-analysis-with-excel-how-to-apply-less-than-or-equal-to-conditions/"><u>Efficient Data Analysis with Excel: How to Apply 'Less than or Equal To' Conditions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-data-management-with-excel-macros-transform-routine-jobs-into-instant-actions/"><u>Efficient Data Management with Excel Macros: Transform Routine Jobs Into Instant Actions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/excel-essentials-unlocking-data-management-with-advanced-filter-techniques/"><u>Excel Essentials: Unlocking Data Management with Advanced Filter Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/excel-trick-for-seamless-selection-how-to-selectively-copy-and-paste-non-displayed-cells-efficiently/"><u>Excel Trick for Seamless Selection: How to Selectively Copy & Paste Non-Displayed Cells Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/exclusive-insight-how-understanding-microsoft-offices-concealed-features-can-benefit-you/"><u>Exclusive Insight: How Understanding Microsoft Office's Concealed Features Can Benefit You</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-crafting-eye-catching-visuals-with-microsoft-excel-top-six-techniques/"><u>Expert Advice: Crafting Eye-Catching Visuals with Microsoft Excel - Top Six Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-leveraging-microsoft-excels-smart-data-recognition-feature/"><u>Expert Tips for Leveraging Microsoft Excel's Smart Data Recognition Feature</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-push-to-talk-on-discord-a-step-by-step-guide-to-making-it-work-again/"><u>Fixing 'Push-To-Talk on Discord': A Step-by-Step Guide to Making It Work Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-creating-and-using-temporary-sharing-features-within-an-excel-spreadsheet/"><u>Guide: Creating and Using Temporary Sharing Features Within an Excel Spreadsheet</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-beyond-the-lens-essential-ios-and-android-video-platforms/"><u>In 2024, Beyond the Lens  Essential iOS and Android Video Platforms</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-apple-iphone-14-activation-lock-by-drfone-ios/"><u>In 2024, How to Remove Apple iPhone 14 Activation Lock</u></a></li>
<li><a href="https://extra-skills.techidaily.com/navigate-the-metaverse-with-friends-top-10-games-for-2024/"><u>Navigate the Metaverse with Friends - Top 10 Games for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-truth-behind-grok-ai-insights-from-musk-on-its-purpose-and-price/"><u>The Truth Behind Grok AI - Insights From Musk on Its Purpose & Price</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-rated-virtual-reality-vr-video-players-compatible-with-pc-mac-android-and-iphone-2018-edition/"><u>Top-Rated Virtual Reality (VR) Video Players Compatible with PC, Mac, Android & iPhone - 2018 Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-tutorial-on-implementing-the-if-formula-successfully-in-excel-spreadsheets/"><u>Ultimate Tutorial on Implementing the IF Formula Successfully in Excel Spreadsheets</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-ultimate-guide-to-video-dubbing-top-apps-for-2024/"><u>Updated The Ultimate Guide to Video Dubbing Top Apps for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->