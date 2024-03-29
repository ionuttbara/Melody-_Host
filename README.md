# **This project is depreciated and it moved to the Script Project!** **Link for updated file** **https://github.com/ionuttbara/melody_windows/blob/main/ublockfilter.txt**

Melody-_Host
Host for uBlock Origin Extension
<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/jbara2002/Melody-_Host/master/logo.png" alt="ArminC uBlock Settings"></a>
</h1>

<h4 align="center">A high-quality Hosts config built for everyone.</h4>
      
<p align="center">
  <a href="#about">About</a> •
  <a href="#installation">Installation</a> •
  <a href="#updating">Updating</a> •
  <a href="#features">Features</a> •
  <a href="#sources">Sources</a> •
  <a href="#license">License</a>
</p>

---

## About

<table>
<tr>
<td>
  
**Melody Hosts for uBlock ** is a _configuration_ file  for **uBlock Origin** which consists of several **high-quality** *filters* that aim to **block** **ads**, **pop-ups**, **trackers**, **malicious addresses** and **decreases** the number of loaded **elements**, thus **loading** the pages **faster**.

</td>
</tr>
</table>

## Installation

##### Downloading and installing steps:
* **[Download](https://raw.githubusercontent.com/jbara2002/Melody-_Host/main/ublock-backup.txt)** the latest version of the settings.
  * Make sure that you got **[uBlock Origin](https://github.com/gorhill/uBlock#installation)** extension.
* Open _uBlock₀_ **dashboard**.
  * See **[how to open the dashboard](https://github.com/gorhill/uBlock/wiki/Dashboard)**.
* At the bottom, in _Backup/Restore_ section, press `Restore from file...`
  * See **[the dashboard settings](https://github.com/gorhill/uBlock/wiki/Dashboard:-Settings)**.
* Select the `ublockbackup.txt` (from .zip) and press **OK**.

## Updating

When a **new version** is out, you have **two methods** to _update_:

##### 1. You have edited the settings based on your preference:
* Check the new [commits](https://github.com/jbara2002/Melody-_Host) and **update** the settings **manually** by relying on the _commits_.

##### 2. You haven't edited the settings (or at least not so much):
* **Delete everything** (or make sure to **replace the files** when it asks).
* **Redo** the [installation](https://github.com/jbara2002/Melody-_Host#installation) steps.
* _After setup_, **change your preference** settings back (if it is the case).

The _settings_ are **updated** (at a random time), so make sure you **come back** here to **check** for **updates**.

## Features

|           |  🔰 Melody Hosts for Ublock Settings | ◾ Other uBlock₀ settings  |
| --------------------------    | :----------------: | :-------------: |
| Blocks ads                    |         ✔️         |        〰️       |
| Blocks pop-ups                |         ✔️         |        〰️       |
| Blocks trackers               |         ✔️         |        〰️       |
| Blocks annoyances             |         ✔️         |        〰️       |
| Blocks fake-news            |         ✔️         |        〰️       |
| Blocks cookies dialogs           |         ✔️         |        〰️       |
| Blocks Romanian (pro-Russian Romanian news media websites where RomaniaTV or Antena3 are examples)            |         ✔️         |        〰️       |
| Blocks malware                |         ✔️         |        〰️       |
| Blocks coin miners            |         ✔️         |        ❌        |
| Blocks +18                    |         ✔️         |        ❌        |
| Has only useful filters       |         ✔️         |        ❌        |
| Has only recent filters       |         ✔️         |        ❌        |
| Blocks Rick&Roll links        |         ✔️         |        ❌        |
| Optimizes Youtube Recommandations       |         ✔️         |        ❌        |
| Optimizes Reddit Recommandations       |         ✔️         |        ❌        |
| Optimizes Twitch Recommandations       |         ✔️         |        ❌        |
| Blocks analytics and metrics          |         ✔️         |        〰️       |

## Sources

#### Built-in hosts
|               **Name**            |            **Credits**           |                                                                              **Block**                                                                              |                                           **Source**                                           |
|:---------------------------------:|:--------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
| uBlock Filters (uAssets)          | Raymond Hill                     | Ads, adware, trackers, resource abusers and page breaking.                                                                                                          | [LINK](https://github.com/uBlockOrigin/uAssets/tree/master/filters)                            |
| Adguard Base                      | AdGuard Team                     | Ads from websites with English content.                                                                                                                             | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/EnglishFilter/sections)       |
| EasyList                          | EasyList Team                    | Adverts from international webpages, including unwanted frames, images and objects.                                                                                 | [LINK](https://easylist.to/)                                                                   |
| AdGuard Tracking Protection       | AdGuard Team                     | Online counters and web analytics tools.                                                                                                                            | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/TrackParamFilter/sections)    |
| AdGuard URL Tracking Protection   | AdGuard Team                     | Filter that enhances privacy by removing tracking parameters from URLs.                                                                                             | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/TrackParamFilter/sections)    |
| Block access to LAN               | Gwarser                          | Public internet sites from digging into your local LAN files, and can also help mitigate DNS rebind attacks.                                                        | [LINK](https://github.com/gwarser/filter-lists)                                                |
| EasyPrivacy                       | EasyList Team                    | Web bugs, tracking scripts and information collectors.                                                                                                              | [LINK](https://github.com/easylist/easylist/tree/master/easyprivacy)                           |
| URLhaus - Malicious URL Blocklist | Ming Di Leom                     | Malicious websites that are being used for malware distribution.                                                                                                    | [LINK](https://gitlab.com/curben/urlhaus-filter)                                               |
| AdGuard Annoyances filter         | AdGuard Team                     | Cookie notices, third-party widgets and in-page pop-ups.                                                                                                            | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/AnnoyancesFilter/sections)    |
| EasyList Cookie List              | EasyList Team                    | Cookie and privacy warnings.                                                                                                                                        | [LINK](https://fanboy.co.nz/index.html)                                                        |
| uBlock - Annoyances               | Raymond Hill                     | Annoyances.                                                                                                                                                         | [LINK](https://github.com/uBlockOrigin/uAssets/tree/master/filters)                            |
| MVPS HOSTS                        | Mike                             | Parasites, hijackers and unwanted adware/spyware programs.                                                                                                          | [LINK](http://winhelp2002.mvps.org/hosts.htm)                                                  |

#### Custom
|                          **Name**                          |              **Credits**             |                                                                   **Blocks**                                                                     |                                              **Source**                                           |
|:----------------------------------------------------------:|:------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|
| Malware Domains Immortal                                   | RiskAnalytics                        | Domains that are known to be used to propagate malware.                                                                                          | [LINK](https://malwaredomains.com/?page_id=66)                                                    |
| Better                                                     | Ind.ie                               | Unethical web sites.                                                                                                                             | [LINK](https://better.fyi)                                                                        |
| OpenPhish Phishing Feed                                    | OpenPhish Community                  | Phishing sites.                                                                                                                                  | [LINK](https://www.openphish.com/index.html)                                                      |
| Steven Black's ad-hoc list                                 | Steven Black                         | Additional sketch domains.                                                                                                                       | [LINK](https://github.com/StevenBlack/hosts/tree/master/data/StevenBlack)                         |
| Porn Blocklist Light                                       | Chad Mayfield                        | Porn sites that appear on Alex Top 1M site list.                                                                                                 | [LINK](https://github.com/chadmayfield/my-pihole-blocklists/tree/master/lists)                    |
| Fanboy Addon - Notification General Block                  | EasyList Team                        | General notifications.                                                                                                                           | [LINK](https://github.com/easylist/easylist/tree/master/fanboy-addon)                             |
| Fanboy Addon - Notification General Hide                   | EasyList Team                        | General notifications element.                                                                                                                   | [LINK](https://github.com/easylist/easylist/tree/master/fanboy-addon)                             |
| Fanboy Addon - Notification Thirdparty                     | EasyList Team                        | Thirdparty notifications.                                                                                                                        | [LINK](https://github.com/easylist/easylist/tree/master/fanboy-addon)                             |
| Badd Boyz Hosts                                            | Mitchell Krog                        | Spyware, adware, malware, click-jacking, porn sites and reduces bandwidth use.                                                                   | [LINK](https://github.com/mitchellkrogza/Badd-Boyz-Hosts)                                         |
| SomeoneWhoCares                                            | Dan Pollock                          | Spyware, certain pop-up traps, user tracking, and most advertising.                                                                              | [LINK](http://someonewhocares.org/hosts/zero)                                                     |
| I Don't Want to Download Your Browser                      | DandelionSprout                      | Browser upgrade notifications.                                                                                                                   | [LINK](https://github.com/DandelionSprout/adfilt)                                                 |
| Browse websites without logging in                         | DandelionSprout                      | Log-in notifications.                                                                                                                            | [LINK](https://github.com/DandelionSprout/adfilt)                                                 |
| Fanboy's Enhanced Tracking List                            | EasyList Team                        | Common tracking scripts.                                                                                                                         | [LINK](https://fanboy.co.nz/filters.html)                                                         |
| NoCoin Filter List                                         | hoshsadiq                            | Nrowser based miners such as coin-hive.                                                                                                          | [LINK](https://github.com/hoshsadiq/adblock-nocoin-list)                                          |
| Spam404                                                    | Cameron Dawe                         | Online scams.                                                                                                                                    | [LINK](https://github.com/Spam404/lists)                                                          |
| Not on my shift!                                           | Marcos Del Sol Vives                 | Phishing and malware sites                                                                                                                       | [LINK](https://orca.pet/notonmyshift/)                                                            |
| Web Annoyances Ultralist - Ad Placeholder Filters          | Yourduskquibbles                     | Empty advertising placeholders.                                                                                                                  | [LINK](https://github.com/yourduskquibbles/webannoyances/tree/master/filters)                     |
| Web Annoyances Ultralist - Modal Overlay Filters           | Yourduskquibbles                     | Interstitial modal overlay elements.                                                                                                             | [LINK](https://github.com/yourduskquibbles/webannoyances/tree/master/filters)                     |
| Web Annoyances Ultralist - Newsletter Subscription Filters | Yourduskquibbles                     | Newsletter & other subscription cosmetic elements.                                                                                               | [LINK](https://github.com/yourduskquibbles/webannoyances/tree/master/filters)                     |

## License

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)
