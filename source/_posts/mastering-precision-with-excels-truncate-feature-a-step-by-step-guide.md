---
title: "Mastering Precision with Excel's TRUNCATE Feature: A Step-by-Step Guide"
date: 2025-01-18T17:02:01.337Z
updated: 2025-01-25T17:16:02.512Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/56c09995c4310ae28019d3390616d9116d70341b815aee65c7667ed39de0e4c8.jpg
---

## Mastering Precision with Excel's TRUNCATE Feature: A Step-by-Step Guide

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Is the TRUNC Function?](https://extra-resources.techidaily.com/systematic-upgrade-procedures-for-macos-sierra-users/)
* [How to Use the TRUNC Function](https://data-wizards.techidaily.com/immediate-fix-to-freezing-problem-in-vlc/)
* [Remove the Time from a Date-Time Stamp](https://fox-direct.techidaily.com/exploring-interconnected-digital-universes-meta-and-omni-for-2024/)
* [Use TRUNC to Shorten Numbers](https://fox-info.techidaily.com/updated-the-ultimate-strategy-for-posting-srt-content-socially/)

 There are a variety of ways in Excel to remove decimal points and shortening number values. In this article, we explain how to use the TRUNC function and what makes it different from other techniques.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What Is the TRUNC Function?

 The TRUNC function truncates a number to a specified number of decimal places. The key factor that makes TRUNC different from other functions that remove decimal places is that the TRUNC function does not round values. If you use TRUNC to remove all the decimals from the value 4.68, the result is 4.

 The TRUNC function requires two pieces of information:

=TRUNC(number, [digits])

 The number is the value you want to truncate. Digits are the number of numerals you want to truncate the value to. The digits portion is optional, and if not answered, TRUNC will remove all decimal places.

##  How to Use the TRUNC Function

 Let's look at examples of the TRUNC function with some sample data. The below example uses the following TRUNC function.

=TRUNC(A2)

 If you do not specify how many digits to truncate, all decimal places will be removed.

![First TRUNC function example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/first-example.png) 

 You can see with the value in cell A2 that the TRUNC function does not apply any rounding. It simply truncates the number to 411.

 Let's see another example. This time we will reduce the values to two decimal places.

=TRUNC(A2,2)

![TRUNC function to two decimal places](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/two-decimal-places.png) 

 The TRUNC function will not display extra decimals if you ask it to show more than you have.

 Take the following example, and let's truncate it to two decimal places.

=TRUNC(A2,2)

![No extra decimals shown by TRUNC](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/no-extra-decimals.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The value in cell A4 is reduced to two decimal places, but the values in A2 and A3 stay as they are because they have less than two decimal places already.

 If you want to display the two decimals, the cells will need to be formatted to be forced to show them.

##  Remove the Time from a Date-Time Stamp

 A useful example of TRUNC is to remove the time from a date and time stamp in Excel.

 Imagine having the following date and time stamps, but we just want the date in a column for analysis.

![Date and time sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/date-and-time-data.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The following formula will work to remove the time.

=TRUNC(A2)

![Time removed from a date in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/time-removed.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Although the time is removed, the resulting cells will still need to be formatted as a date only.

##  Use TRUNC to Shorten Numbers

 This is a rare technique, but it is worth knowing that the TRUNC function will also accept negative numbers for the digits argument. When you use a negative number, the formula truncates the numbers to the left of the decimal point. However, it does not change the number of digits. It will replace them with zeroes.

 Let's look at the following example.

=TRUNC(A2,-1)

![Entering minus digits for the second argument](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/minus-digits.png) 

 You can see in each example that zero was used to replace the number that was removed from the left of the decimal point.

---

 There are multiple ways in Excel to remove decimal places, however, most of these will apply a rounding of some nature. The strength of the TRUNC function is that it does not round values and simply shortens them to the specified decimal place amount.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-expert-guide-3-ways-to-keep-track-of-live-discord-events/"><u>[New] 2024 Approved Expert Guide 3 Ways to Keep Track of Live Discord Events</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-measuring-movie-gb-usage-over-a-day/"><u>[New] In 2024, Measuring Movie GB Usage Over a Day</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-boosting-creativity-the-most-outstanding-free-slide-show-templates/"><u>[Updated] Boosting Creativity The Most Outstanding Free Slide Show Templates</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-enhance-your-podcasts-production-with-top-audio-devices-for-2024/"><u>[Updated] Enhance Your Podcast's Production with Top Audio Devices for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-slumber-assistants-our-pick-of-5-apple-watch-apps/"><u>Best Slumber Assistants: Our Pick of 5 Apple Watch Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fresh-techniques-for-boosting-minecraft-gameplay-and-reducing-lag/"><u>Fresh Techniques for Boosting Minecraft Gameplay and Reducing Lag</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-nonfunctional-camera-on-your-hp-notebook-running-windows-11/"><u>How to Fix a Nonfunctional Camera on Your HP Notebook Running Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-infinix-note-30i-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Infinix Note 30i Location | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/master-the-basics-essential-photo-edits-for-starters/"><u>Master the Basics Essential Photo Edits for Starters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-hiccups-restoring-functionality-to-your-unresponsive-google-chrome-browser/"><u>No More Hiccups: Restoring Functionality to Your Unresponsive Google Chrome Browser</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-user-account-control-prompts-in-windows-11-10-and-7/"><u>Resolve User Account Control Prompts in Windows 11, 10 & 7</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-definitive-checklist-for-acquiring-the-perfect-student-laptop-or-desktop/"><u>The Definitive Checklist for Acquiring the Perfect Student Laptop or Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-5-solutions-to-reduce-gpu-load-by-the-desktop-window-manager-on-windows-11/"><u>Top 5 Solutions to Reduce GPU Load by the Desktop Window Manager on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-cannot-read-file-paths-effective-solutions-and-tips/"><u>Troubleshooting Windows 'Cannot Read File Paths': Effective Solutions and Tips</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/l-storytelling-crafting-compelling-narratives-in-youtube-videos/"><u>Visual Storytelling Crafting Compelling Narratives in YouTube Videos</u></a></li>
</ul></div>

