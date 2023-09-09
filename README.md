<p align="center">
  <img src="https://github.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/blob/master/images/firewall-icon.png" width="128" height="128"/>
</p>

<h1 align="center">Summer CMS Block Bad Crypto Filter Lists</h1>

<p align="center"><img src="https://github.com/Summer-CMS-Modules/sc-vendor-packages-parser/blob/master/assets/images/cover.jpg" /></p>

This is a filter list to block "browser-based crypto mining and injected malware sites". Currently there are a few websites added into the lists. If you see other websites supporting these deeds, then feel free to raise an **Issue** or **Pull request** for it to be taken care of.

<p align="center">
    <img src="/assets/images/stars.svg" alt="stars" />
    <img src="/assets/images/badges/cms.png" height="20" alt="summer cms" />
    <img src="/assets/images/badges/type-package.png" height="20" alt="package" />
    <a href="https://github.com/Summer-CMS/Awesome#readme"><img src="https://github.com/Summer-CMS/Ecosystem/blob/master/assets/images/awesome-badge.svg"></a>
    <a href="https://circleci.com/gh/Summer-CMS-Modules/sc-vendor-packages-parser"><img src="/assets/images/circleci.svg"></a>
    <img src="/assets/images/code.svg" />
    <a href="https://github.com/Summer-CMS-Modules/sc-module-template" title="GitHub action to setup PHP"><img alt="GitHub Actions status" src="/assets/images/work-flow.svg"></a>
    <a href="https://github.com/Summer-CMS/Welcome#minimum-system-requirements" title="PHP Versions Supported"><img alt="PHP Versions Supported" src="https://img.shields.io/badge/php-8.0%20to%208.2-777bb3.svg?logo=php&logoColor=white&labelColor=555555"></a>  
    <a href="https://github.com/Summer-CMS/Welcome#minimum-system-requirements"><img src="https://img.shields.io/badge/Laravel-9.0%20(LTS)-777bb3.svg?logo=laravel&logoColor=white&labelColor=555555&color=orange" /></a>
    <a href="https://github.com/Summer-CMS/Welcome#minimum-system-requirements"><img src="https://img.shields.io/badge/Symfony-6.0%20to%206.4-777bb3.svg?logo=symfony&logoColor=white&labelColor=555555&color=yellow" /></a>
    <a href="CODE_OF_CONDUCT.md"><img src="/assets/images/conduct.svg" alt="conduct" /></a>
    <a href="https://github.com/Summer-CMS-Modules/sc-documentation"><img src="/assets/images/docs.svg" alt="docs" /></a>
    <a href="https://www.gnu.org/licenses/gpl-3.0"><img src="https://img.shields.io/badge/License-GPLv3-blue.svg" /></a>
    <img alt="GitHub release (latest by date including pre-releases)" src="https://img.shields.io/github/v/release/Summer-CMS-Modules/sc-vendor-packages-parser?include_prereleases">
</p>

<br>

## Table of Contents 📑

..

## Installation

### AdBlock Filter

Make sure you have an adblocker installed in your desktop or mobile browsers that uses [Adblock Plus](https://adblockplus.org/)' filter list:

- ![AdBlock](https://i.imgur.com/3KbyifF.png) [AdBlock](https://getadblock.com) (Active by default)
- ![AdBlock Plus](https://i.imgur.com/kPRCfhu.png) [Adblock Plus](https://adblockplus.org/)
- ![uBock Origin](https://i.imgur.com/PSFuzKb.png) [uBlock Origin](https://github.com/gorhill/uBlock)
- ![AdGuard Browser Extension](https://i.imgur.com/zmMHq2j.png) [AdGuard Browser Extension](https://adguard.com/en/adguard-browser-extension/overview.html) (Included by default)
- ![AdBlock Browser](https://i.imgur.com/6pkmjA0.png) [Adblock Browser](https://adblockbrowser.org/) for **Android** and **iOS** devices
- ![Brave Browser](https://user-images.githubusercontent.com/831718/32730079-e80c013c-c853-11e7-83b4-7443bc489581.png) [Brave Browser](https://www.brave.com) (Included by default)
- ![Opera Browser](https://i.imgur.com/bP0t9xc.png) [Opera Browser](https://www.opera.com) (Included by default from Opera 50)

For a thorough explanation on how to add the to your adblocker, open one of the help guides found in this folder: https://github.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/tree/master/docs

There are two methods to install into your adblocker:

1. Click the link below:

- [https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/master/src/lists/nomalware.txt&title=Crypto%20Malware%20Block%20Lists](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/master/src/lists/nomalware.txt&title=Crypto%20Malware%20Block%20Lists)

2. Copy and paste the link in the settings of the ad-blocker:

- https://raw.githubusercontent.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/master/src/lists/nomalware.txt

## Hosts based blocking

For the blocking based on the [HOSTS file](<https://en.wikipedia.org/wiki/Hosts_(file)>) use the below link:

- [https://raw.githubusercontent.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/master/src/lists/hosts.txt](https://raw.githubusercontent.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/master/src/lists/hosts.txt)

### hosts

You can simply copy and paste the contents of above file into your hosts file. The locations of your hosts file depends on your system:

- Linux: `/etc/hosts`
- MacOS: `/etc/hosts`
- Windows: `C:\Windows\System32\drivers\etc\hosts`

Whichever OS you use, you will require escalated privileges to edit the file (either use `sudo` for Linux/MacOS or administrative account on Windows). Or you can use command below for linux

```
sudo -- sh -c 'curl -sS https://raw.githubusercontent.com/Summer-CMS-Vendor-Packages/sc-crypto-malware-block-lists/master/src/lists/hosts.txt >> /etc/hosts'
```

### Adblockers

- ![DNS66](https://i.imgur.com/XFBuNqj.png) [DNS66](https://github.com/julian-klode/dns66) for **Android**
- ![Blokada](https://i.imgur.com/XB1l9aG.png) [Blokada](http://blokada.org/) for **Android**
- ![AdAway](https://i.imgur.com/AdWsIxw.png) [AdAway](https://github.com/AdAway/AdAway) for **Android**
- ![AdGuard](https://i.imgur.com/zmMHq2j.png) [AdGuard](https://adguard.com) for **All Platforms**

### Perimeter blocking

You may use the hosts file with below applications to block these miners on whole networks. Simply add the link to the above hosts file in each system.

- ![pfSense](https://i.imgur.com/ElyO5Ie.png) [pfSense](https://www.pfsense.org/) with [pfBlockerNG](https://www.tecmint.com/install-configure-pfblockerng-dns-black-listing-in-pfsense/)
- ![Pi-hole](https://i.imgur.com/0mgKKma.png) [Pi-hole](https://pi-hole.net)

---

_Mining (Opt-in **and** opt-out) will be blocked by default. If you see that mining is important, you would have to [whitelist](https://adblockplus.org/filters#whitelist) the website you actually want to support._
