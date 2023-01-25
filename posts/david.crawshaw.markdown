---
title: David Crawshaw
summary: Co-founder, CTO (Tailscale)
date: 2021-06-07
categories:
- bsd
- developer
- linux
- mac
- windows
---

### Who are you, and what do you do?

I am co-founder and CTO of [Tailscale][]. I like to write code and help others write code.

### What hardware do you use?

My setup grew to deal with 2020. I have four computers:

- [MacBook Pro][macbook-pro] 16"
- 2014 [iMac][] 5k
- Headless [AMD Threadripper 1950X][ryzen-threadripper-1950x]
- 1.5U Embedded [EPYC NAS/router][e301-9d-8cn4]

### And what software?

My primary development machine is the MacBook Pro 16". I have a lot of feelings about [macOS][]: it is astonishingly painful for developers, but makes up for it with a consistent experience for users. To be a programmer is to be both, so I pick macOS for the good fonts and reasonably-consistent experience that adapts to decades of changing hardware.

The laptop is mostly plugged into an external screen. I find laptops to be mostly a disappointment. Each week I check to see if an iMac 5k with the new CPU line has been released.

The 2014 iMac 5k I dedicate to video conferencing, mostly [Hangouts][google-hangouts] and [Zoom][zoom.2]. It got pulled out of mothballs in early 2020. Microphones are important, so I have an [Elgato Wave:3][wave-3] and open ear headphones. I also attach the back camera of an [iPad Pro][ipad-pro]. Using a dedicated machine lets me turn away from my work to focus on who I am talking to. Also on large calls I don't have to listen to a laptop fan trying to keep up.

As I can't pin down the latency characteristics of WiFi, I ethernet to all of my computers. Cutting a few milliseconds out of audio lag makes conversations (which WiFi introduces... randomly) makes a difference.

The Headless AMD Threadripper is running [Proxmox][proxmox-ve]. My main [Debian][] environment runs as a VM here, along with various Windows test VMs, and an [Ubuntu][] VM running matlab for my SO. Mostly I connect over ssh to Unix, occasionally RDP. When I switch away from programming in [Go][], I switch to this machine to run slow compilers (like llvm).

All the sockets between my computers are over Tailscale, so whenever I grab the laptop and leave the house, the connections to my VMs and NAS remain stable. I use the [sharing](https://tailscale.com/blog/sharing-over-tailscale/ "A post about the sharing feature of Tailscale.") feature to give friends and family access to the NAS. This also doubles as an exercise in [eating your own dog food](https://en.wikipedia.org/wiki/Eating_your_own_dog_food "The Wikipedia entry for dogfooding.").

Debian is a decent programming environment. It has some of the consistency properties like macOS, but fails unexpectedly. I tried to create an rc.local file last week, but those are gone apparently. My previous attempts to get 4k screens working on Linux failed, so I stick to 5k Mac desktops. Overall, Debian is fine.

My router / small NAS is an ongoing experiment. I switched it to Linux for disk performance but would like to get this back to [OpenBSD][]. (I miss [pf][].)

The router and Proxmox machines are attached with some QSFP+ 40gbit hardware I got off [eBay][]. It's fun! I highly recommend playing with second-hand network hardware.

For writing software I full-screen a terminal and use [Vim][]. Ctrl+Z for a shell. Every now and again I go searching for a replacement IDE. [VSCode][visual-studio-code] came closer than anything else in the last two decades to replacing Vim, but somehow I am back here.

### What would be your dream setup?

Realistically: an iMac 5k with an M-series CPU.

If I really wanted to dream: a hackable Unix system with an integrated 5k+ screen and X server, and the OS keeps up to date with improving hardware without moving things around on the screen or changing keyboard shortcuts. But that dream seems to be getting further away.

[debian]: https://www.debian.org/ "A Linux distribution."
[e301-9d-8cn4]: http://web.archive.org/web/20220603190641/https://www.supermicro.com/en/aplus/system/embedded/as-e301-9d-8cn4.cfm "An embedded computer system."
[ebay]: https://www.ebay.com/ "An auction service."
[go]: https://golang.org/ "A compiled programming language."
[google-hangouts]: https://hangouts.google.com/ "A voice, video and text chat service."
[imac]: https://www.apple.com/imac/ "An all-in-one computer."
[ipad-pro]: https://en.wikipedia.org/wiki/IPad_Pro "An iOS tablet."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[openbsd]: http://www.openbsd.org/ "An open-source operating system emphasising security and cryptography."
[pf]: http://www.openbsd.org/faq/pf/filter.html "A TCP packet filter included with OpenBSD."
[proxmox-ve]: https://www.proxmox.com/en/proxmox-ve "Server management software for virtual machines."
[ryzen-threadripper-1950x]: http://web.archive.org/web/20201118103346/https://www.amd.com/en/products/cpu/amd-ryzen-threadripper-1950x "A CPU."
[tailscale]: https://tailscale.com/ "A VPN service."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
[vim]: https://www.vim.org/ "A command-line text editor."
[visual-studio-code]: https://code.visualstudio.com/ "A development IDE."
[wave-3]: https://www.elgato.com/en/wave-3 "A microphone."
[zoom.2]: https://zoom.us "Video conferencing software."
