---
title: Potential Threats when Using Microsoft Office on Apple's macOS Platform
date: 2024-08-28T00:19:29.534Z
updated: 2024-08-29T00:19:29.534Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/floating-office-app-icons-in-3d-illustration.jpg
---

## Potential Threats when Using Microsoft Office on Apple's macOS Platform

### Highlights

* Vulnerabilities in Microsoft apps on macOS could allow external access through permissions, risking privacy and data security.
* Attackers could manipulate trusted apps to perform actions without users knowing, exploiting macOS permission automation.
* Library injections in common Microsoft programs on macOS raise concerns, urging users to review app permissions and stay vigilant.

 A library injection vulnerability in Microsoft apps—Excel, OneNote, PowerPoint, Word, Outlook, and Teams—on the macOS means that they are open to external access through already-set permissions.

 This could mean that an adversary could copy the application into a controllable location and perform a library injection to use the application's entitlements. In other words, hackers could record video and sound, access personal data, or log your input on your device. What's more, they could potentially send emails through your Outlook, view photos in your Pictures folder, or, in the worst-case scenario, escalate privileges.

 Apple uses a [permissions-based](https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-oneplus-open-and-browser-drfone-by-drfone-virtual-android/)—or entitlement-based—model that [prompts customers to manually enable apps](https://techno-recovery.techidaily.com/13-best-free-hard-drive-testing-tools-july-2024/) to access certain information and tools on their device, such as their photos, contacts, camera, and microphone. Once the permission is granted, macOS remembers these settings (unless changed manually), and it is this automation that the attackers can exploit in this vulnerability.

 Although this Transparency, Consent, and Control (TCC) framework aims to protect privacy and maintain system security, it isn't foolproof. Indeed, if a trusted app is compromised, it can be manipulated to enable attackers to perform actions without the device's owner knowing it's happening. Furthermore, hardened runtime guards and [sandboxed apps](https://driver-download.techidaily.com/download-and-update-radeon-hd-7850-drivers-for-optimal-performance-in-windows-10/) are supposed to secure people's device data and resources, though a [malware](https://apple-account.techidaily.com/in-2024-can-i-remove-the-apple-watch-activation-lock-by-iphone-11-pro-max-without-the-previous-owner-by-drfone-ios/) could still find ways to bypass these measures in certain scenarios.

 According to Cisco Talos senior security research engineer, Francesco Benvenuto, Microsoft says that these issues are "low risk," claiming that some of its applications "need to allow loading of unsigned libraries to support plugins." Though this might lead macOS customers to conclude that Microsoft doesn't intend to fix the issue, Cisco Talos noted that Teams and OneNote had been updated, and no longer possess the entitlement that previously led these programs vulnerable to attack. Nevertheless, Excel, Outlook, PowerPoint, and Word remain susceptible.

 Library injections require significant technical expertise, though the fact that these weaknesses pertain to such commonly used Microsoft programs is enough to concern those who use macOS. While the real-world implications of such vulnerabilities are not yet clear—with Microsoft yet to respond to interrogation—organizations and personal users should review their app permissions and ensure they remain vigilant to unusual activity across the 365 suite.

 Source: [Cisco Talos](https://blog.talosintelligence.com/how-multiple-vulnerabilities-in-microsoft-apps-for-macos-pave-the-way-to-stealing-permissions/), [The Register](https://www.theregister.com/2024/08/19/cisco%5Ftalos%5Fmicrosoft%5Fmacos/)

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



<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->