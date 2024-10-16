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


