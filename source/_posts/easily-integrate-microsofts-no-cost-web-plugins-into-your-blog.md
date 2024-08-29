---
title: Easily Integrate Microsoft's No-Cost Web Plugins Into Your Blog
date: 2024-08-28T00:19:00.332Z
updated: 2024-08-29T00:19:00.332Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604114715.png
---

## Easily Integrate Microsoft's No-Cost Web Plugins Into Your Blog

Would you like to use Hotmail, Office Web Apps, Messenger, and more on your website domain? Here's how you can add Windows Live to your website for free. Microsoft offers a popular suite of online communications products including Hotmail and Messenger. Although Hotmail hasn't been as popular in recent years as Gmail, it is getting a refresh this summer that might make it an even better email solution. Additionally, the new Office Web Apps offer great compatibility with Office documents. While Skydrive offers 25Gb of free online file storage for all users, so Windows Live can make a great communications solution for your domain. Note**:** To signup for Windows Live for your domain, you will need to be able to add info to your WordPress.com blog or change Domain settings manually. **Getting Started** Open the Windows Live Custom Domains page (Link below) to get started adding Windows Live to your domain. Your free Windows Live account will let you create up to 500 accounts, so it's great for teams and groups that want to have customized email addresses in addition to those who just want an email account for their website. Enter your domain or subdomain you want to add to Windows Live in the box, and then select whether you want to setup Hotmail with this or now. We want to add email to our domain, so select Set up Windows Live Hotmail for my domain and click Continue. You'll need to sign in with a Windows Live ID to create the account, or choose to create a new Windows Live account associated with your domain. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image44.png) 

 Sign in with your Windows Live ID...this can be a Hotmail, Live Messenger, XBOX Live, Zune ID, or Microsoft.com account. 

![sshot-2010-06-04-[11-49-18]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604114918.png) 

 Or, enter your information to create a new Windows Live ID if you selected the second option. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image45.png) 

 Now, review your settings and make sure everything looks correct. Click the I Accept button to setup your account. 

![sshot-2010-06-04-[11-49-53]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604114953.png) 

 Your account is now fully setup, but you'll need to add or edit DNS information on your site. The steps are slightly different depending if your site is hosted on WordPress.com, on your own server, or hosting service. We'll show you how to do it on either one. 

![sshot-2010-06-04-[12-24-02]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122402.png) 

 First, though, note the information below this box. You'll see settings for your Mail setup... 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image46.png) 

 Security settings... 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image47.png) 

 And Messenger integration. Make note of the settings, especially the circled ones, as we'll need them in the next step. 

![sshot-2010-06-04-[12-24-35]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122435.png) 

**Integrate Windows Live with Your WordPress Blog** If the domain you added to Windows Live is for your [WordPress blog](https://tech-hub.techidaily.com/how-do-character-restrictions-affect-chatgpts-generated-text-outputs/), login to your WordPress dashboard in a separate browser window or tab. Click the arrow beside Upgrades, and select Domains from the menu. 

![sshot201006032200002](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot201006032200002.png) 

 Click the Edit DNS link beside the domain name you're adding to Windows Live. 

![sshot201006032200593](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot201006032200593.png) 

 In the text box on this page, enter the following, replacing **Your\_info** with your code from the Mail Setup box in your Windows Live Dashboard. Note that this is the blurred section in our screenshots. It should be a numerical code like 1234567890.pamx1.hotmail.com. 

> MX 10 **Your\_info**.pamx1.hotmail.com.

> TXT v=spf1 include:hotmail.com \~all CNAME **Your\_info** domains.live.com.

 Click Save DNS records, and your settings are saved to WordPress. Note that this will only integrate email with your WordPress account; you cannot integrate Messenger with a domain hosted on WordPress.com. 

![sshot-2010-06-04-[12-11-53]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604121153.png) 

 Finally, return to your Windows Live Settings page and click Refresh. If your settings are correct, you'll now be ready to use Windows Live on your WordPress.com domain. 

![sshot-2010-06-04-[12-24-02]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122402.png) 

**Integrate Windows Live with Your Own Server** If your website is hosted on your own server or hosting account, you'll need to take a few more steps to add Windows Live to your domain. This is fairly easy, but the steps may be different depending on your hosting company or registrar. With some hosts, you may have to contact support to have them add the MX records for you. Our site's host uses the popular cPanel for website administration, so here's how we added the MX Entries through cPanel. Login to your website's cPanel, and select MX Entry under the Mail section. 

![sshot-2010-06-04-[12-14-48]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604121448.png) 

 In the text box on this page, enter the following, replacing **Your\_info** with your code from the Mail Setup box in your Windows Live Dashboard. Note that this is the blurred section in our screenshots. It should be a numerical code like 1234567890.pamx1.hotmail.com. 

> MX 10 **Your\_info**.pamx1.hotmail.com.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image48.png) 

 Now, go back to your cPanel home, and select Advanced DNS Zone Editor under Domains. 

![sshot-2010-06-04-[12-17-11]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604121711.png) 

 Here, add a TXT record with the following info: 

| Name:     | **yoursite.com.**                |
| --------- | -------------------------------- |
| TTL:      | 3600                             |
| TXT Data: | v=spf1 include:hotmail.com \~all |

 Click Add Record and your Mail integration data is all configured. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image49.png) 

 To integrate Messenger with your own domain, you'll have to add an SRV entry to your DNS settings. cPanel doesn't have an option for this, so we had to contact our site's hosting company and they added the entry for us. Copy all of the information in the Messenger box and send it to your domain support, and they should be able to add this for you. Alternately, if you don't want or need Messenger, then you can simply skip this step. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image50.png) 

 Once all of your settings are in place, return to your Windows Live Settings page and click Refresh. If your settings are correct, you'll now be ready to use Windows Live on your WordPress.com domain. 

![sshot-2010-06-04-[12-24-02]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122402.png) 

**Create a New Email Account On Your Domain** Welcome to your new Windows Live admin page! Now you can add email accounts so you and anyone else you want can access Hotmail and the other Windows Live apps with your domain. Click Add to add an account. 

![sshot-2010-06-04-[12-25-05]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122505.png) 

 Enter an account name, which will be the email address of the account, e.g. **accountname@yourdomain.com**. Then enter the user's name and a password for the account. By default this will be a temporary password, and the user will have to change it on first log-in, but if you're setting up this account for yourself, you can uncheck the box and keep this as your standard password. 

![sshot-2010-06-04-[12-59-27]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604125927.png) 

 Now, go to [www.mail.live.com](http://www.mail.live.com), and sign in with your new email address and password. Remember, your email address is your username previously entered followed by @**yourdomain.com**. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image51.png) 

 To finish setting up the email account, enter your password, secret question and answer, alternate email, and location information. Click I accept to finish setting up your new email account. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image52.png) 

 Enter the characters in the Captcha to confirm you're a human, and click Continue. 

![sshot-2010-06-04-[13-03-35]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604130335.png) 

 Your new Hotmail inbox will now load, and you'll have a welcome email in your inbox. This works the same as normal Hotmail, except this time, your email address is with your own domain. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image53.png) 

 You can now access any of the Windows Live services from the top-level menu. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image54.png) 

 Here's an Excel Spreadsheet open in the new Office Web Apps via SkyDrive on our new Windows Live account. 

![sshot-2010-06-04-[13-32-14]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604133214.png) 

 If you setup Messenger access previously, you can now sign in to Windows Live Messenger using your new @**yourdomain.com** account as well. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image55.png) 

**Important Links** Accessing your Windows Live accounts is easy. Simply go to any Windows Live site, such as [www.hotmail.com](http://www.hotmail.com) or [www.skydrive.com](http://www.skydrive.com), and sign in with your new Windows Live ID from your domain as normal. You don't need a special address to access your account; it works just like the standard public Hotmail accounts. To administer your Windows Live for your domain, go to <https://domains.live.com/> and sign in with the Windows Live ID you used to create the account. Here you can add more users, change settings, and view usage details for the Windows Live accounts on your domain. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image56.png) 

**Conclusion** Windows Live is easy to add to your domain, and lets you create up to 500 email address for it. With the upcoming updates to Hotmail and Office Web Apps coming this summer, this can be a nice way to make your domain even more useful. And with 500 email accounts, you can easily let your team take advantage of your unique address as well. If you'd rather use Google's online applications with your domain, check out our article on how to [add free Google apps to your website or blog](https://tech-haven.techidaily.com/reliable-guide-successfully-transforming-your-kindle-books-into-epub-format-proven-methods-of-2024/). **Link** [Signup for Windows Live for Your Domain](https://domains.live.com/Signup/SignupDomain.aspx)

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-filming-to-fame-discovering-the-top-10-ladies-on-youtube/"><u>[New] 2024 Approved  From Filming to Fame  Discovering the Top 10 Ladies on YouTube</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-haste-assessment-of-windows-documents/"><u>[Updated] 2024 Approved  Haste Assessment of Windows Documents</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-quick-fire-photos-with-iphone-burst-feature/"><u>[Updated] 2024 Approved  Quick-Fire Photos with iPhone Burst Feature</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-insider-knowledge-instagrams-music-copyright-landscape-decoded/"><u>[Updated] In 2024, Insider Knowledge  Instagram's Music Copyright Landscape Decoded</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-diving-deep-into-samsung-photo-enhancers-guide/"><u>2024 Approved  Diving Deep Into Samsung Photo Enhancers Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-mastering-metaverse-mirth-humorous-digital-world-memes/"><u>2024 Approved  Mastering Metaverse Mirth  Humorous Digital World Memes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ace-the-fix-troubleshooting-and-repairing-0x80070643-error-during-windows-updates/"><u>Ace the Fix: Troubleshooting and Repairing 0X80070643 Error During Windows Updates</u></a></li>
<li><a href="https://fox-access.techidaily.com/achieving-steady-motion-video-and-photography-insights/"><u>Achieving Steady Motion  Video & Photography Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204227541-breeze-through-high-wmi-cpu-usage-woes-on-win11/"><u>Breeze Through High WMI CPU Usage Woes on Win11!</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/clearing-focus-techniques-for-blurring-meeting-backdrops/"><u>Clearing Focus  Techniques for Blurring Meeting Backdrops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/compreh-ensive-strategies-for-diagnosing-and-repairing-windows-driver-power-problem/"><u>Compreh Ensive Strategies for Diagnosing & Repairing Window's Driver Power Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210600140-constraint-a-do-not-redact-any-percentages-or-numerical-values/"><u>Constraint A: Do Not Redact Any Percentages or Numerical Values.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/deciphering-and-correcting-error-code-1068-on-your-windows-pc-solved/"><u>Deciphering and Correcting Error Code 1068 on Your Windows PC [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-and-troubleshooting-windows-blue-screen-error-0xc00x00000e9-a-step-by-step-guide/"><u>Decoding and Troubleshooting Windows Blue Screen Error 0xC00^X00000E9: A Step-by-Step Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-steps-to-setup-and-activate-a-wireless-adapter-on-windows-pcs/"><u>Direct Steps to Setup & Activate a Wireless Adapter on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-and-fix-error-144-in-livekernel-event/"><u>Expert Tips to Overcome and Fix Error 144 in LiveKernel Event</u></a></li>
<li><a href="https://video-capture.techidaily.com/fbm-transcripts-how-to-get-and-use-complete-records-for-2024/"><u>FBM Transcripts  How to Get and Use Complete Records for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-irksome-issue-of-error-code-0x800704cf-on-your-windows-pc/"><u>Fixing the Irksome Issue of Error Code 0X800704CF on Your Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-microsoft-print-to-pdf-error-a-step-by-step-guide-for-windows-10-and-11-users/"><u>Fixing the Microsoft Print to PDF Error: A Step-by-Step Guide for Windows 10 and 11 Users</u></a></li>
<li><a href="https://techidaily.com/hard-reset-vivo-y78plus-t1-edition-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Vivo Y78+ (T1) Edition in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-your-touchpad-cursor-remains-active-in-windows-11/"><u>How To Ensure Your Touchpad Cursor Remains Active In Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-honor-90-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Honor 90 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-windows-plus-shift-plus-s-working-again-on-your-pc-windows-1110/"><u>How to Get Windows + Shift + S Working Again on Your PC (Windows 11/10)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-an-unresponsive-integrated-webcam-in-the-windows-environment/"><u>How to Repair an Unresponsive Integrated Webcam in the Windows Environment</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-samsung-galaxy-a05s-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Samsung Galaxy A05s Back to Operation | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-upgrade-to-windows-11-for-2024/"><u>How to Upgrade to Windows 11  for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-windows-file-access-issues-no-more-errors/"><u>Resolve Windows File Access Issues: No More Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-steps-when-cant-reach-the-dhcp-server/"><u>Resolved: Troubleshooting Steps When Can't Reach the DHCP Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revived-stalled-audio-on-discord/"><u>Revived Stalled Audio on Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/say-goodbye-to-drawn-out-closures-solving-the-puzzle-of-a-lethargic-windows-10-shutdown/"><u>Say Goodbye to Drawn-Out Closures: Solving the Puzzle of a Lethargic Windows 10 Shutdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/shockwave-flash-and-google-chrome-collision-solutions-to-get-them-running-smoothly/"><u>Shockwave Flash and Google Chrome Collision – Solutions to Get Them Running Smoothly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-dealing-with-non-functional-winplusshiftpluss-in-windows-versions-11-and-10/"><u>Solve the Problem: Dealing With Non-Functional Win+Shift+S in Windows Versions 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-cannot-reset-this-computer-issue-in-windows-10/"><u>Solving the 'Cannot Reset This Computer' Issue in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-the-modify-rendering-api-issue-causing-dota-2-error-202/"><u>Step-by-Step Fix for the 'Modify Rendering API' Issue Causing Dota 2 Error 202</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-scrolling-issue-on-synaptics-touchpad-under-windows-ten/"><u>Step-by-Step Guide to Fix Scrolling Issue on Synaptics Touchpad Under Windows # Ten</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-reset-issues-on-your-windows-11-machine-expert-solutions/"><u>Troubleshooting and Fixing Reset Issues on Your Windows 11 Machine: Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-windows-camera-failure-error-0xa00f4292-explained/"><u>Troubleshooting Guide for Windows Camera Failure - Error 0xA00F4292 Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-speaker-issues-and-fixing-high-pitched-sounds-in-windows-os-tips-and-solutions/"><u>Troubleshooting Speaker Issues and Fixing High-Pitched Sounds in Windows OS: Tips & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-to-eliminate-screen-stuttering-on-windows-11-devices/"><u>Troubleshooting Techniques to Eliminate Screen Stuttering on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-diagnose-and-repair-driverpowerstatefailure-glitches/"><u>Ultimate Guide to Diagnose and Repair DRIVER_POWER_STATE_FAILURE Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-entry-point-missing-mistakes-on-windows-devices/"><u>Understanding and Correcting ‘Entry Point Missing’ Mistakes on Windows Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-netflix-connectivity-issues-is-it-just-you/"><u>Understanding Netflix Connectivity Issues - Is It Just You?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-does-my-windows-11-computer-activate-alone-and-how-to-fix-it/"><u>Why Does My Windows 11 Computer Activate Alone and How to Fix It?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-isnt-my-logitech-keyboard-working-on-windows-11-troubleshooting-tips/"><u>Why Isn't My Logitech Keyboard Working on Windows 11? Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-wont-my-computer-shut-down-on-windows-11-proven-methods-to-fix-and-restart-safely/"><u>Why Won't My Computer Shut Down on Windows 11? Proven Methods to Fix and Restart Safely</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-automatic-repair-loop-solved/"><u>Windows 11 Automatic Repair Loop [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-update-issue-overcome-the-0x800705b4-setup-failure-with-easy-fixes/"><u>Windows 11 Update Issue? Overcome the 0X800705b4 Setup Failure with Easy Fixes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->