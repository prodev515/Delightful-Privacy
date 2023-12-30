# Delightful Privacy [![delightful](https://codeberg.org/LinuxCafeFederation/awesome-alternatives/raw/branch/master/delightful-badge.png)](https://codeberg.org/teaserbot-labs/delightful)

This is a collection of operating systems, online services and other miscellaneous tools to help the average user fight for their privacy and security online. Use in combination with [Awesome-Alternatives](https://gitlab.com/linuxcafefederation/awesome-alternatives) for a truely open and free online experience.

## Table of contents

- [Operating Systems](#operating-systems)
- [Web Browsers](#web-browsers)
- [Secure Communications](#secure-communications)
- [Email](#email)
- [VPN](#vpn)

# [Operating Systems](https://en.wikipedia.org/wiki/Operating_system)

### [Fedora](https://getfedora.org/)
Fedora uses Security-Enhanced Linux by default, which implements a variety of security policies, including mandatory access controls, which Fedora adopted early on. Fedora provides a hardening wrapper, and does hardening for all of its packages by using compiler features such as position-independent executable (PIE). [Wikipedia](https://en.wikipedia.org/wiki/Fedora_operating_system)

### [Pop!_OS](https://pop.system76.com/)
Pop!_OS provides full out-of-the-box support for both AMD and Nvidia GPUs. It is regarded as an easy distribution to set-up for gaming, mainly due to its built-in GPU support. Pop!_OS provides default disk encryption, streamlined window and workspace management, keyboard shortcuts for navigation as well as built in power management profiles. The latest releases also have packages that allow for easy setup for TensorFlow and CUDA. [Wikipedia](https://en.wikipedia.org/wiki/Pop!_OS)

### [Debian](https://www.debian.org/)
Debian is one of the oldest operating systems based on the Linux kernel. The project is coordinated over the Internet by a team of volunteers guided by the Debian Project Leader and three foundational documents: the Debian Social Contract, the Debian Constitution, and the Debian Free Software Guidelines. New distributions are updated continually, and the next candidate is released after a time-based freeze. [Wikipedia](https://en.wikipedia.org/wiki/Debian)

### [openSUSE Tumbleweed](https://software.opensuse.org/distributions/tumbleweed) - [Rolling Release!](https://en.wikipedia.org/wiki/Rolling_release)
Upstream rolling release of [SuSe Enterprise Linux](https://www.suse.com/products/server/) that uses [openQA](https://open.qa/) before pushing updates to the system. Enables [AppArmor](https://www.apparmor.net/) by default but allows the selection and usage of Security-Enhanced Linux during install. Features the robust system management utility [YaST](https://yast.opensuse.org/).

### **For enhanced security**

### [Qubes OS](https://www.qubes-os.org/)
Qubes OS is a security-focused desktop operating system that aims to provide security through isolation. Virtualization is performed by Xen, and user environments can be based on Fedora, Debian, Whonix, and Microsoft Windows, among other operating systems. [Wikipedia](https://en.wikipedia.org/wiki/Qubes_OS)

### [Tails](https://tails.boum.org/)
Tails, or The Amnesic Incognito Live System, is a security-focused Debian-based Linux distribution aimed at preserving privacy and anonymity. All its incoming and outgoing connections are forced to go through Tor, and any non-anonymous connections are blocked. 
[Wikipedia](https://en.wikipedia.org/wiki/Tails_(operating_system)).

### [Whonix](https://www.whonix.org/)
Whonix  is a Debian GNU/Linux–based security-focused Linux distribution. It aims to provide privacy, security and anonymity on the internet. The operating system consists of two virtual machines, a "Workstation" and a Tor "Gateway", running Debian GNU/Linux. All communications are forced through the Tor network to accomplish this. [Wikipedia](https://en.wikipedia.org/wiki/Whonix)

# [Web Browsers](https://en.wikipedia.org/wiki/Web_browser)

## For Desktop

### [Firefox](https://www.mozilla.org/) Needs manual tweaking to be more secure! Use [arkenfox](https://github.com/arkenfox/user.js/wiki)
Firefox, is a free and open-source web browser developed by the Mozilla Foundation and its subsidiary, the Mozilla Corporation. [Wikipedia](https://en.wikipedia.org/wiki/Firefox) <br>
Recommended addons: [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) | [Https Everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/) | [Privacy Possum](https://addons.mozilla.org/en-US/firefox/addon/privacy-possum/) | [NoScript](https://addons.mozilla.org/en-US/firefox/addon/noscript/) | [CanvasBlocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/) | [ClearURLs](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) | 

### [LibreWolf](https://librewolf-community.gitlab.io/)
A fork of Firefox, focused on privacy, security and freedom
Same addons as above.

### [Tor](https://www.torproject.org/)
Tor is free and open-source software for enabling anonymous communication. The name derived from the acronym for the original software project name "The Onion Router". Tor directs Internet traffic through a free, worldwide, volunteer overlay network consisting of more than seven thousand relays to conceal a user's location and usage from anyone conducting network surveillance or traffic analysis. Using Tor makes it more difficult to trace Internet activity to the user. [Wikipedia](https://en.eikipedia.org/wiki/Tor_%28anonymity_network%29)<br>
TorProject advises against using addons with Tor Browser, however you can use FireFox addons, and the interent without adblock sucks. <br>
My Recommendation: [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) 

### [UnGoogled-Chromium](https://github.com/Eloston/ungoogled-chromium)
Without signing in to a Google Account, Chromium does pretty well in terms of security and privacy. However, Chromium still has some dependency on Google web services and binaries. In addition, Google designed Chromium to be easy and intuitive for users, which means they compromise on transparency and control of internal operations.

ungoogled-chromium addresses these issues in the following ways:

- Remove all remaining background requests to any web services while building and running the browser

- Remove all code specific to Google web services

- Remove all uses of pre-made binaries from the source code, and replace them with user-provided alternatives when possible.   Disable features that inhibit control and transparency, and add or modify features that promote them (these changes will almost always require manual activation or enabling). [GitHub](https://github.com/Eloston/ungoogled-chromium)  <br>
Recommended addons: [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) | [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp) | [NoScript](https://chrome.google.com/webstore/detail/noscript/doojmbjmlfjjnbmnoijecmcbfeoakpjm)

## For mobile

### [Bromite](https://www.bromite.org/) Android Only
Bromite is a Chromium fork with ad blocking and privacy enhancements; take back your browser! [Bromite](https://www.bromite.org)

### [Fennec F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/)
Fennec F-Droid is based on the latest Firefox release (codenamed Fenix).
It has proprietary bits and telemetry removed.<br>
Recommended addon: [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)

### Firefox Focus [Android](https://play.google.com/store/apps/details?id=org.mozilla.focus) - [iOS](https://apps.apple.com/us/app/firefox-focus-privacy-browser/id1055677337)
Firefox Focus is a free and open-source privacy-focused browser from Mozilla, available for Android and iOS. [Wikipedia](https://en.wikipedia.org/wiki/Firefox_Focus)<br>
Recommended addon: [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)

### [Tor](https://www.torproject.org/) Browser for mobile [Android](https://play.google.com/store/apps/details?id=org.torproject.torbrowser) - [iOS](https://apps.apple.com/us/app/onion-browser/id519296448)
Tor protects your privacy on the internet by hiding the connection
between your Internet address and the services you use. We believe Tor
is reasonably secure, but please ensure you read the instructions and
configure it properly. [GitHub](https://github.com/guardianproject/tor-android)
<br>
TorProject advises against using addons with Tor Browser, however you can use FireFox addons, and the interent without adblock sucks. <br>
My Recommendation: [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) 

## [Secure Communications](https://en.wikipedia.org/wiki/Secure_communication)

### [Jami](https://jami.net/)
Jami is completely peer-to-peer and doesn't require a server for relaying data between users. Jami is a GNU project backed by the Free Software Foundation, useing state of the art end-to-end encryption with perfect forward secrecy for all communications and comply with the X.509 standard.

### [Threema](https://threema.ch/en/) 
The messenger that puts security and privacy first. Pay once, chat forever. No collection of user data. Open Source.

### [Matrix](https://matrix.org/)

Matrix is an open standard for interoperable, decentralised, real-time communication.. The most popular way to interact with matrix is through [Element](https://element.io/) which was formerly called Riot. [matrix](https://matrix.org/)

### [Signal](https://signal.org/en/) **Requires a phone number.**
Share Without Insecurity State-of-the-art end-to-end encryption (powered by the open source Signal Protocol) keeps your conversations secure. We can't read your messages or listen to your calls, and no one else can either. Privacy isn’t an optional mode — it’s just the way that Signal works. Every message, every call, every time. [Signal](https://signal.org/en/)

### [Session](https://getsession.org/)
Session is an end-to-end encrypted messenger that minimises sensitive metadata, designed and built for people who want absolute privacy and freedom from any form of surveillance. [getsession](https://getsession.org/)

### [Briar](https://code.briarproject.org/briar/briar)
Briar is a messaging app designed for activists, journalists, and anyone else who needs a safe, easy and robust way to communicate. [briarproject](https://code.briarproject.org/briar/briar)

# [Email](https://en.wikipedia.org/wiki/Email)

### [Mailbox](https://mailbox.org/) - [You have to manually setup encrypted mailbox](https://kb.mailbox.org/display/MBOKBEN/The+Encrypted+Mailbox)
There are many ears listening on the Internet, which is why all our services require mandatory SSL/TLS-encrypted data transmission. For additional security, we also use enhanced (green) security certificates ("EV") by the independent SwissSign trust service provider from Switzerland (Check the padlock symbol in your web browser's URL field). But this is just the beginning – there is so much more that we do. [Mailbox](https://mailbox.org/)

### [Disroot](https://disroot.org)
Disroot is a decentralized cloud-based service that allows you to store your files and communicate with one another. Established by a privacy-focused organization of volunteers, if we look at Disroot as an email provider specifically, it stands out thanks to its emphasis on security with a completly free open-source approach. [ProPrivacy](https://proprivacy.com/email/review/disroot)

### [ProtonMail](https://protonmail.com/)
ProtonMail is an end-to-end encrypted email service founded in 2013 in Geneva, Switzerland by scientists who met at the CERN research facility. ProtonMail uses client-side encryption to protect email content and user data before they are sent to ProtonMail servers, unlike other common email providers such as Gmail and Outlook.com. The service can be accessed through a webmail client, the Tor network, or dedicated iOS and Android apps. [Wikipedia](https://en.wikipedia.org/wiki/ProtonMail)

# [Search Engine](https://en.wikipedia.org/wiki/Web_search_engine)

### [Qwant](https://www.qwant.com/)
Choosing Qwant is using a search engine that respects its users. We do not keep any track of your queries. No one is able to know what you are looking for on the Internet. Your search results are not tracked. You browse the web without filters and any targeted ads. [Wikipedia](https://en.wikipedia.org/wiki/Qwant)

### [Searx](https://searx.me)
searx is a free metasearch engine, available under the GNU Affero General Public License version 3, with the aim of protecting the privacy of its users. To this end, searx does not share users' IP addresses or search history with the search engines from which it gathers results. Tracking cookies served by the search engines are blocked, preventing user-profiling-based results modification. By default, searx queries are submitted via HTTP POST, to prevent users' query keywords from appearing in webserver logs. [Wikipedia](https://en.wikipedia.org/wiki/Searx) - Find public instances of searx here [searx.space](https://searx.space/) and always read the Privacy Policy of an instance before using it.

### [Startpage](https://en.wikipedia.org/wiki/Startpage.com)
Startpage is a web search engine that highlights privacy as its distinguishing feature. Previously, it was known as the metasearch engine Ixquick, At that time, Startpage was a variant service. Both sites were merged in 2016. [Wikipedia](https://en.wikipedia.org/wiki/Startpage.com)

### [YaCy](https://yacy.net)
YaCy is a free distributed search engine, built on principles of peer-to-peer (P2P) networks. Its core is a computer program written in Java distributed on several hundred computers, as of September 2006, so-called YaCy-peers. Each YaCy-peer independently crawls through the Internet, analyzes and indexes found web pages, and stores indexing results in a common database (so called index) which is shared with other YaCy-peers using principles of P2P networks. It is a free search engine that everyone can use to build a search portal for their intranet and to help search the public internet clearly. [Wikipedia](https://en.wikipedia.org/wiki/YaCy)

# [VPN](https://en.wikipedia.org/wiki/Virtual_private_network)
## **If you need anonymity and privacy online use [Tor](https://torproject/org) instead, if you are looking to bypass a geo-restriction, don't trust public WiFi, or are looking to Torrent, a VPN will help you.**

### [Mullvad](https://mullvad.net)
Mullvad is an open-source commercial virtual private network (VPN) service based in Sweden. Launched in March 2009, Mullvad operates using the WireGuard and OpenVPN protocols. Mullvad accepts Bitcoin and Bitcoin Cash for subscriptions in addition to conventional payment methods. 

No email address or other identifying information is requested during Mullvad's registration process. Rather, a unique 16-digit account number is anonymously generated for each new user. This account number is henceforth used to log in to the Mullvad service.

The TechRadar review notes that "The end result of all this is you don't have to worry about how Mullvad handles court requests to access your usage data, because, well, there isn't any." [Wikipedia](https://en.wikipedia.org/wiki/Mullvad)

### [ProtonVPN](https://protonvpn.com)
ProtonVPN utilizes OpenVPN (UDP/TCP) and the IKEv2 protocol, with AES-256 encryption. The company has a strict no-logging policy for user connection data, and also prevents DNS and Web-RTC leaks from exposing users' true IP addresses. ProtonVPN also includes Tor access support and a kill switch to shut off Internet access in the event of a lost VPN connection.

In January 2020, ProtonVPN became the first VPN provider to release its source code on all platforms and conduct an independent security audit. ProtonVPN is the only VPN to do so, even though experts say this is a crucial factor in deciding whether to trust a VPN service. [Wikipedia](https://en.wikipedia.org/wiki/ProtonVPN)


## For information about alternatives to software and services.
If you are looking for alternatives to proprietary services like Discord and Facebook, or an open-source alternative to Photoshop, check out our list about [Awesome-Alternatives](https://gitlab.com/linuxcafefederation/awesome-alternatives)

## Links to Linux Café

- [Linux Café Website](https://linuxcafefederation.github.io/LinuxCafe/)
- [Linux Café Discord](https://discord.gg/YY4zrNR)
- [Linux Café Matrix](https://matrix.to/#/#linuxcafe:linuxcafe.chat)
- [Linux Café Telegram](https://t.me/joinchat/Mn4RpxM6KrSLQMBL78yloQ)
- [Linux Café Reddit](https://reddit.com/r/linuxcafe)

# Mirrors

- Codeberg: https://codeberg.org/LinuxCafeFederation/Delightful-Privacy
- GitLab (main): https://gitlab.com/linuxcafefederation/Delightful-Privacy
- GitHub: https://github.com/LinuxCafeFederation/Delightful-Privacy
