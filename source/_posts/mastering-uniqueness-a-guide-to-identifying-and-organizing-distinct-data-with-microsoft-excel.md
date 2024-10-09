---
title: "Mastering Uniqueness: A Guide to Identifying and Organizing Distinct Data with Microsoft Excel"
date: 2024-08-28T00:19:28.388Z
updated: 2024-08-29T00:19:28.388Z
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

 Because the second argument assumes FALSE if nothing is included, we simply add a comma after the first argument and then another comma before the last argument. Alternatively, you can use this formula to obtain the same result:

=UNIQUE(A2:A10,FALSE,TRUE)

 You can use the UNIQUE function to list distinct values as well as text. In this formula, we can list unique [dates](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/):

=UNIQUE(F2:F10)

![UNIQUE function for dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UNIQUEDates-ExcelUNIQUEFunction.png) 

Related: [How to Sort by Date in Microsoft Excel](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
##  Sort the List Automatically

 As mentioned, you can [sort the list](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) automatically at the same time you use the UNIQUE function to create it. To do this, you simply add the SORT function to the beginning of the formula.

 The SORT function is currently only available in the Excel versions listed [earlier](https://fox-http.techidaily.com/in-2024-experience-like-never-before-leading-10-vr-devices/).

 The syntax for this function is `SORT(array, index, order, column)` where only the first argument is required.

 Using the first list of unique customers we created above and sort it immediately, you would use this formula:

=SORT(UNIQUE(A2:A10))

 As you can see, the UNIQUE formula is the required `array` argument for the SORT function.

![Sort values in ascending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SortAscending-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
 By default, the SORT function lists items in ascending order. To sort the same list in descending order, you would use the following formula which adds the `order` argument.

=SORT(UNIQUE(A2:A10),,-1)

 Notice here we have a double comma again. This is because we don't want the `index` argument, only the `order` argument. Use 1 for ascending order and -1 for descending order. If no value is used, the function assumes 1 by default.

![Sort values in descending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SortDescending-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
##  Combine Unique Values

 One more handy addition to the UNIQUE function allows you to combine values. For instance, maybe your list has values in two columns instead of just one as in the screenshot below.

![First and last names to combine](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/NamesToConcatenate-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 By adding the ampersand (&) operator and a space, we can create a list of first and last names of unique customers with this formula:

=UNIQUE(A2:A10&" "&B2:B10)

 To break down the formula, the first array, A2 through A10, contains the first names, the ampersands [concatenate the first names to the last names](https://article-helps.techidaily.com/updated-2024-approved-elevate-your-drone-game-with-top-tier-lipo-tech/) in B2 through B10 with a space between them in quotes.

![Combine unique first and last names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Concatenate-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 You can also include the SORT function here to put your list in ascending order with this formula:

=SORT(UNIQUE(A2:A10&" "&B2:B10))

![Combine and sort unique first and last names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ConcatenateSort-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
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

