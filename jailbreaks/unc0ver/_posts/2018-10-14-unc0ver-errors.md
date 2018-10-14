---
title: "Common Errors with unc0ver"
---

Restarts, crashes, resprings, and other issues may occur. This post documents the most common of these. For answers to other questions about unc0ver, read [the unc0ver FAQ]({% site.github.url %}/unc0ver-faq).

## VFS Doesn't Work

Follow this guide, [originally contributed by Cryptic](https://discordapp.com/channels/349243932447604736/500765231891611649/500808505561710594):

1. Turn off wifi and bluetooth
2. airplane mode
3. kill all apps
4. clear ram
5. open app, close app from app switcher, open it again
6. lock device
7. raise to wake after 10 seconds
8. lock device for 30 seconds then unlock without raise to wake.
9. jailbreak
10. profit

## Rebooting at 1/48

Rebooting at 1/48 is unpatchable and means the kernel panicked or the exploit failed ([source](https://discordapp.com/channels/349243932447604736/500765231891611649/500795084594216970)):

> **SwagMaster#2291**  
> Reboots at 1/48 is the exploit failing/kernel panicking. This cannot be fixed by pwn. Either keep trying, or wait for certain services to host a signed and entitled version

## Rebooting at 30/48

Step 30 is the APFS remount. This is an intended part of the jailbreak ([source](https://discordapp.com/channels/349243932447604736/500765231891611649/501114594421374978)).