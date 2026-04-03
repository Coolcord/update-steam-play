update-steam-play
=================

A quick and dirty bash script to manage and update Steam Play versions on Linux

## About update-steam-play

 update-steam-play is a simple bash script to install and update Steam Play compatibility tools.
 The purpose of this is to have a quick script that can run before/after a system update to get the latest versions of Steam Play compatibility tools for Linux. I wrote this since I wanted a tool that would simply update Proton GE in place, but also keep the last major version of each iteration of Proton.

## Sample Output
```
Fetching all Steam Play release data from GitHub...
✔ GE-Proton-Latest is already up to date (version v10-34).
✔ GE-Proton9 is already up to date (version v9-27).
✔ GE-Proton8 is already up to date (version v8-32).
✔ GE-Proton7 is already up to date (version v7-55).
✔ GE-Proton6 is already up to date (version v6.21-GE-2).
✔ GE-Proton5 is already up to date (version v5.9-GE-8-ST).
✔ GE-Proton4 is already up to date (version v4.21-GE-2).
✔ EM-Proton-Latest is already up to date (version v10.0-34).
✔ Luxtorpeda-Latest is already up to date (version v76.2.0).
✔ Boxtron-Latest is already up to date (version v0.5.4).
✔ Roberta-Latest is already up to date (version v0.1.0).
✅ All Steam Play versions are now up to date!
```

## Supported Steam Play Compatibility Tools
+ [Proton GE](https://github.com/GloriousEggroll/proton-ge-custom)
+ [Proton EM](https://github.com/Etaash-mathamsetty/Proton)
+ [Luxtorpeda](https://github.com/luxtorpeda-dev/luxtorpeda)
+ [Boxtron](https://github.com/dreamer/boxtron)
+ [Roberta](https://github.com/dreamer/roberta)

