update-steam-play
=================

A quick and dirty bash script to manage and update Steam Play versions on Linux

## About update-steam-play

 update-steam-play is a simple bash script to install and update Steam Play compatibility tools.
 The purpose of this is to have a quick script that can run before/after a system update to get the latest versions of Steam Play compatibility tools for Linux. I wrote this since I wanted a tool that would simply update Proton GE in place, but also keep the last major version of each iteration of Proton.

Sample output:
```
Fetching all Steam Play release data from GitHub...
✔  GE-Proton-Latest is already up to date (version 10-29).
✔  GE-Proton9-27 is already up to date.
✔  GE-Proton8-32 is already up to date.
✔  GE-Proton7-55 is already up to date.
✔  GE-Proton6-21 is already up to date.
✔  GE-Proton5-9 is already up to date.
✔  Luxtorpeda-Latest is already up to date (version v74.3.1).
✅ All Steam Play versions are now up to date!
```

## Supported Steam Play Compatibility Tools
+ Proton GE
+ Luxtorpeda
+ Boxtron
+ Roberta

