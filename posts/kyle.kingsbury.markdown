---
title: Kyle Kingsbury
summary: Computer safety researcher
date: 2017-04-13
categories:
- developer
- linux
- researcher
- security
---

### Who are you, and what do you do?

My name's Kyle Kingsbury, and for reasons I've never fully understood, machines around me tend to break down in unusual ways. I'm making the best of that curse by [testing distributed systems](https://jepsen.io/ "Kyle's computer safety research company.") to see whether they're safe. I introduce network partitions, clock skew, and other failures, and carefully observe the system I'm testing to see whether it loses data, makes stale or invalid data visible, or allows transactions to interleave improperly. I write reports and give talks on my research, and also offer consulting and training classes at companies and conferences.

In past lives I was a photographer, physics student, aikidoist, IT support person, network ops engineer, and backend developer. I've published some [very minor research](https://arxiv.org/abs/0903.3931 "Kyle's chaos research paper.") in Physical Review Letters on chaos in nonlinear quantum systems. I [blog about software](https://aphyr.com/ "Kyle's personal website.") and wrote some open source projects, like [Riemann][]. I've also made woodcuts, websites, 3D renderings, shirts, short stories, furniture, music, books... and just finished making a lamp last week. I like creating things, even it's just as an amateur!

### What hardware do you use?

The safety analysis work I do is CPU and memory intensive, and readily parallelizable. Comcast gave me an OSS research grant to build a machine for that work, so my desktop is a ridiculous 48-way Xeon (2x E5-2697v2), with 128GB of ECC DDR3 and 11 TB of miscellaneous SSDs & spinning rust. The motherboard is wonky and refuses to find half the disks on boot. You can crash the box by using certain USB ports. We have a complicated relationship.

There's definitely a trade-off between performance and being locked into a tiny set of weird motherboards that support that kind of hardware. I don't necessarily recommend it unless you like being the kind of person who opens their case every few weeks, muttering "what is it THIS time" under their breath.

I use a standard layout Das Keyboard with Cherry MX Brown switches, and cannot believe that I'm the sort of person who cares about that. Maybe it comes with being a [Vim][] user. There are no labels on the keycaps (it was the only model they had on sale) which means it takes me forever to type passwords -- and every time I use [Mutt][] is a game of Russian Roulette. I use a [Logitech G5 laser mouse][g5-laser-mouse], which may be the closest to the Platonic ideal pointing device as it is possible for late-stage capitalism to produce.

My display is a 32-inch 4k Dell -- I think it's a [UP3216Q][up3216q]. It's a wonderful screen for editing photographs and for rendering lots of [xterms][xterm], which, let's face it, is 90% of my computing life.

I sometimes shoot with a [Nikon D700][d700], which has spectacular autofocus and low-light performance -- but when traveling I prefer my [D7000][] with a [28-300mm Nikkor][af-s-nikkor-28-300mm-f3.5-5.6g-ed-vr]. It's lighter, offers better resolution, and that lens is incredibly versatile. I really like Nikon's ergonomics, though most of my photo friends shoot with Canon.

Some of my talk slides are drawn using Sakura technical pens and Whitelines grid notebooks. I take photos with my phone or camera on a tripod, and clean them up in [GIMP][]. That process doesn't work well for color work or for editing on planes before the talk, so I've moved to an [iPad Air 2][ipad-air-2] with the [Paper app][paper-ios] and [Pencil stylus][pencil]. It's honestly kind of a pain -- the stylus is unreliable and palm rejection doesn't work, so I have to redraw things a whole bunch. But the flexibility, and being able to spit out a PDF with a few taps is great.

### And what software?

I run [Debian][] (hi Jess!). It's mostly stock except for ZFS, and using [OpenBox][]+[GKrellM][]+[xfce][]-panel as my window manager. I love having virtual workspaces and configurable bindings for everything. I use [irssi][] for IRC, Mutt/[Geary][] for mail, [Chromium][] for browsing, and [Pidgin][] for IM. I edit photos in [darktable][] and The GIMP, and do my vector work in [Inkscape][]. Morganastra sold me on the [Fish shell][fish] a few years ago and I've never looked back.

I'm hopelessly reliant on middle-click-paste. Laptop trackpads drive me nuts. This is entirely my own fault.

Every so often I try to become a Normal Computer User so I can spend less time futzing with my weird tools, try [OS X][macos] for a week, and give up. At this point I live in perpetual, mild trepidation that the people who maintain the Galapagos island of software I rely on will stop caring, stranding me in desktop Linux limbo.

I have a terrible memory and need to see everything on the screen at once, or I'll forget! So when I'm writing software I live in six to twelve [gnome-terminals][gnome-terminal]. Most are running Vim, editing the different namespaces I'm calling through at that time. Then there's usually a [clojure][] repl, and a test runner that automatically reloads and runs tests when I write files to disk. Maybe a window for [git][] commands and running various tools.

I think I learned this way of working from my Dad, who's a UNIX hacker -- works on filesystems, operating systems, that kind of thing. We were chatting about work setups last year, and even though he works in [C][] and I'm using this high-level functional [Lisp][], we still use the same tools. We both have poor memories and have to see the whole call stack laid out across the screen in order to reason about a program! I see people program in one window on a laptop sometimes, and that just seems like... some kind of code sorcery! Must be cool.

Aphyr.com is a big mass of custom [Ruby][]+[Sinatra][] running on a [Linode][]. Jepsen.io is a Clojure site, running on [Skyliner][]. The articles are written in [Markdown][] and preprocessed with [Pandoc][]. There's a lot of [LaTeX][] in my life, come to think of it.

There are a bunch of miscellaneous Clojure, Ruby, and [Perl][] scripts for various things too. You know those movies -- like, Honey, I Shrunk the Kids, or Wallace and Gromit -- where they pan through an inventor's household and they have all these ridiculous gizmos for making eggs and answering the phone? That's kinda what my ~/bin is like. There are daemons for taking ZFS snapshots and backing things up to my NAS and S3. Keeping SSH reverse tunnels open. Scripts for tearing apart PDFs, adding my signature to a page, and stitching them back together again. Spinning up clusters of Debian nodes in LXC for Jepsen tests. Setting the color of the lights in my living room by generating color schemes and downloading them from websites. Rsyncing my phone's photos to an SFTP drop. There's a daemon on aphyr.com that parses email describing current prices in [EVE Online][eve-online]'s market, loads that into [sqlite][], and uses a hilarious n-way self-join to pathfind efficient trading routes. Compute Goldberg machines everywhere.

### What would be your dream setup?

I'm sure there's an upper limit to the number of xterms I can reasonably have in front of me, but I don't think I'm anywhere near it yet. A 50" curved display might be nice? Also I'd like keys with labels on them, so you could tell what buttons will, say, mark an email as unread vs delete the entire thread and forward jockstrap selfies to your clients.

Also a computer which turns on reliably and doesn't crash when you plug in a keyboard. Maybe I'm setting unrealistic goals here.

On the software front, I'm still hunting for a good email client. Geary's typography is confusing, Mutt is nice but I really like being able to see prior emails while composing a new one, and [Thunderbird][] crashes every ten minutes. I'd also like better color management in Linux, but I can't even begin to characterize *how* the current setup is broken.

I'm also blowing enough money on [AWS][] clusters these days that it might be cost-effective to build a physical 5-node cluster for Jepsen testing in my apartment. That'd be pretty swell, because LXC containers all share the same clock, which keeps me from testing clock skew locally.

[af-s-nikkor-28-300mm-f3.5-5.6g-ed-vr]: https://www.nikonusa.com/en/nikon-products/product-archive/camera-lenses/af-s-nikkor-28-300mm-f%252f3.5-5.6g-ed-vr.html "A zoom lens."
[aws]: https://aws.amazon.com/ "Amazon's web service platforms."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[chromium]: https://www.chromium.org/ "Open-source builds of the Chrome web browser."
[clojure]: https://en.wikipedia.org/wiki/Clojure "A dynamic programming language using the Java Virtual Machine."
[d7000]: http://web.archive.org/web/20150902003342/http://www.nikonusa.com:80/en/Nikon-Products/Product/dslr-cameras/D7000.html "A 16.2 megapixel DSLR."
[d700]: https://www.nikonusa.com/en/nikon-products/product/dslr-cameras/d700.html "A 12.1 megapixel DSLR."
[darktable]: https://www.darktable.org/ "An open source photo workflow tool."
[debian]: https://www.debian.org/ "A Linux distribution."
[eve-online]: https://www.eveonline.com/ "A space-based MMO game."
[fish]: https://fishshell.com/ "A command-line shell."
[g5-laser-mouse]: http://web.archive.org/web/20230131035846/http://www.amazon.com/Logitech-Laser-Mouse-Blue-Black/dp/B000ODN7VM/ "A mouse"
[geary]: https://wiki.gnome.org/Apps/Geary "An email client for GNOME."
[gimp]: https://www.gimp.org/ "An open-source image editor."
[git]: https://git-scm.com/ "A version control system."
[gkrellm]: http://gkrellm.srcbox.net "Linux system monitoring software."
[gnome-terminal]: https://en.wikipedia.org/wiki/GNOME_Terminal "A terminal application."
[inkscape]: https://inkscape.org/ "An open-source vector graphics program."
[ipad-air-2]: http://web.archive.org/web/20170320213915/http://www.apple.com/ipad-air-2/ "A tablet device."
[irssi]: https://irssi.org/ "A CLI irc client."
[latex]: https://www.latex-project.org/ "Typesetting software."
[linode]: https://www.linode.com "A VPS hosting service."
[lisp]: https://en.wikipedia.org/wiki/Lisp_(programming_language) "A programming language."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[markdown]: https://daringfireball.net/projects/markdown/ "An email-like format for marking up text."
[mutt]: http://www.mutt.org/ "A command-line email client."
[openbox]: http://openbox.org/wiki/Main_Page "A window manager for *nix."
[pandoc]: https://pandoc.org/ "A Markdown document converter."
[paper-ios]: http://web.archive.org/web/20230815030158/https://wetransfer.com/paper "A notebook/drawing app."
[pencil]: http://wetransfer.com/pencil "An iPad stylus."
[perl]: https://www.perl.org/ "An interpreted scripting language."
[pidgin]: https://www.pidgin.im/ "An open-source multi-protocol chat client."
[riemann]: http://riemann.io/ "A tool for monitoring distributed systems."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[sinatra]: https://sinatrarb.com/ "A lightweight Ruby web framework."
[skyliner]: http://web.archive.org/web/20220815195826/https://www.skyliner.io/ "An AWS deployment service."
[sqlite]: http://web.archive.org/web/20230815162335/https://www.sqlite.org/index.html "A self-contained database engine."
[thunderbird]: http://web.archive.org/web/20070322094547/http://www.thunderbird.net:80/ "An open-source cross-platform mail client."
[up3216q]: http://web.archive.org/web/20200708102608/https://www.dell.com/en-us/shop/dell-ultrasharp-32-ultra-hd-4k-monitor-with-premiercolor-up3216q/apd/210-afln/monitors-monitor-accessories "A 32 inch monitor."
[vim]: https://www.vim.org/ "A command-line text editor."
[xfce]: https://www.xfce.org/ "A lightweight UNIX-like desktop environment."
[xterm]: https://en.wikipedia.org/wiki/Xterm "Terminal software for the X Window System."
