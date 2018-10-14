---
title: "Common Errors with unc0ver"
---

Restarts, crashes, resprings, and other issues may occur. This post documents the most common of these. For answers to other questions about unc0ver, read [the unc0ver FAQ]({% post_url 2018-10-13-unc0ver-faq %}).

## VFS Doesn't Work

Follow this guide, [contributed by Cryptic](https://discordapp.com/channels/349243932447604736/500765231891611649/500808505561710594):

![Cryptic's Method to Enable VFS](https://cdn.discordapp.com/attachments/481925396284047360/500800864454311950/image0.png)

## Rebooting at 1/48

Rebooting at 1/48 is unpatchable and means the kernel panicked or the exploit failed ([source](https://discordapp.com/channels/349243932447604736/500765231891611649/500795084594216970)):

> **SwagMaster#2291**  
> Reboots at 1/48 is the exploit failing/kernel panicking. This cannot be fixed by pwn. Either keep trying, or wait for certain services to host a signed and entitled version

## Rebooting at 30/48

Step 30 is the APFS remount. This is an intended part of the jailbreak ([source](https://discordapp.com/channels/349243932447604736/500765231891611649/501114594421374978)).