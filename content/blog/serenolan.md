---
title: "SerenoLan - How To"
date: 2023-03-13T17:50:00+01:00
tags: ["Coding"]
featured: true
---
## Why?
Using a program called [ZeroTier](https://www.zerotier.com/) I created a virtual network that I can use to host all of my servers and such.

## How?
The setup process on my end took... a lot.

But on your end it should be easy enough!
Just run this command in Powershell:
```
iex ((New-Object System.Net.WebClient).DownloadString('https://cdn-sereno.pages.dev/files/scripts/serenolan-setup.ps1'))
```
If you follow what the script says, you'll have access to the network!

That's it!

I'm going to use this method to host various stuff such as game servers (eg. Minecraft)