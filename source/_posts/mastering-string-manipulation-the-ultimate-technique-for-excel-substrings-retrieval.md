---
title: "Mastering String Manipulation: The Ultimate Technique for Excel Substrings Retrieval"
date: 2024-08-28T00:18:23.222Z
updated: 2024-08-29T00:18:23.222Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
---

## Mastering String Manipulation: The Ultimate Technique for Excel Substrings Retrieval

### Quick Links

* [Which Method to Use for Substring Extraction?](https://youtube-clips.techidaily.com/new-crafting-a-pro-sports-youtube-feed-on-macos/)
* [Get the String To the Left of Your Text](https://facebook-video-share.techidaily.com/in-2024-youtube-ad-free-watching-chromefirefoxandroidios-tutorial/)
* [Extract the String to the Right of Your Text](https://ai-live-streaming.techidaily.com/meet-geekoms-game-changer-the-mini-pc-ax8-equipped-with-next-gen-intel-and-cutting-edge-ryzen-processors/)
* [Obtain a String From the Middle of Your Text](https://driver-download.techidaily.com/easy-installation-brother-mfc-9340cdw-drivers-for-windows-10-8-and-7-free-downloads-and-updates/)

 If you want to extract a substring from the left, right, or middle of your text, you can use Microsoft Excel's

        `LEFT`
    
 , `RIGHT`, `MID`, `LEN`, and `FIND` functions to do that. We'll show you how.

##  Which Method to Use for Substring Extraction?

 What [method to use](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) to extract a substring depends on where your substring is located.

 To extract a string from the left of your specified character, use the [first method](https://network-issues.techidaily.com/1719974331029-eradicate-lagging-vids-instantly/) below. To extract everything that's to the right of your specified character, use the [second method](https://extra-skills.techidaily.com/updated-leading-meaningful-conversations-an-interviewers-journey/) below. To extract a string from the middle of your text, use the [third method](https://technical-tips.techidaily.com/navigating-through-facebooks-visual-library-a-comprehensive-guide-to-image-searches/) below.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

##  Get the String To the Left of Your Text

 If you'd like to get all the text that's to the left of the specified character in your cell, use Excel's

        `LEFT`
    
 and `FIND` functions to do that.

 First, open your spreadsheet and click the cell in which you want to see the result.

![Select a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/1-left-select-cell.png) 

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
 In your selected cell, type the following function. In this function, replace `B2` with the cell where your full text is and `@` with the search character. The function will retrieve the entire string to the left of this character.

 Then press Enter.

=LEFT(B2,FIND("@",B2)-1)

![Use the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/2-enter-left-function.png) 

 Your selected cell will display the result of the function, which is the full text before your specified character in your cell.

![The result of the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/3-left-function-result.png) 

 You're all set.

##  Extract the String to the Right of Your Text

 To get all the text that's to the right of the specified character in your cell, use Excel's `RIGHT` , `LEN` , and `FIND` functions.

 Start by launching your spreadsheet and clicking the cell in which you want to see the result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/4-right-select-cell.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
 In the selected cell, enter the [following function](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/). In this function, replace `B2` with the cell where your full text is and `@` with the search character. Excel will extract the entire string to the right of this character.

 Then press Enter.

=RIGHT(B2,LEN(B2)-FIND("@",B2))

![Type the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/5-type-right-function.png) 

 You'll see the result of the function in your chosen cell.

![The result of the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/6-right-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
 You're done.

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

##  Obtain a String From the Middle of Your Text

 If you'd like to extract a string containing a specific number of characters located at a certain position in your cell, use Excel's `MID` function.

 In your spreadsheet, select the cell where you want to display the resulting string.

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/7-mid-select-cell.png) 

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the selected cell, enter the following function. In this function, replace `B2` with the cell where you have the full text, `1` with the position of the character where you want to start the string selection, and `3` with the number of characters you want to extract.

 Then press Enter.

=MID(B2,1,3)

![Enter the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/8-enter-mid-function.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
 Excel will extract the specified number of characters from the given position in your cell.

![The result of the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/9-mid-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
 And that's all there is to it.

---

 Like this, you can also [count the number of cells with text](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/) in your Excel spreadsheets. Check out our guide to learn how.

Related: [How to Count Cells With Text in Microsoft Excel](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/)

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
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-make-memories-not-videos-top-10-buzz-creating-tiktok-hacks/"><u>[Updated] 2024 Approved  Make Memories, Not Videos!  Top 10 Buzz-Creating TikTok Hacks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-detailed-guide-to-googles-voice-to-text-service-features-and-usage-for-2024/"><u>[Updated] Detailed Guide to Google's Voice-to-Text Service Features and Usage for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-bite-sized-video-specialist/"><u>2024 Approved  Bite-Sized Video Specialist</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-securing-your-youtube-profitability-monetization-auditing-guide/"><u>2024 Approved  Securing Your YouTube Profitability  Monetization Auditing Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ace-your-pcs-stability-addressing-and-solving-the-vcruntime140dll-error-problem/"><u>Ace Your PC's Stability: Addressing and Solving the VCRUNTIME140.dll Error Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/application-stalls-due-to-dll-absence/"><u>Application Stalls Due to DLL Absence</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-your-streams-with-ease-overcoming-twitch-error-4000/"><u>Diagnosing and Repairing Your Streams with Ease: Overcoming Twitch Error 4000</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diuril-ibuprofen-and-lipitor-in-that-order/"><u>Diuril, Ibuprofen, and Lipitor in that Order</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-a-quick-and-smooth-windows-10-power-down/"><u>Effective Solutions for a Quick and Smooth Windows 10 Power Down</u></a></li>
<li><a href="https://win-howtos.techidaily.com/elevate-your-scroll-wheel-game/"><u>Elevate Your Scroll Wheel Game</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x887a0006-a-step-by-step-guide-to-troubleshooting-and-resolution/"><u>Error Code 0X887A0006: A Step-by-Step Guide to Troubleshooting and Resolution</u></a></li>
<li><a href="https://fox-access.techidaily.com/essential-tools-for-crafting-a-competitive-business-plan/"><u>Essential Tools for Crafting a Competitive Business Plan</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-our-expert-picks-the-ultimate-guide-to-iphone-gps-applications/"><u>Explore Our Expert Picks: The Ultimate Guide to iPhone GPS Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-the-missing-dll-issue-how-to-restore-vcruntime140dll-on-windows-10/"><u>Fix the Missing DLL Issue: How to Restore VCRUNTIME140.dll on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-annoying-screen-tremor-on-your-windows-10-pc/"><u>Fixing the Annoying Screen Tremor on Your Windows 10 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-correct-unsupported-command-errors-on-lcdled-displays/"><u>How to Address and Correct Unsupported Command Errors on LCD/LED Displays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-and-resolve-audio-glitches-on-youtube-with-windows-10-patches/"><u>How to Repair and Resolve Audio Glitches on YouTube with Windows 10 Patches</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-enhancing-connectivity-ios-photo-library-and-snapchat-merge/"><u>In 2024, Enhancing Connectivity  IOS Photo Library & Snapchat Merge</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-complete-breakdown-of-using-screencastify-for-video-capture/"><u>In 2024, The Complete Breakdown of Using Screencastify for Video Capture</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210124096-laptop-keyboard-malfunction-heres-what-you-can-do-to-fix-it/"><u>Laptop Keyboard Malfunction? Here's What You Can Do To Fix It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-smooth-gameplay-expert-advice-on-solving-lags-in-pubg/"><u>Master Smooth Gameplay: Expert Advice on Solving Lags in PUBG!</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-the-ultimate-mp3-editors-manual-techniques-for-optimal-sound-quality/"><u>New 2024 Approved The Ultimate MP3 Editors Manual Techniques for Optimal Sound Quality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-darkness-in-gaming-solutions-for-obsgamecapture-screen-glitches/"><u>Overcoming Darkness in Gaming: Solutions for ObsGameCapture Screen Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-remote-server-connection-failures-effective-troubleshooting-techniques/"><u>Overcoming Remote Server Connection Failures: Effective Troubleshooting Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/remedy-for-missed-additional-monitor-win11/"><u>Remedy for Missed Additional Monitor (Win11)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-lag-issues-ultimate-guide-to-enhance-your-minecraft-performance/"><u>Resolve Your Lag Issues: Ultimate Guide to Enhance Your Minecraft Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-critical-failure-in-directx-system-detailed-analysis/"><u>Resolved: Critical Failure in DirectX System - Detailed Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-7-innovative-ai-programs-revolutionizing-math-problem-solving/"><u>Top 7 Innovative AI Programs Revolutionizing Math Problem-Solving</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-driver-related-power-issues-in-windows-operating-systems/"><u>Troubleshooting Driver-Related Power Issues in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-minecraft-multiplayer-server-connection-errors/"><u>Troubleshooting Guide: Resolving Minecraft Multiplayer Server Connection Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-speaker-distortion-on-windows-11-and-7-a-comprehensive-guide/"><u>Troubleshooting Speaker Distortion on Windows 11 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-0x80070643-update-failures-expert-solutions/"><u>Troubleshooting Windows 0X80070#643 Update Failures - Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-the-startup-error-code-0xc000007b-for-smooth-running-applications/"><u>Understanding And Repairing The Startup Error Code 0xC000007b For Smooth Running Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-registration-woes-heres-how-to-solve-unregistered-class-issues/"><u>Windows 11 Registration Woes? Here's How to Solve Unregistered Class Issues</u></a></li>
</ul></div>
