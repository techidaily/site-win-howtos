---
title: "Mastering String Manipulation: The Ultimate Technique for Excel Substrings Retrieval"
date: 2025-01-19T17:46:04.495Z
updated: 2025-01-25T17:16:38.450Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
---

## Mastering String Manipulation: The Ultimate Technique for Excel Substrings Retrieval

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 In your selected cell, type the following function. In this function, replace `B2` with the cell where your full text is and `@` with the search character. The function will retrieve the entire string to the left of this character.

 Then press Enter.

=LEFT(B2,FIND("@",B2)-1)

![Use the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/2-enter-left-function.png) 

 Your selected cell will display the result of the function, which is the full text before your specified character in your cell.

![The result of the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/3-left-function-result.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You're all set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Extract the String to the Right of Your Text

 To get all the text that's to the right of the specified character in your cell, use Excel's `RIGHT` , `LEN` , and `FIND` functions.

 Start by launching your spreadsheet and clicking the cell in which you want to see the result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/4-right-select-cell.png) 

 In the selected cell, enter the [following function](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/). In this function, replace `B2` with the cell where your full text is and `@` with the search character. Excel will extract the entire string to the right of this character.

 Then press Enter.

=RIGHT(B2,LEN(B2)-FIND("@",B2))

![Type the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/5-type-right-function.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll see the result of the function in your chosen cell.

![The result of the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/6-right-function-result.png) 

 You're done.

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

##  Obtain a String From the Middle of Your Text

 If you'd like to extract a string containing a specific number of characters located at a certain position in your cell, use Excel's `MID` function.

 In your spreadsheet, select the cell where you want to display the resulting string.

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/7-mid-select-cell.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the selected cell, enter the following function. In this function, replace `B2` with the cell where you have the full text, `1` with the position of the character where you want to start the string selection, and `3` with the number of characters you want to extract.

 Then press Enter.

=MID(B2,1,3)

![Enter the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/8-enter-mid-function.png) 

 Excel will extract the specified number of characters from the given position in your cell.

![The result of the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/9-mid-function-result.png) 

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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-image-framing-essentials-top-apps-and-websites-creators/"><u>[New] 2024 Approved Image Framing Essentials Top Apps & Websites Creators</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203181297-resolved-unmasking-the-hidden-culprit-of-high-cpu-consumption-the-role-of-shell-infrastructures/"><u>[Resolved] Unmasking the Hidden Culprit of High CPU Consumption: The Role Of Shell Infrastructures</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-step-by-step-guide-recording-audio-on-the-internet-today/"><u>[Updated] In 2024, Step-by-Step Guide Recording Audio on the Internet Today</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-ultimate-guide-to-linking-fb-stories/"><u>[Updated] In 2024, The Ultimate Guide to Linking FB Stories</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/44cm5pep44gp6kal44kj44km44kl44ki44gg44gr77yb44k544k44oh44kj44oz44kw44gu5yuv55s744oa44km44oz44ot44o844oj44oe44ol44ol44ki44or44cn/"><u>「早く見られるように！スタディングの動画ダウンロードマニュアル」</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-the-unavailable-remote-procedure-call-error-in-windows-environments/"><u>Diagnosing and Repairing the Unavailable Remote Procedure Call Error in Windows Environments</u></a></li>
<li><a href="https://facebook.techidaily.com/1719153081491-facebook-founder-names-goat-as-crypto-pet/"><u>Facebook Founder Names Goat as 'Crypto' Pet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-your-current-security-settings-do-not-allow-this-file-to-be-downloaded/"><u>Fixed: Your Current Security Settings Do Not Allow This File to Be Downloaded</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-bluetooth-adapter-missing-from-windows-device-manager/"><u>How To Fix Bluetooth Adapter Missing From Windows Device Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-syncing-and-audio-dropouts-in-your-logitech-wireless-g930/"><u>How To Repair Syncing and Audio Dropouts in Your Logitech Wireless G930</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-game-enhancing-screens-top-5-for-ps5-and-xbox-gamers/"><u>In 2024, Game-Enhancing Screens Top 5 for PS5 & Xbox Gamers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigate-the-world-of-books-with-these-5-artificous-intelligence-tools/"><u>Navigate the World of Books with These 5 Artificous Intelligence Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hosted-network-could-not-start-errors-on-windows-11-devices/"><u>Overcoming 'Hosted Network Could Not Start' Errors on Windows 11 Devices</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-the-dark-screen-hurdle-a-players-handbook-for-cyberpunk-ebooten2077-successes/"><u>Resolving the Dark Screen Hurdle: A Player's Handbook for Cyberpunk Ebooten2077 Successes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-update-troubles-heres-how-to-fix-installation-errors-effortlessly/"><u>Steam Update Troubles? Here's How to Fix Installation Errors Effortlessly!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-adding-libdvdcss-to-handbrake-for-macos-ventura-and-windows-11/"><u>Step-by-Step Guide: Adding Libdvdcss to Handbrake for macOS Ventura & Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-xiaomi-redmi-12-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-windows-update-problems-for-smooth-operations/"><u>Troubleshoot Windows Update Problems for Smooth Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unfixable-fault-devices-cease-functioning/"><u>Unfixable Fault: Devices Cease Functioning</u></a></li>
</ul></div>

