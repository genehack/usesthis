---
title: Justin Frankel
summary: Software developer (Winamp, REAPER)
date: 2012-10-02
categories:
- developer
- mac
- windows
---

### Who are you, and what do you do?

My name is [Justin Frankel](http://www.1014.org/ "Justin's website."). I have programmed for fun since I was a kid, and for fun and work since I quit college. I've made software including [Winamp][] (I wrote Winamp originally because I wanted to listen to music), and now I primarily work on [REAPER][] (digital audio workstation software, which I started making because I wanted to record music).

### What hardware do you use?

At home my main computer is a Lian Li aluminum case with a Corsair high efficiency power supply, an Asus P5Q Pro Turbo motherboard with a Q9500 CPU, 8GB RAM, Nvidia 8800GTX, and a 1TB disk. I got a $300 2560x1440 27" IPS monitor off of eBay recently (after reading [this post by Jeff Atwood](http://www.codinghorror.com/blog/2012/07/the-ips-lcd-revolution.html "An article by Jeff Atwood on IPS monitors.")), which is completely fantastic.

At the office I have a 24" [iMac][], with a 2.93GHz C2D and 4GB RAM.

I prefer to type on the original (circa 1998) PS2 [Microsoft Natural Keyboard][natural-keyboard] (not the Elite! The Elite's arrow keys are not inverted-T, and it is unusable). I have three of these, but it is a shame that newer computers do not have PS2 ports.

When I travel I use a 13" Sony Z series laptop, which I have had since early 2011. It has a 1920x1080 screen, which is fantastic for a 13" laptop, but the screen is a touch lacking on brightness, and the battery life isn't great. It is very light, though, at 3 pounds, and is quite fast (it is a dual core i7 with Turbo Boost, and uses a couple of SSDs in RAID-0). Honestly though, my wife's C2D [MacBook Air][macbook-air] really wins overall -- it feels more solid and the battery life is substantially better.

In addition to those machines, I also have an iMac G5 for PPC testing, and an older C2D [ThinkPad X60][thinkpad-x60] which has a bunch of OSes installed.

We use a couple of i7 [Mac Minis][mac-mini] for build servers -- they are plenty fast for building on both Windows and OS X, but use around 7 watts each when idle. I have two [ReadyNAS Pro][readynas-pro], each with around 4TB of storage, in two different places (home + office). These keep all of my personal audio recordings (around 2TB last I checked), pictures, and also backups of everything. They run nightly backups of our various web servers, too.

Finally, I end up doing a good deal of busy work on my [iPhone 4S][iphone-4s] -- using the mail client to move messages between IMAP accounts is pretty effective for delegating work. The calendar app is the only calendar I'll use, too.

### And what software?

**Operating Systems:**

I use [Windows 7][windows-7] and [OS X 10.6][macos] most of the time. 

I generally prefer to use Windows, and my practice for running things is to hit the start button on the keyboard, and type things that I will expect to find in the start menu. I also use Start+R, then type "cmd" to launch a command prompt, "ssh \<host\>" to run [PuTTY][putty] (which I have in my path named as ssh.exe, etc), or just a URL.

On OS X I tend to use [Terminal.app][terminal] for as much as possible, and run native applications via Spotlight (Cmd+Space).

**Development tools:**

[Git][] is completely awesome and at this point I'd be lost without it. [MSysGit][] on Windows is also quite nice in that it comes with a ton of standard gnu tools which are nice to have.

I usually use the [Visual C++ 6 IDE][visual-c-plusplus] (circa 1998), which is not perfect but also only occasionally gets in my way. Sometimes when I find myself missing a particular feature in the editor, I'll open the file in [vim][]. Occasionally I need to fire up Visual C++ 2005 for 64 bit stuff, too. The use of these older/ancient compilers is mitigated by using them along with the Intel C Compiler for release builds.

For Windows development, a completely awesome tool is [ClipX][], which is a free clipboard manager written by my friend Francis Gastellu, however he still has not fixed the Windows User Object leak that occurs when you open the paste menu (\*cough\* Francis ahem \*cough\*). It's great if you're wanting to copy various symbols or expressions for later pasting.

On OS X I'll do most of my editing in vim, but use [XCode 3][xcode] for compiling and editing projects. I haven't moved to XCode 4 yet, as I find the UI difficult to use and it does not seem to be capable of targeting OS X 10.4.

A lot of helper scripts get written in [PHP][] or [Perl][], or sometimes just normal shell scripts.

**Communications:**

We do most of our team communication via IRC. I use [mIRC][] on Windows, [X-Chat Aqua][x-chat-aqua] on OS X, or [Colloquy][colloquy-ios] on the iPhone, combined with an unreleased logging caching proxy which allows using multiple clients on multiple devices, keeping all in synchronization. 

[Pidgin][] or [iChat][] (if on OS X) for those occasional AIM communications (down to about three people who use AIM still).

[Thunderbird][] for email.

**Other applications:**

I'll use [GIMP][] for many image editing tasks (for me, this usually is just making test images for themes, or making small tweaks to existing images). I prefer [Photoshop][] but find it to be ridiculously overpriced, and I am terrible with either of them anyway and will let the professionals make things. [PNGCrush][] is a good tool, I usually use it to expand PNGs to be uncompressed, using "pngcrush -f 0 -m 1 -l 0 -force".

For recording I use REAPER (naturally). 

As much as it pains me I use [QuickBooks 2007][quickbooks] for bookkeeping. It is awful, so I installed it on a [Windows XP][windows-xp] virtual machine some years ago, used with [Virtual Box][virtualbox].

[Steam][]: I don't play very many games but Steam really makes it easy to buy/install games without having to have physical discs or worry about copy protection being installed.

### What would be your dream setup?

In 2007 we bought a top of the line, dual quad-core Xeon workstation. It was very helpful for testing REAPER on a system with 8 cores, and was a nice computer, but it was loud and used something ridiculous like 270 watts even when idle. I felt like ashamed to turn the thing on.

Having had that experience, and also having paid many electricity bills, I'd say my ideal system would be a quad core i7 with at least 8GB RAM, a nice keyboard, a big high resolution monitor, a video card good enough for [Call of Duty: World at War][call-of-duty-world-at-war], 256GB SSD, and with the total idle power consumption (including monitor) under 80 watts.

[call-of-duty-world-at-war]: https://en.wikipedia.org/wiki/Call_of_Duty:_World_at_War "A WWII first person shooter."
[clipx]: http://bluemars.org/clipx/ "A Windows clipboard history manager."
[colloquy-ios]: http://web.archive.org/web/20191118233533/https://colloquy.mobi/ "An IRC client app."
[gimp]: https://www.gimp.org/ "An open-source image editor."
[git]: https://git-scm.com/ "A version control system."
[ichat]: https://en.wikipedia.org/wiki/IChat "An AIM/Jabber client included with Mac OS X."
[imac]: https://www.apple.com/imac-24/ "An all-in-one computer."
[iphone-4s]: https://en.wikipedia.org/wiki/IPhone_4S "A smartphone."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[mirc]: https://www.mirc.com/ "An IRC client for Windows."
[msysgit]: https://github.com/msysgit/msysgit/ "A Windows version of Git built on MSys."
[natural-keyboard]: https://en.wikipedia.org/wiki/Microsoft_Natural_keyboard "An older ergonomic keyboard."
[perl]: https://www.perl.org/ "An interpreted scripting language."
[photoshop]: https://www.adobe.com/products/photoshop.html "A bitmap image editor."
[php]: https://www.php.net/ "An interpreted scripting language."
[pidgin]: https://www.pidgin.im/ "An open-source multi-protocol chat client."
[pngcrush]: https://pmt.sourceforge.net/pngcrush/ "A command-line tool for compression PNG images."
[putty]: https://www.chiark.greenend.org.uk/~sgtatham/putty/ "A free Telnet/SSH client for Windows."
[quickbooks]: http://web.archive.org/web/20230524094339/https://quickbooks.intuit.com/ "Business accounting software for Windows."
[readynas-pro]: https://www.readynas.com/?p=1498 "A network backup/storage solution."
[reaper]: https://www.reaper.fm/ "A software digital audio workstation."
[steam]: https://store.steampowered.com/ "A digital game distribution service."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[thinkpad-x60]: https://www.thinkwiki.org/wiki/Category:X60s "A 12.1 inch PC laptop."
[thunderbird]: https://www.thunderbird.net/ "An open-source cross-platform mail client."
[vim]: https://www.vim.org/ "A command-line text editor."
[virtualbox]: https://www.virtualbox.org/ "Open-source virtualisation software."
[visual-c-plusplus]: https://learn.microsoft.com "An IDE for Windows software development."
[winamp]: https://www.winamp.com/home-static.html "A media player."
[windows-7]: https://en.wikipedia.org/wiki/Windows_7 "An operating system."
[windows-xp]: https://en.wikipedia.org/wiki/Windows_XP "An operating system for x86 computers."
[x-chat-aqua]: https://sourceforge.net/projects/xchataqua/ "A Mac OS X version of the IRC client."
[xcode]: https://en.wikipedia.org/wiki/Xcode "An IDE for Mac developers."
