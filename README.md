<p align="center">"<i>Those who would give up essential liberty to purchase a little temporary safety, deserve neither liberty nor safety.</i>"</p>

<p align="center"><a href="https://www.freeiconspng.com/img/5264" title="Image from freeiconspng.com"><img src="https://www.freeiconspng.com/uploads/skull-icon-25.png" width="350" alt="Skull Hd Icon" /></a></p>

# <p align="center"># xT0ddz guide to Internet Security</p>

## 🔒 &nbsp;What is it?

This repository is a collection of various materials and tools that I use every day in my work. It contains a lot of useful information gathered in one piece. It is an invaluable source of knowledge for me that I often look back on.

## :restroom: &nbsp;For whom?

For everyone, really. Here everyone can find their favourite tastes. But to be perfectly honest, it is aimed towards System and Network administrators, DevOps, Pentesters, and Security Researchers.

## 🤡 &nbsp;Current Security Analysis




### Test your [current data leakage](https://coveryourtracks.eff.org/) through your web browser
* Use this [Advanced test](https://browserleaks.com/) for more information about your data leakage

Take note of how many bits of information are being leaked as well as if your actual IP address/location is visible.


Understanding web trackers

When you visit a website, your browser makes a "request" for that site. In the background, advertising code and invisible trackers on that site might also cause your browser to make dozens or even hundreds of requests to other hidden third parties. Each request contains several pieces of information about your browser and about you, from your time zone to your browser settings to what versions of software you have installed.

At first glance, the data points that third-party trackers collect may seem relatively mundane and disparate. But when compiled together, they can reveal a detailed behavioral profile of your online activity, from political affiliation to education level to income bracket. As long as this trove of data about you is linked back to you, your online activity can be logged. Ad networks primarily rely on two methods to maintain this link: cookie tracking, and browser fingerprinting.

Cookies are small chunks of information that websites store in your browser. Their main use is to remember helpful things like your account login info, or what items were in your online shopping cart—in other words, they save your place. But they can also be misused to link all your visits, searches, and other activities on a site together. This use of cookies is a privacy violation, and browsers generally allow you to block, limit, or delete cookies. 

A digital fingerprint is essentially a list of characteristics that are unique to a single user, their browser, and their particular hardware setup. This includes information the browser needs to send to access websites, like the location of the website the user is requesting. But it also includes a host of seemingly insignificant data (like screen resolution and installed fonts) gathered by tracking scripts. Tracking sites can stitch all the small pieces together to form a unique picture, or "fingerprint," of your device.

understanding why browser security is important
https://www.makeuseof.com/tag/browser-compromises-privacy/



Browser Hardening
--Understand that this is different from PC security. VPNs and antivirus/anti-malware should be enabled at a minimum. PC security will be address ina different entry.

Which browser should I use?
Short answer: Mozilla Firefox
I rank Firefox second when put next to Tor browser, but for everyday use Firefox is your best bet.

Firefox is the only widely used web browser that is completely open-source. Anyone can examine Firefox’s source code, making sure there are no sketchy elements (like tracking software) baked into the final product. This is completely different than browsers like Chrome, and MS Edge who collect as much as they can from it's users. Out of the box, Mozilla is much more secure than it's competitors, and better yet it gives you complete control over your security. It is also relatively lightweight and won't bog down your machine by running tens of background processes. 

Firefox Hardening:
understand that you sacrifice sonvineince when you improve security
Figure out how important your privacy is to you

Excerpt from github user "arkenfox" who is the creator of broswerhardening repository that I used.
"We recommend keeping extensions to a minimum: they have privileged access within your browser, require you to trust the developer, can make you stand out, and weaken site isolation.

This list covers privacy and security related extensions only. While we believe these are the very best of the best, this can be subjective depending on your needs. We are also not saying you have to use all these extensions."

Guide I used
https://github.com/arkenfox/user.js/wiki/4.1-Extensions 












Tools for Covering your Web Browsing tracks
