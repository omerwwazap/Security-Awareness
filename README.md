# Malware-Removal-Guide

Made this because for some reason lots of friends were asking about Virus/Malware removal, so this is a small guide to help them out.

## Disclaimer

- The following instructions are recommendations only.

## Pre-requisites for These to Work

- System that successfully boots
- **Do NOT use this guide if your system has a form of malware that encrypts your files**
  - For that go [here](#for-ransomware-type-malware-to-do) but it will be better if you contact a professional.
- **For Windows only**
- All tools should be run in Normal Mode (not Safe Mode) unless you are unable to boot Normal Mode, or if the scans fails in Normal Mode.
- All tools must be run under an Administrator account.
- **Before you start** go into your browser’s extensions and remove all suspicious items' if there are any.
- **Before you start** remove any default search providers and unusual homepage, if there are any.

## Tools to Run

1. Download and run [rkill](https://www.bleepingcomputer.com/download/rkill/dl/10/)
   1. Could take a couple minutes to run.
   2. What rkill does;
      - Kills running malicious processes
      - Removes policies in the registry that prevent normal OS operation.
2. Download an updated copy of [Malwarebytes](https://www.malwarebytes.com/mwb-download/thankyou/) and turn on the [Scan for Rootkits](https://i.imgur.com/5lLJB3R.png)
   1. Run the scan an wait for it to finnish.
   2. What it does;
      1. Removes the vast majority of infections.
      2. Has built-in repair tools to fix damage done by malware.
3. Download and run [Malwarebytes ADWCleaner 8](https://downloads.malwarebytes.com/file/adwcleaner)
   1. Removes majority of adware, Toolbars, and Browser hijacks.
   2. Scans for bloatware & pre-installed software and lets you quarantine any or all of it
   3. Fixes proxy settings changed by malware
   4. Removes certain non-default browser settings

Below this line is for more advanced/tech literate people and if you have contacted me as a friend and are still experiencing problems, its time to contacted me again.

---
**If the above do not solve your problem do the following list By; [Second-Opinion Scanners](https://www.reddit.com/r/antivirus/wiki/index#wiki_second-opinion_scanners)**

1. Run [Sophos HitmanPro](http://get.hitmanpro.com/)
   1. Very cool malware scanner.
2. Will be aded later 2 [Trend-Micro Rootkitbuster](https://www.bleepingcomputer.com/download/trend-micro-rootkitbuster/)
3. Will be aded later 3 [Trend Micro HouseCall](https://www.trendmicro.com/en_us/forHome/products/housecall.html)
4. Will be aded later 4 [Kaspersky Virus Removal Tool](https://www.kaspersky.com/downloads/thank-you/free-virus-removal-tool)
5. Will be aded later 5 [ESET Online Scanner](https://www.eset.com/us/home/online-scanner/?intcmp=intrw)

**Note:** If a virus/malware has stopped you from browsing the web or downloading files, you can try running the [NetAdapter Repair Tool](https://www.bleepingcomputer.com/download/netadapter-repair-all-in-one/) with all options checked.

## Helpful and Specialized Tools (To Do)

- uBlock Origin Browser Extension (Blocks ads)
- https://www.reddit.com/r/antivirus/wiki/index#wiki_specialized_tools

## For Ransomware Type Malware (To Do)

1. Will be aded later 2
2. https://www.reddit.com/r/antivirus/wiki/index#wiki_anti-ransomware_tools
3. https://rtech.support/books/safety-and-security/page/ransomware
4. https://www.nomoreransom.org/en/decryption-tools.html
5. https://www.mcafee.com/enterprise/en-us/downloads/free-tools/ransomware-decryption.html
6. https://heimdalsecurity.com/blog/ransomware-decryption-tools/
7. https://noransom.kaspersky.com/
8. https://www.avg.com/en-ww/ransomware-decryption-tools
9. https://www.avast.com/ransomware-decryption-tools
10. https://www.quickheal.com/free-ransomware-decryption-tool/
11. https://www.emsisoft.com/ransomware-decryption-tools/

**NOTE:** Many security companies, including some of the ones listed above, have additional ransomware decryptors available, but do not list them publicly. If you have a system affected by ransomware, contact your security software provider for the latest information and assistance.

## Do not use any of these programs (To Do)

- https://rtech.support/books/software-we-recommend/page/blacklist
- https://rtech.support/books/software-we-recommend/page/windows-maintenance

## References

- Amazing Info by [r/techsupport Wiki Site](https://rtech.support/)
- [r/techsupport Wiki](https://www.reddit.com/r/techsupport/wiki/index)
- Very in-depth info by [r/antivirus Wiki](https://www.reddit.com/r/antivirus/wiki/index)
- [Cool Web Tools for analysis or testing](https://www.reddit.com/r/antivirus/wiki/index#wiki_web_tools)
- 
