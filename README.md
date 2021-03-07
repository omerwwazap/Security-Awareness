# Malware-Removal-Guide

Made this because for some reason lots of friends were asking about Virus/Malware removal, so this is a small guide to help them out.

## Disclaimer

- The following instructions are recommendations only.
- Give Windows Defender a try as your main Anti-Virus program,
    - It is more than adequate for consumers.
    - Much better than running a free AV suite that is of lesser quality or plans to sell your personal habits for profit (MCafee, Avast, AVG, etc)

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
   2. What it does;
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

Below this line is for more advanced/tech literate people and if you have contacted me as a friend and are still experiencing problems, its time to contacted me again.

---
**If the above do not solve your problem do the following.**

1. Run [Sophos HitmanPro](http://get.hitmanpro.com/)
   1. Very cool malware scanner.
2. Will be aded later 2 [Trend-Micro Rootkitbuster](https://www.bleepingcomputer.com/download/trend-micro-rootkitbuster/)
3. Will be aded later 3 [Trend Micro HouseCall](https://www.trendmicro.com/en_us/forHome/products/housecall.html)
4. Will be aded later 4 [Kaspersky Virus Removal Tool](https://www.kaspersky.com/downloads/thank-you/free-virus-removal-tool)
5. Will be aded later 5 [ESET Online Scanner](https://www.eset.com/us/home/online-scanner/?intcmp=intrw)

**Note:** If a virus/malware has stopped you from browsing the web or downloading files, you can try running the [NetAdapter Repair Tool](https://www.bleepingcomputer.com/download/netadapter-repair-all-in-one/) with all options checked.

## Helpful and Specialized Tools

- uBlock Origin Browser Extension (Blocks ads)
- https://www.reddit.com/r/antivirus/wiki/index#wiki_specialized_tools
- **Adware Cleaner**
  - Malwarebytes [AdwCleaner](https://downloads.malwarebytes.com/file/adwcleaner)
- **Anti-Rootkit Program**
  - [GMER Anti Rootkit](http://www.gmer.net/#files)
  - From Kaspersky Lab [TDSSKiller](https://usa.kaspersky.com/downloads/tdsskiller)
  - McAfee [McAfee RootKitRemover](https://www.mcafee.com/enterprise/en-us/downloads/free-tools/rootkitremover.html)

## Ransomware Decryption and Identification Tools

- Identifying 
    - **NoMoreRansom.org and EUROPOL** - [Crypto Sheriff](https://www.nomoreransom.org/crypto-sheriff.php?lang=en)
    - **Malwarehunterteam**-  [Ransomware Identification](https://id-ransomware.malwarehunterteam.com/)
- Decryption
  1. **Avast** - [Ransomware Decryption Tools](https://www.avast.com/ransomware-decryption-tools)
  2. **Emsisoft** - [Ransomware Decryption Tools](https://www.emsisoft.com/ransomware-decryption-tools/)
     - Has a very nice and easy to use Ransomware Identifier
  3. **Eset** - [Stand-Alone Malware Removal Tools](https://support.eset.com/en/kb2372-stand-alone-malware-removal-tools)
  4. **Kaspersky Lab** - [Ransomware Decryption Tools](https://noransom.kaspersky.com/)
  5. **NoMoreRansom.org and EUROPOL** - [Decryption Tools](https://www.nomoreransom.org/en/decryption-tools.html)
  6. **McAfee** - [McAfee Ransomware Recover (Mr2)](https://www.mcafee.com/enterprise/en-us/downloads/free-tools/ransomware-decryption.html)
  7. **AVG** - [Ransomware Decryption Tools](https://www.avg.com/en-ww/ransomware-decryption-tools)
  8. **QuickHeal** - [Ransomware Decryption Tool](https://www.quickheal.com/free-ransomware-decryption-tool/)
  9. Old Github Repo for Decryption Tools - [All-in-One Ransomware Decryption Tools](https://github.com/jamestiotio/NoMoreRansom)
  10. Old Github Repo for Decryption Tools - [Ransomware Decryptor List](https://github.com/alternat0r/Ransomware-Decryptor-List)
  11. **Cisco Talos Github Repo** - [Decryption Tools](https://github.com/Cisco-Talos?q=decryptor&type=&language=)
  12. **Heimdal Security Blog** - [Decryption Tools List](https://heimdalsecurity.com/blog/ransomware-decryption-tools/)
- Help by Forum - List
  1. [Major Geeks Forum](https://forums.majorgeeks.com/)
  2. [Malware Removal Forum](https://www.malwareremoval.com/forum/)
  3. [Bleeping Computer Virus, Spyware, Malware, & PUP Removal Guides](https://www.bleepingcomputer.com/virus-removal/)
  4. [Bleeping Computer Forum](https://www.bleepingcomputer.com/forums/f/79/security/)
  5. [MalwareTips](https://malwaretips.com/)
  6. [**Malwarebytes** Forum](https://forums.malwarebytes.com/)
  7. [Tech Spot Forum](https://www.techspot.com/community/forums/virus-and-malware-removal.28/)
  8.  [Malwaretips - Malware Removal Help](https://malwaretips.com/categories/malware-removal-help.9/)


**NOTE:** Many security companies, including some of the ones listed above, have additional ransomware decryptors available, but do not list them publicly. If you have a system affected by ransomware, contact your security software provider for the latest information and assistance.
## References

- Amazing Info by [r/techsupport Wiki Site](https://rtech.support/)
- [r/techsupport Wiki](https://www.reddit.com/r/techsupport/wiki/index)
- Very in-depth info by [r/antivirus Wiki](https://www.reddit.com/r/antivirus/wiki/index)
- [Cool Web Tools for analysis or testing](https://www.reddit.com/r/antivirus/wiki/index#wiki_web_tools)
- [Second-Opinion Scanners](https://www.reddit.com/r/antivirus/wiki/index#wiki_second-opinion_scanners)
