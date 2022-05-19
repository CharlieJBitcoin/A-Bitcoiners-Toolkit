# A Bitcoiner's Toolkit
A curated list of software, services and guides essential for every bitcoiner.

## Contents
- [Intro](#introduction)
  - [Why?](#why)
  - [Who is this for?](#who-is-this-for)
  - [Disclaimer](#disclaimer)
- [The Non-Bitcoin Toolkit](#the-non-bitcoin-toolkit)
  - [Operating Systems](#operating-systems)
  - [Email](#email)
  - [Home Networking & Storage](#home-networking-and-storage)
  - [Hosted VPN Providers](#hosted-vpn-providers)
  - [Password and 2FA](#password-and-2fa)
  - [PGP](#pgp)
  - [Messaging and Social](#messaging-and-social)
  - [Podcast Apps](#podcast-apps)
  - [Maps and Navigation](#maps-and-navigation)
  - [Other Apps](#other-apps)
- [The Bitcoin Toolkit](#the-bitcoin-toolkit)
  - [Bitcoin Dashboards & Explorers](#bitcoin-dashboards-and-explorers)
  - [Privacy Focused Bitcoiners](#privacy-focused-bitcoiners)
- [Other Privacy Lists](#other-curated-privacy-lists)

## Introduction
### Why?
When you start to use Bitcoin, the incentive model for your own personal privacy and security changes. Securing your personal data can seem like a "pointless" endeavour for some, but once who start self-custodying Bitcoin, that attitude inevitably shifts to caring deeply about your own privacy and the security of your stack.

This list is aimed to provide an easy-to-access archive of software and services which any bitcoiner will find useful, aiming to replace many of the free (but detrimental to your privacy) services which are commonly used.

There are already [lots](#other-curated-privacy-lists) of privacy focused lists out there. What hopefully sets this one apart is the focus on application for bitcoiners. Where possible, links to how these suggestions can be applied to your Bitcoin software stack have been provided 

### Who Is This For?
This is aimed at those just starting out on their privacy journey, and those looking to expand their toolkit with new recommendations.

### Disclaimer
This is by no means comprehensive! V1 of this list is simply [myself](https://twitter.com/charliejbitcoin) and [@BitcoinTimO](https://twitter.com/bitcointimo) thinking of what we use day-to-day. Suggestions and improvements are more than welcome!

---

# The Non-Bitcoin Toolkit

## Operating Systems

### PC :computer:

  **Default**

  - Windows - Improved: [Win10 Ameliorated](https://ameliorated.info/), not verified so use with caution!

  **Alternatives**

  - [PopOS](https://pop.system76.com/) - Good daily driver, suitable for gaming, encrypts drives, familiar UI    - [Tails](https://tails.boum.org/) - Excellent privacy assurances, Tor by default, boot from USB (portable), runs on RAM.
  - [Qubes](https://www.qubes-os.org/intro/) - Security focus, compartmentalises your activity.
  - [Mint](https://linuxmint.com/) - Good daily driver, available in cut down [xcfe](1https://linuxmint-installation-guide.readthedocs.io/en/latest/choose.html) version (good for older devices).
  - [Ubuntu](https://ubuntu.com/) - Good daily driver, often people's first experience of Linux.

  **Guides**

  Learn more about Linux:
  - [FOSSLinux.com](https://www.fosslinux.com/42688/getting-started-with-linux-operating-system.htm) guide, the basic of Linux and how it works.

  Learn Linux as you go:
  - 402 Payment Required [video series](https://youtube.com/playlist?list=PLmoQ11MXEmagwLs0NtjadkyVwc-CFfr4h) how to set up a full node using the Linux terminal from basics.
  - Ministry of Nodes [tutorials](https://www.youtube.com/playlist?list=PLCRbH-IWlcW290O0N0lQV6efxuCA5Ja8c) setting up a full node and other software on Ubuntu.
  - Hackernoon [article](https://hackernoon.com/a-complete-beginners-guide-to-installing-a-bitcoin-full-node-on-linux-2018-edition-cb8e384479ea) guide on setting up a node on Kubuntu from basics.
  - [RaspiBolt](https://raspibolt.org/), a guide to setting up a full core and lightning node.

### Phone :iphone:

  **Default**

  - Android - Improved: Techlore [Video](https://www.youtube.com/watch?v=dMWEym0KPcA)
  - iOS - Improved: Techlore [Video](https://www.youtube.com/watch?v=d2bJVKcIEg0)

  **Alternatives**

  - [CalyxOS](https://calyxos.org/) - de-googled android, good daily driver with good privacy trade off balance. 
  - [GrapheneOS](https://grapheneos.org/) - security focused phone OS, wider device compatibility than CalyxOS.

  **Guides**
  - Bitcoin Q&A's [guide](https://bitcoiner.guide/calyxos/) to CalyxOS setup.
  - EconoAlchemist's [guide](https://bitcoinmagazine.com/guides/how-to-establish-mobile-bitcoin-privacy-with-a-pixel-4a-and-calyxos) to Calyx and whirlpooling.
  - Lopp's [Blog](https://blog.lopp.net/grapheneos-phone-privacy-protection/) post on GrapheneOS.
  - Citadel Dispatch [e.0.3.4](https://bitcointv.com/w/m2Jc9AtRyo2LUwE65bYdpr) with Sethforprivacy.

---

## Email
### Providers :envelope:

  **Default**

  - [Gmail](https://protonmail.com/blog/google-privacy-problem/) - Improved: Stop other apps from reading your emails ([1](https://www.trustedreviews.com/news/how-to-stop-people-reading-your-gmail-3500379)). 

  **Alternatives**

  - [Tutanota](https://mail.tutanota.com/) - open source e2ee email provider
  - [ProtonMail](https://protonmail.com/) - open source e2ee email provider

  **Learn**

  - [PGP encrypt](https://www.inverse.com/article/27013-how-to-encrypt-email-pgp-key) your emails. Good foressaginf actual people.

### Aliasing :bust_in_silhouette:

  - [SimpleLogin](https://simplelogin.io/) - Create unlimited aliases (paid version only, 15 aliases for free) for your base email, to never reuse an email again.

---

## Phone Numbers

  - [Silent.link](https://silent.link/) (US only)
  - Buying PAYG sim cards
  - [Quackr](https://quackr.io/)

---

## Home Networking and Storage

### Networking

  **Default**

  - ISP provided router w/ stock settings

  **First Steps**

  - Enhance the privacy of ISP router by changing factory settings [1](https://www.cgparker.com/home-network-security-router-settings/)

  **Alternatives**

  - [pfSense](https://www.pfsense.org/) router
  - [PiHole](https://pi-hole.net/)

  **Guides**

  - NetworkChuck's [video](https://youtu.be/lUzSsX4T4WQ) on setting up pfSense
  - Citadel Dispatch [CD.0.3.6 episode](https://citadeldispatch.com/cd36/) with @jamesob and @\_k3tan

### Cloud and storage

  **Default**

  - Google Cloud / iCloud

  **Alternatives**

  - [Nextcloud](http://nextcloud.com/)
  - [Syncthing](https://syncthing.net/) (backups/file syncing)

---

## Hosted VPN Providers

  **Hosted VPN**

  - [Mullvad](https://mullvad.net/en/)
  - [IVPN](https://www.ivpn.net/)

  **Sorta VPN**

  - [ZeroTier](https://www.zerotier.com/)

  **Guides**

  - [ZeroTier for your node](https://www.youtube.com/watch?v=oM0HvY_x_Hc&list=PLCRbH-IWlcW290O0N0lQV6efxuCA5Ja8c&index=12) by @\_k3tan

---

## Password and 2FA

### Password Managers

  - KeePass ([Windows](https://keepass.info/)); KeePassDX ([Android](https://www.keepassdx.com/))
  - [Bitwarden](https://www.keepassdx.com/)

### 2FA

  - [Aegis](https://getaegis.app/)

---

## PGP

  - [OpenKeychain](https://www.openkeychain.org/)

---

## Messaging and Social

### Social Media

  - [Infinity](https://f-droid.org/en/packages/ml.docilealligator.infinityforreddit/) (Reddit)
  - [Fritter](https://f-droid.org/en/packages/com.jonjomckay.fritter) (Twitter)
  - [Nextpipe](https://newpipe.net/) (YouTube)

### Messaging

  **Default**

  - SMS
  - WhatsApp

  **Alternatives**

  - [Signal](https://www.signal.org/)
  - [Matrix](https://matrix.org/) ([Element](https://matrix.org/docs/projects/client/element) is a good client)
  - [Briar](https://briarproject.org/)

  **Guides**

  - Comparison between [WhatsApp, Telegram, Signal by Techlore](https://youtu.be/3Fvzjf2349c), and tips to get the [most out of Signal](https://duckduckgo.com/?q=techlore+signal&t=brave&iax=videos&ia=videos&iai=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DUSf56JdGrTI), also by Techlore.

### Calls & Conferencing

  **Default**

  - Cellular calls
  - Google Meet / MS Teams / Skype

  **Alternatives**

  - [Jitsi](https://jitsi.org/), and go to [meet.jit.si](https://meet.jit.si/) to set a call up
  - Signal voice/video call

---

## Podcast Apps

  - AntennaPod
  - Fountani
  - Breez

---

## Maps and Navigation

  - Organic Maps

---

## Other Apps

  **App Stores**

  - F-Droid
  - Aurora

  **Tracking Prevention**

  - Exodus

---

# The Bitcoin Toolkit

## Bitcoin Dashboards and Explorers
### Dashboard

  - [Clark Moody's Dashboard](https://bitcoin.clarkmoody.com/dashboard/)
  - [Bitbo.io](https://bitbo.io)

### Block Explorer

  **Default**

  - Blockchain.com

  **Alternatives**

  - [OXT.me](https://oxt.me)
  - [Mempool.space](https://mempool.space)

  **Self-Host**

  - [RPC Explorer](https://github.com/janoside/btc-rpc-explorer)

---

## Privacy Focused Bitcoiners

### A-E
- [@BitcoinQ_A](https://twitter.com/bitcoinq_a) ([bitcoiner.guide](https://bitcoiner.guide/))
- [@BrotherRabbit_](https://twitter.com/brotherrabbit_)
- [@BTCGandalf](https://twitter.com/BTCGandalf) ([This Is Bitcoin](https://www.youtube.com/thisisbitcoinyt))
- [@dammkewl](https://mobile.twitter.com/dammkewl)
- [@Diverter_NoKYC](https://twitter.com/diverter_nokyc) ([diverter.hostyourown.tools](https://diverter.hostyourown.tools/))
- [@Din_J7](https://twitter.com/Din_J7)
- [@EconoAlchemist](https://twitter.com/econoalchemist) ([burn the bridge](https://www.econoalchemist.com/))
- [@ErgoBTC](https://mobile.twitter.com/ErgoBTC)

### F-J
- [@heady_wook](https://mobile.twitter.com/heady_wook)

### K-O
- [@_k3tan](https://mobile.twitter.com/_k3tan)
- [@KYC3](https://twitter.com/KYCfree)
- [@LaurentMT](https://mobile.twitter.com/LaurentMT)
- [@MarketsBylili](https://twitter.com/Marketsbylili)
- [@maxtannahill](https://mobile.twitter.com/maxtannahill)
- [@noisymouse27f](https://mobile.twitter.com/noisymouse27f)
- [@ODELL](https://twitter.com/ODELL) ([Matt Odell](https://mattodell.keybase.pub/))
- [@openoms](https://twitter.com/openoms)
- [@orangedmike](https://twitter.com/orangedmike)
- [@OxoUtx](https://mobile.twitter.com/OxoUtx)

### P-T
- [@RoninDojoNode](https://mobile.twitter.com/RoninDojoNode)
- [@Satrinity](https://twitter.com/satrinity402)
- [@SovrnBitcoiner](https://twitter.com/sovrnbitcoiner)
- [@TDevD](https://twitter.com/SamouraiDev)

### U-Z
- [@wanderinKing072](https://mobile.twitter.com/wanderinKing072)

---

# Other Curated Privacy Lists

- [Privacy Respecting](https://github.com/nikitavoloboev/privacy-respecting)
- [PrivacyTools.io](https://www.privacytools.io/)

---

