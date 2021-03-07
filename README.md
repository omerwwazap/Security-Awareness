# Malware-Removal-Guide

Made this because for some reason lots of friends were asking about Virus/Malware removal so this is a small guide to help them out.

## Disclaimer

- The following instructions are recommendations only.

## Pre-requisites for These to Work

- System that successfully boots
- **Do NOT use this guide if your system has a form of malware that encrypts your files**
  - For that use this [x](x)
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

If these do not solve your problem do the following

1. Run [Sophos HitmanPro](http://get.hitmanpro.com/)
   1. Very cool malware scanner.
