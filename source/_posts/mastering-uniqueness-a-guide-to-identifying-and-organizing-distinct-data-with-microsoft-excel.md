---
title: "Mastering Uniqueness: A Guide to Identifying and Organizing Distinct Data with Microsoft Excel"
date: 2025-01-20T17:25:03.233Z
updated: 2025-01-25T17:42:25.947Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ab3bfec296887a8d448d8e35c0b03544ab7fa85c994173438d04396b799c480a.jpg
---

## Mastering Uniqueness: A Guide to Identifying and Organizing Distinct Data with Microsoft Excel

### Quick Links

* [Use the UNIQUE Function in Excel](https://facebook-video-content.techidaily.com/new-in-2024-unlocking-your-fb-watchlist-access-liked-movies-and-shows/)
* [Sort the List Automatically](https://fox-that.techidaily.com/the-journey-of-facetime-snapshots-how-to-retrieve-and-store-them-safely/)
* [Combine Unique Values](https://youtube-clips.techidaily.com/from-passion-to-paychecks-your-vlog-venture-guide/)

 When you want a list of customers, email addresses, product IDs, or something similar where each one is distinct, [Excel has a function](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) to help. We'll show you how to use this function to list unique values and text.

 You can already use functions in Excel to total [the number of distinct values](https://youtube-help.techidaily.com/in-2024-unleash-potential-with-optimal-hashtags-for-gaming-vids/). But here we'll show you how to list those values instead using the UNIQUE function. Plus, we'll throw in easy ways to sort the list and combine values.

As of March 2022, the UNIQUE function is available in Excel for Microsoft 365, Excel for the web, Excel 2021 or later, or Excel for iPhone, iPad, or Android phones or tablets.

Related: [How to Count Unique Values in Microsoft Excel](https://youtube-help.techidaily.com/in-2024-unleash-potential-with-optimal-hashtags-for-gaming-vids/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Use the UNIQUE Function in Excel

 You can use the UNIQUE [function for text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) or numbers, decide how to compare the cell range, and opt to show results that only appear once.

 The syntax for the function is 

        `UNIQUE(array, column, only_once)`
    
 where only the first argument is required. Include the 

        `column`
    
 argument to compare columns instead of rows and the `only_once` argument to return values that occur only one time in the array.

 Should you choose to include the optional arguments, you'll use the TRUE indicator in the formula for each. If no indicator is included, the function assumes FALSE.

 As an example, we'll create a list of customers for an email blast. Rather than use the existing list in cells A2 through A10 because some customers ordered more than once, we'll make a new list where each customer appears one time.

=UNIQUE(A2:A10)

![UNIQUE function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UNIQUE-ExcelUNIQUEFunction.png) 

 For another example, we'll add the third argument, `only_once`, to find those customers who've only ordered once.

=UNIQUE(A2:A10,,TRUE)

![UNIQUE function for data appearing once](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/OnlyOnce-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Because the second argument assumes FALSE if nothing is included, we simply add a comma after the first argument and then another comma before the last argument. Alternatively, you can use this formula to obtain the same result:

=UNIQUE(A2:A10,FALSE,TRUE)

 You can use the UNIQUE function to list distinct values as well as text. In this formula, we can list unique [dates](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/):

=UNIQUE(F2:F10)

![UNIQUE function for dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UNIQUEDates-ExcelUNIQUEFunction.png) 

Related: [How to Sort by Date in Microsoft Excel](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Sort the List Automatically

 As mentioned, you can [sort the list](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) automatically at the same time you use the UNIQUE function to create it. To do this, you simply add the SORT function to the beginning of the formula.

 The SORT function is currently only available in the Excel versions listed [earlier](https://fox-http.techidaily.com/in-2024-experience-like-never-before-leading-10-vr-devices/).

 The syntax for this function is `SORT(array, index, order, column)` where only the first argument is required.

 Using the first list of unique customers we created above and sort it immediately, you would use this formula:

=SORT(UNIQUE(A2:A10))

 As you can see, the UNIQUE formula is the required `array` argument for the SORT function.

![Sort values in ascending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SortAscending-ExcelUNIQUEFunction.png) 

 By default, the SORT function lists items in ascending order. To sort the same list in descending order, you would use the following formula which adds the `order` argument.

=SORT(UNIQUE(A2:A10),,-1)

 Notice here we have a double comma again. This is because we don't want the `index` argument, only the `order` argument. Use 1 for ascending order and -1 for descending order. If no value is used, the function assumes 1 by default.

![Sort values in descending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SortDescending-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Combine Unique Values

 One more handy addition to the UNIQUE function allows you to combine values. For instance, maybe your list has values in two columns instead of just one as in the screenshot below.

![First and last names to combine](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/NamesToConcatenate-ExcelUNIQUEFunction.png) 

 By adding the ampersand (&) operator and a space, we can create a list of first and last names of unique customers with this formula:

=UNIQUE(A2:A10&" "&B2:B10)

 To break down the formula, the first array, A2 through A10, contains the first names, the ampersands [concatenate the first names to the last names](https://article-helps.techidaily.com/updated-2024-approved-elevate-your-drone-game-with-top-tier-lipo-tech/) in B2 through B10 with a space between them in quotes.

![Combine unique first and last names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Concatenate-ExcelUNIQUEFunction.png) 

 You can also include the SORT function here to put your list in ascending order with this formula:

=SORT(UNIQUE(A2:A10&" "&B2:B10))

![Combine and sort unique first and last names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ConcatenateSort-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Just like you might want to [highlight duplicate values in Excel](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/), you may want to find unique ones. Keep the UNIQUE function and these additional ways to use it in the mind the next time you need to create a list of distinct values or text in Excel.

Related: [How to Use Conditional Formatting to Find Duplicate Data in Excel](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/)

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-charting-the-course-of-monetization-for-creator-economy-on-youtubeshorts/"><u>[Updated] 2024 Approved Charting the Course of Monetization for Creator Economy on YouTubeshorts</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-crafting-charismatic-videos-with-diy-camera-setups/"><u>[Updated] Crafting Charismatic Videos with DIY Camera Setups</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-bloodthirsty-horror-your-ultimate-8-zombie-game-compilation/"><u>[Updated] In 2024, Bloodthirsty Horror Your Ultimate 8 Zombie Game Compilation</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-vimeo-unveiled-the-premier-video-platform/"><u>[Updated] In 2024, Vimeo Unveiled The Premier Video Platform</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-master-quick-youtube-video-uploads-and-rendering-secrets/"><u>2024 Approved Master Quick YouTube Video Uploads and Rendering Secrets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-resolving-issues-with-your-logitech-clips-digital-pen-on-xp/"><u>Comprehensive Guide To Resolving Issues With Your Logitech Clip's Digital Pen On XP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-class-not-registered-problems-in-windows-10-a-comprehensive-solution/"><u>Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correct-the-bad-module-information-to-stop-game-malfunctions/"><u>How To Correct the 'Bad Module Information' To Stop Game Malfunctions</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-discover-the-1-5-editors-perfect-for-your-macos-sierra-setup/"><u>In 2024, Discover the #1-#5 Editors Perfect for Your MacOS Sierra Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/power-fluctuation-addressed-and-stabilized-in-distribution-hub/"><u>Power Fluctuation Addressed and Stabilized in Distribution Hub</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-resolve-launch-errors-of-new-world-issues-with-enabling-eas-easy-anti-cheat/"><u>Step-by-Step Guide to Resolve Launch Errors of New World - Issues with Enabling EA's Easy Anti-Cheat</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-sketches-of-fortnite-game-screenshots-for-2024/"><u>Swift Sketches of Fortnite Game Screenshots for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unexpected-computer-shuts-off-heres-how-to-diagnose-and-resolve-it/"><u>Unexpected Computer Shuts Off? Here's How to Diagnose and Resolve It.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-mystery-of-microsofts-error-resolution-on-w11/"><u>Unlocking the Mystery of Microsoft's Error Resolution on W11</u></a></li>
<li><a href="https://win-updates.techidaily.com/unveiling-the-shields-of-your-pc-a-deep-dive-into-windows-defender-with-yl-software/"><u>Unveiling the Shields of Your PC: A Deep Dive Into Windows Defender with YL Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-booting-woes-discover-how-to-overcome-unexpected-freezes-upon-startup/"><u>Windows 10 Booting Woes? Discover How to Overcome Unexpected Freezes Upon Startup</u></a></li>
</ul></div>

