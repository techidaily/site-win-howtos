---
title: Diagnosing and Resolving Failed Installation of Windows 10 Updates Efficiently
date: 2025-01-02T19:20:20.406Z
updated: 2025-01-07T03:41:44.526Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Resolving Failed Installation of Windows 10 Updates Efficiently
excerpt: This Article Describes Diagnosing and Resolving Failed Installation of Windows 10 Updates Efficiently
thumbnail: https://thmb.techidaily.com/ef756af67baaa63e6513047560b51e7a06317e95c3578e612a362286e500591b.jpg
---

## Resolving Unregistered Class Errors on Your Windows 10 PC - Solutions Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a90d415e22e7.jpg)

 If you want to open an app or program on your Windows 10, but if fails, and you’re seeing this error saying: **Class not registered** . Reset assured, you’re not alone. Many Windows users encounter this error. More importantly, you can fix it easily by yourself.

 This error occurs on your Windows 10 mainly due to the app or the program with**unregistered DLL files** . You can probably fix it by these following solutions:

 **Try one at a time:**

1. [  Fix DCOM(Distributed Component Object Model) errors ](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 1. Fix DCOM%28Distributed Component Object Model%29 errors)
2. [ Re-register ExplorerFrame.dll file](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 2. Re-register ExplorerFrame.dll file)
3. [ Start Internet Explorer ETW Collector Service](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 3. Start Internet Explorer ETW Collector Service)
4. [ Set Windows Photo Viewer as a default image viewer ](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 4. Set Windows Photo Viewer as a default image viewer)
5. [ Disable iCloud](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 5. Disable iCloud) ``

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Go to **Component Services**  \> **Computers**  \> **My Computer**  on the Component Services window. Then double-click on **DCOM Config** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

4) Open the app again to see if it goes fine.

``

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

``

``

`` 3) Click **Default apps**  on the left pane. Then on the right pane, scroll down to click **Reset**  under the **Reset to the Microsoft recommended defaults**  section.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7-11.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

4) Open the app again to see if it goes fine.

 Note: If you’ve installed iCloud on your Windows 10, you can try the fix below if all the fixes above don’t help.

## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Open the app again to see if it goes fine.

That’s it!

 Hopefully you have got your Windows 10 out of Class not registered error.

[](https://tools.techidaily.com/drivereasy/download/)

[](https://tools.techidaily.com/drivereasy/download/) [](https://tools.techidaily.com/drivereasy/download/)

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://win-howtos.techidaily.com/descubre-tus-habilidades-de-edicion-de-video-con-el-mejor-editor-para-windows-y-mac-compras-seguros-exclusivas-ofertas/"><u>¡Descubre Tus Habilidades De Edición De Video Con El Mejor Editor Para Windows Y Mac: Compras Seguros, Exclusivas Ofertas!</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-turbocharge-your-photos-windows-11-edition/"><u>[New] 2024 Approved Turbocharge Your Photos Windows 11 Edition</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-strategies-for-effective-youtube-comment-engagement/"><u>[Updated] 2024 Approved Strategies for Effective YouTube Comment Engagement</u></a></li>
<li><a href="https://win-howtos.techidaily.com/caf-wav-movavi/"><u>CAF WAV 무료 스트리밍: 이웃에서 원특유 방법은 Movavi!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conversione-libera-del-formato-video-3gpp-in-avi-online-utilizzando-zamzar-servizio-gratuito-e-facile-da-usare/"><u>Conversione Libera Del Formato Video 3GPP in AVI Online Utilizzando Zamzar – Servizio Gratuito E Facile Da Usare!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decouvrez-les-plus-performants-outils-dedition-imagee-musicaux-en-2024-choix-expert/"><u>Découvrez Les Plus Performants Outils D'Edition Imagée Musicaux en 2024 - Choix Expert!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortlessly-change-your-mov-videos-to-avi-no-cost-no-hassle-with-online-tools/"><u>Effortlessly Change Your MOV Videos to AVI - No Cost, No Hassle with Online Tools!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-for-checking-and-updating-graphics-card-driver-versions-with-nvidia/"><u>Expert Tips for Checking & Updating Graphics Card Driver Versions with NVIDIA</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-and-speedy-convert-avis-to-gifs-quickly-with-our-online-tool/"><u>Free and Speedy: Convert AVIs to Gifs Quickly with Our Online Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guia-instrutivo-para-tirar-fotos-da-serie-rolante-em-um-pc-com-windows-e-10/"><u>Guia Instrutivo Para Tirar Fotos Da Série Rolante Em Um PC Com Windows E 10</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavis-learning-tools-and-tips-a-valuable-guide-for-effective-study-strategies/"><u>Movavi's Learning Tools & Tips: A Valuable Guide for Effective Study Strategies</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-ultimate-guide-to-leading-cloud-credentials-featured-on-zdnet/"><u>The Ultimate Guide to Leading Cloud Credentials , Featured on ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-list-of-6-student-favorites-apps-to-boost-homework-efficiency/"><u>The Ultimate List of 6 Student Favorites: Apps to Boost Homework Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformation-libre-de-raw-a-ligne-claire-avec-movavi/"><u>Transformation Libre De RAW À Ligne Claire Avec Movavi</u></a></li>
<li><a href="https://some-approaches.techidaily.com/turn-the-last-scenes-first-with-android-for-2024/"><u>Turn the Last Scenes First with Android for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-the-capabilities-a-deep-dive-into-the-linksys-ea9500-high-performance-router-review/"><u>Unveiling the Capabilities: A Deep Dive Into the Linksys EA9500 High-Performance Router Review</u></a></li>
</ul></div>

