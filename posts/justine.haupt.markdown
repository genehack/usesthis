---
title: Justine Haupt
summary: Science associate
date: 2020-06-30
categories:
- developer
- linux
- scientist
- windows
---

### Who are you, and what do you do?

[I](http://www.justine-haupt.com/ "Justine's website.") usually call myself an engineer as I do mechanical, electrical, optical, and software development in almost equal parts. I'm a "science associate" at a national laboratory where I do research and development for cosmology and astronomy instrumentation, though more recently I've branched into optics for quantum networking.

I also recently started an open source hardware company, which is mostly a creative outlet for my engineering projects-turned-products. For additional fun I play old time fiddle and fly a Piper Pawnee as tow pilot for a local glider club.

### What hardware do you use?

Main computer: 2013 Dell [XPS 9530][xps-15-9530] ultrabook (7 years old at the time of this writing) Computers in my office: Two Dell boxes.
SBCs: [Raspberry Pis][raspberry-pi] (for general "LAN of things" stuff), NVIDIA [Jetson Nano][jetson-nano] (for robotics development)
Pen: Pilot [G2][g2.2] with the .38mm ball
Paper: Plover Bond, when I can justify using it
Soldering station: Pace [ST 30][st-30]
Multimeter: Fluke model 75
Oscilloscope: Rigol [MSO1104Z][]
3D Printers: Makergear [M2][], Makergear [M3-ID][], plus a very large homebrew printer

### And what software?

On my laptop and one of the two work PCs I run [Debian][] Linux, which I switched to as my sole OS when I spilled cranberry juice on my previous laptop in 2014. You see, the refurbished Dell XPS 15 I bought at the time came with [Windows 8][windows-8] (!) on it. I decided then and there to commit to Linux as my sole operating system and never looked back. That Dell XPS is still my main personal laptop for work and play, though by now I've upgraded it more than once.

My go-to desktop environment for years was [MATE][] customized to look more like [XFCE][], but after seeing some colleagues power-using the [awesome][] tiling window manager I transitioned to that about a year ago and have fallen in love with it. It's wonderfully customizable thanks to the [Lua][] configuration scripts, and one realizes how silly (e.g. wasteful of screen real estate) it is ever to have windows overlapping each other. This is one of those things like one's taste in music... my childhood self would never have listened to the music I now love, and likewise, one's computing preferences are a journey.

For text editing and programming it's [Vim][], though I admit to using the arrow keys to move the cursor around instead of hjkl. It's very nice not having to change one's editing workflow when working headless. I also use Vim for note-taking and for this I specifically use the [VimWiki][] add-on which adds some nice/basic text highlighting for what would otherwise be plain text.

For electrical design it's [KiCad][], and for web development I've been pretty happy with [Brackets][]. [Simplify3D][] is my gcode slicer.

As programming languages go I mostly find myself in [Python][] and Arduino [C++][c-plusplus], though as I start to entertain more serious programming projects requiring speed, especially in a robotics context, I've been playing around with [Go][] and finding I like it very much. It's a compiled-language and a solid alternative to C++ that's easier and more fun to work in the way Python is for non-compiled languages.

For general word processing I actually often stick with MS [Word][] and run it on [CrossOver][], which is a commercial version of [Wine][] that works quite well. Lately I've been using [Google Docs][google-docs] more and more but I don't like relying on the cloud _one bit_. As for [LibreOffice][], when one has to share documents with Word and [PowerPoint][] users on an almost daily basis it's just a non-starter in terms of small but egregious formatting issues.

A few programs I need don't run on Linux. I expect that that will change, but for now when using the laptop (most of the time, especially now during COVID) I run [Windows 7][windows-7] in a virtual machine on VMware [Workstation Player][workstation-player]. I use the oldest version of Windows that I can for performance and because security is a non-issue running in the VM. Here I use Autodesk [Inventor][] for mechanical design, [OSLO][] or [Zemax][opticstudio] for optical design, and [Vegas][vegas-pro] for video editing. One might wonder if a graphically intense program like Inventor is really usable on a virtual machine on a 7 year old laptop, and yes, it's perfectly usable even with large mechanical assemblies. That said I would still love to figure out a GPU-passthrough solution for this.

In my office (at Brookhaven National Lab) I have a separate Windows workstation just for running Inventor and Zemax, but I have just one keyboard and mouse and one (networked) hard drive, so from the user perspective it all feels like one computer. Here's how that works: The keyboard, mouse, and the left-two of the three monitors go to the Linux box, which is on the same LAN as the Windows box which has the right monitor. When I move the mouse from the left two Linux monitors to the right (Windows) monitor, the transition for both mouse and keyboard is absolutely seamless. The software that makes that magic happen is called [Synergy][]. And because both PC's look at the same hard drive I can save files from (say) Inventor on the far-right monitor and then immediately attach them in email from one of the two left (Linux) monitors. And when the Windows one decides to be an idiot I can just ignore it and go on my merry way with the main Linux box. I have this set up this way because in that environment I really need all the performance I can get to run Inventor, but I foresee a _single_ Linux box in my eventual future even for the more demanding lab work environment. Considering that all new software seems to be cross-platform, that Wine/CrossOver runs MS [Office][] without any bugs and at native speed (really), and that a virtual machine works perfectly for any programs that really can't be run any other way, there's fewer and fewer reasons not to switch to Linux full time IMHO.

### What would be your dream setup?

I like the freedom to work from the couch and other comfortable places, so I suppose my dream computer would be a lightweight but powerful laptop with 2 GPUs to allow passing one through for a virtual machine. There also needs to be native functionality in the virtual machine software to let that happen, and none of this seems to exist right now.

An idea that intrigues me is that instead of an actual laptop, an ultrathin laptop-like dumb terminal could interface with a nearby computer via USB-C. Thus, any performance and thermal limitations imposed by the laptop form factor are eliminated, and there would still only be one wire running to the "laptop" (remember that USB-C can handle power and keyboard-video-mouse all over one cable). Who among us doesn't always keep their laptop plugged in anyway? The computer in this case might still be much more compact than a traditional PC; perhaps it could be a single-board ARM computer with battery power. The whole thing could even piggyback on the dumb terminal somehow when on the go. I'm also excited for the future of augmented reality and would be curious to try a system with no physical screen.

[awesome]: https://awesomewm.org/ "A window manager for X."
[brackets]: https://brackets.io/ "A web-based IDE."
[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[crossover]: https://www.codeweavers.com/crossover/ "Software for running Windows software on non-Windows operating systems."
[debian]: https://www.debian.org/ "A Linux distribution."
[g2.2]: https://www.jetpens.com/Pilot-G2-Original-Gel-Pens/ct/610 "A pen."
[go]: https://go.dev/ "A compiled programming language."
[google-docs]: https://en.wikipedia.org/wiki/Google_Docs "A web-based office suite."
[inventor]: http://web.archive.org/web/20221224070540/https://www.autodesk.com/products/inventor/overview "3D CAD software for mechanical designers."
[jetson-nano]: https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-nano/ "A dedicated AI hardware system."
[kicad]: http://web.archive.org/web/20220324205847/https://kicad-pcb.org/ "Open-source CAD software."
[libreoffice]: https://www.libreoffice.org/ "A free, open-source productivity suit."
[lua]: http://www.lua.org/ "An interpreted scripting language."
[m2]: https://makergear.com/products/m2 "A 3D printer."
[m3-id]: https://makergear.com/products/m3-id "A 3D printer."
[mate]: https://en.m.wikipedia.org/wiki/MATE_(software) "A desktop environment for Linux and BSD."
[mso1104z]: https://www.tequipment.net/Rigol/MSO1104Z/Mixed-Signal-Oscilloscopes/ "An oscilloscope."
[office]: https://www.microsoft.com/en-us/microsoft-365 "An office productivity suite."
[opticstudio]: http://web.archive.org/web/20230706203330/https://www.zemax.com/pages/opticstudio "Optical design software."
[oslo]: http://web.archive.org/web/20230706203331/https://lambdares.com/oslo "Optical design software."
[powerpoint]: https://www.microsoft.com/en-us/microsoft-365/powerpoint "Presentation software."
[python]: https://www.python.org/ "An interpreted scripting language."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[simplify3d]: https://www.simplify3d.com/ "3D printing software."
[st-30]: https://www.tequipment.net/Pace/ST-30-8007-0499/Soldering-Stations/ "A soldering iron."
[synergy]: https://symless.com/ "Software to share a single keyboard and mouse between multiple computers."
[vegas-pro]: https://en.wikipedia.org/wiki/Sony_Vegas_Pro "A non-linear video editing suite."
[vim]: https://www.vim.org/ "A command-line text editor."
[vimwiki]: https://github.com/vimwiki/vimwiki "A wiki add-on for vim."
[windows-7]: https://en.wikipedia.org/wiki/Windows_7 "An operating system."
[windows-8]: http://web.archive.org/web/20230522122523/https://en.wikipedia.org/wiki/Windows_8 "An operating system for PC and tablet computers."
[wine]: https://www.winehq.org/ "Software for running Windows software on other operating systems."
[word]: https://www.microsoft.com/en-us/microsoft-365/word "A document editor."
[workstation-player]: https://en.m.wikipedia.org/wiki/VMware_Workstation_Player "Virtualisation software."
[xfce]: https://www.xfce.org/ "A lightweight UNIX-like desktop environment."
[xps-15-9530]: https://www.dell.com/support/home/en-us/product-support/product/xps-15-9530/drivers "A 15 inch PC laptop."
