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


