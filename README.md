# Malware-Removal-Guide

[![Maintenance](https://img.shields.io/badge/Repo_Status-Semi_Active-yellow.svg)](https://shields.io/) [![HitCount](http://hits.dwyl.com/omerwwazap/omerwwazap/Malware-Removal-Guide.svg)](http://hits.dwyl.com/omerwwazap/omerwwazap/Malware-Removal-Guide) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

For Turkish Version [Click Here](https://github.com/omerwwazap/Malware-Removal-Guide/blob/main/README-tr.md).

Made this because for some reason lots of friends were asking about Virus/Malware removal, so this is a small guide to help them out.

- [Malware-Removal-Guide](#malware-removal-guide)
  - [Disclaimer](#disclaimer)
  - [Pre-requisites for These to Work](#pre-requisites-for-these-to-work)
  - [Tools to Run](#tools-to-run)
  - [Helpful and Specialized Tools](#helpful-and-specialized-tools)
  - [Ransomware Decryption and Identification Tools](#ransomware-decryption-and-identification-tools)
  - [References](#references)

## Disclaimer

- The following instructions are recommendations only.
- Give Windows Defender a try as your main Anti-Virus program;
  - It is more than adequate for consumers.
    - Much better than running a free AV suite that is of lesser quality or plans to sell your personal habits for profit (MCafee, Avast, AVG, etc)
- **For Windows only**

## Pre-requisites for These to Work

- System that successfully boots.
- **Do NOT use this guide if your system has a form of malware that encrypts your files.**
  - For that go [here](#for-ransomware-type-malware-to-do) but it will be better if you contact a professional.
- All tools should be run in Normal Mode (not Safe Mode) unless you are unable to boot Normal Mode, or if the scans fails in Normal Mode.
- All tools must be run under an Administrator account.
- Browser Related - **Before you start**
  - Go into your browser’s extensions and remove all suspicious items, if there are any.
  - Remove any default search providers and unusual homepages, if there are any.

## Tools to Run

1. Download and run [rkill](https://www.bleepingcomputer.com/download/rkill/dl/10/)
   1. Could take a couple minutes to run.
   2. Do not reboot your computer after running RKill as the malware programs will start again.
   3. What it does;
      - Kills running malicious processes
      - Removes policies in the registry that prevent normal OS operation.
2. Download an updated copy of [Malwarebytes](https://www.malwarebytes.com/mwb-download/thankyou/) and turn on the [Scan for Rootkits](https://i.imgur.com/5lLJB3R.png)
   1. Run the scan an wait for it to finnish.
   2. What it does;
      - Removes the vast majority of infections.
      - Has built-in repair tools to fix damage done by malware.
3. Download and run [Malwarebytes ADWCleaner 8](https://downloads.malwarebytes.com/file/adwcleaner)
   1. What it does;
      - Removes majority of adware, Toolbars, and Browser hijacks.
      - Scans for bloatware & pre-installed software and lets you quarantine any or all of it
      - Fixes proxy settings changed by malware
      - Removes certain non-default browser settings
4. Run [Sophos HitmanPro](http://get.hitmanpro.com/)
   1. Very cool malware scanner.

----

Below this line is for more advanced/tech literate people and if you have contacted me as a friend and are still experiencing problems, its time to contacted me again.

- Contents Below the Line
  - [Helpful and Specialized Tools](#helpful-and-specialized-tools)
  - [Ransomware Decryption and Identification Tools](#ransomware-decryption-and-identification-tools)
  - [References](#references)

[Go To Top](#malware-removal-guide)

---

**If the above do not solve your problem do the following.**

1. [Rogue Killer](https://www.adlice.com/roguekiller/#alt_download)
2. [Trend Micro HouseCall](https://www.trendmicro.com/en_us/forHome/products/housecall.html)
3. [Kaspersky Virus Removal Tool](https://www.kaspersky.com/downloads/thank-you/free-virus-removal-tool)
4. [ESET Online Scanner](https://www.eset.com/us/home/online-scanner/?intcmp=intrw)

**Note:** If a virus/malware has stopped you from browsing the web or downloading files, you can try running the [NetAdapter Repair Tool](https://www.bleepingcomputer.com/download/netadapter-repair-all-in-one/) with all options checked.

## Helpful and Specialized Tools

- **Ad Blocker**
  - uBlock Origin Browser Extension (Firefox, Chrome, Edge and Opera) [GitHub Repo](https://github.com/gorhill/uBlock)
    - <code>ublock.org</code> is not a official site.
- **Adware Cleaner**
  - Malwarebytes [AdwCleaner](https://downloads.malwarebytes.com/file/adwcleaner)
- **Anti-Rootkit Program**
  - [GMER Anti Rootkit](http://www.gmer.net/#files)
  - Trend-Micro [Rootkitbuster](https://www.bleepingcomputer.com/download/trend-micro-rootkitbuster/)
  - From Kaspersky Lab [TDSSKiller](https://usa.kaspersky.com/downloads/tdsskiller)
  - McAfee [McAfee RootKitRemover](https://www.mcafee.com/enterprise/en-us/downloads/free-tools/rootkitremover.html)
  - Malwarebytes [Anti-Rootkit](https://www.malwarebytes.com/antirootkit/)

## Ransomware Decryption and Identification Tools

| Vendor                                   | Name and Link                                        | Decryption / Identification | Notes                                  |
| ---------------------------------------- | -----------------------------------------------------| --------------------------- | --------------------------------------|
| NoMoreRansom.org and EUROPOL             | [Crypto Sheriff](https://www.nomoreransom.org/crypto-sheriff.php?lang=en)                                                  | Identification              |                                                                                                  |
| Malwarehunterteam                        | [Ransomware Identification](https://id-ransomware.malwarehunterteam.com/)                                                  | Identification              |                                                                                                  |
| Avast                                    | [Ransomware Decryption Tools](https://www.avast.com/ransomware-decryption-tools)                                           | Decryption                  |                                                                                                  |
| Emsisoft                                 | [Ransomware Decryption Tools](https://www.emsisoft.com/ransomware-decryption-tools/)                                       | Decryption                  | Has a very nice and easy to use Ransomware Identifier                                            |
| Eset                                     | [Stand-Alone Malware Removal Tools](https://support.eset.com/en/kb2372-stand-alone-malware-removal-tools)                  | Decryption                  |                                                                                                  |
| Kaspersky Lab                            | [Ransomware Decryption Tools](https://noransom.kaspersky.com/)                                                             | Decryption                  |                                                                                                  |
| NoMoreRansom.org and EUROPOL             | [Decryption Tools](https://www.nomoreransom.org/en/decryption-tools.html)                                                  | Decryption                  |                                                                                                  |
| McAfee                                   | [McAfee Ransomware Recover (Mr2)](https://www.mcafee.com/enterprise/en-us/downloads/free-tools/ransomware-decryption.html) | Decryption                  |                                                                                                  |
| AVG                                      | [Ransomware Decryption Tools](https://www.avg.com/en-ww/ransomware-decryption-tools)                                       | Decryption                  |                                                                                                  |
| QuickHeal                                | [Ransomware Decryption Tool](https://www.quickheal.com/free-ransomware-decryption-tool/)                                   | Decryption                  |                                                                                                  |
| Old Github Repo for Decryption Tools     | [All-in-One Ransomware Decryption Tools](https://github.com/jamestiotio/NoMoreRansom)                                      | Decryption                  | Long list of URLs, but the repo is 4 year old.                                                    |
| Old Github Repo for Decryption Tools - 2 | [Ransomware Decryptor List](https://github.com/alternat0r/Ransomware-Decryptor-List)                                       | Decryption                  | A similar repo to this one, but it has all the executables for decryption and it is 3 years old. |
| Cisco Talos Github Repo                  | [Decryption Tools](https://github.com/Cisco-Talos?q=decryptor&type=&language=)                                             | Decryption                  |                                                                                                  |
| Heimdal Security Blog                    | [Decryption Tools List](https://heimdalsecurity.com/blog/ransomware-decryption-tools/)                                     | Decryption                  |                                                                                                  |
| BleepingComputer                         | [Windows Ransomware Decryptor Download Exec's](https://www.bleepingcomputer.com/download/windows/ransomware-decryptors/)   | Decryption                  |

**NOTE:** Many security companies, including some of the ones listed above, have additional ransomware decryptors available, but do not list them publicly. If you have a system affected by ransomware, contact your security software provider for the latest information and assistance.

- Some Forum Lists in case you need help
  - [Major Geeks Forum](https://forums.majorgeeks.com/)
  - [Malware Removal Forum](https://www.malwareremoval.com/forum/)
  - [Bleeping Computer Virus, Spyware, Malware, & PUP Removal Guides](https://www.bleepingcomputer.com/virus-removal/)
  - [Bleeping Computer Forum](https://www.bleepingcomputer.com/forums/f/79/security/)
  - [MalwareTips](https://malwaretips.com/)
  - [**Malwarebytes** Forum](https://forums.malwarebytes.com/)
  - [Tech Spot Forum](https://www.techspot.com/community/forums/virus-and-malware-removal.28/)
  - [Malwaretips - Malware Removal Help](https://malwaretips.com/categories/malware-removal-help.9/)

## References

- Amazing Info by [r/techsupport Wiki Site](https://rtech.support/)
- [r/techsupport Wiki](https://www.reddit.com/r/techsupport/wiki/index)
- Very in-depth info by [r/antivirus Wiki](https://www.reddit.com/r/antivirus/wiki/index)
- [Cool Web Tools for analysis or testing](https://www.reddit.com/r/antivirus/wiki/index#wiki_web_tools)
- [Second-Opinion Scanners](https://www.reddit.com/r/antivirus/wiki/index#wiki_second-opinion_scanners)
- [Redirect Virus problem](https://www.2-viruses.com/how-to-fix-google-redirect-virus-browser-hijacker-problem)
- [Information on Browser Hijacker](https://www.bleepingcomputer.com/virus-removal/threat/browser-hijacker/)

[Go To Top](#malware-removal-guide)
