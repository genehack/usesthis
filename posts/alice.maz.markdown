---
title: Alice Maz
summary: Developer, cofounder (Sylph Bioscience)
date: 2020-01-16
categories:
- developer
- linux
---

### Who are you, and what do you do?

I'm [Alice Maz](https://www.alicemaz.com/ "Alice's website."). I'm cofounder of [Sylph Bioscience](https://sylph.io/ "Alice's bioscience company."), a startup building a computer platform for simulating the behavior of biological systems. I do general computer stuff, but being wedged between the biologist and the mathematician at a quantitative biology company means I'm also the de facto business guy. My primary programming languages lately are Scheme and email. This year I get to learn embedded dev making DIY medical devices for my girlfriend.

I also write here and there, with a particular interest in history. Someday I'll take a sabbatical to write a comparative study of medieval Europe and ancient China. Aside from that I'm an avid weightlifter and reckless cyclist. In the near future I'd like to be a capable scout and competent brawler.

### What hardware do you use?

While I do have a desktop with two monitors and a mechanical keyboard, lately I seem to do all my work on my [T480 ThinkPad][thinkpad-t480]. It's a spectacular laptop, and the first I've had that everything worked on Linux without any tricky setup. I have a [Pixel 3][pixel-3], a pair of [ATH-M50x][] headphones, a handful of [Raspberry Pis][raspberry-pi], and a couple more VPS instances than I can keep track of.

I also have to list my [Kenema tenugui](https://www.teamwakon.com/collections/kenema/products/kenema-shien-dokuro-the-dyed-tenugui "A cotton towel."), which I tie to my backpack and follows me everywhere. I got it when I started biking out of a vague sense that always having a towel could come in handy, and it isn't a meme, you can use a towel for anything. Also it billows behind me like a flag when I'm on the road, and the "skull exhaling smoke that is also a skull" design communicates to drivers that I don't fear death.

### And what software?

I run [Void Linux][void] on my computers. Maybe the best distro I've used so far, really happy to be back on a BSD-style init system. My browser is [Qutebrowser][], my phone runs [Graphene][grapheneos]. I prefer [musl][] to [glibc][] and [LLVM][] to the GNU toolchain. In all cases I'm making the choice to accept an amount of compatibility failures on the margins in exchange for a vastly sounder core system. I do almost all my programming in [CHICKEN][] [Scheme][] these days, and most of the rest in [Haskell][].

My taste in applications is spartan to a fault. I use [Vim][] for writing almost anything, software or otherwise. No plugins, ten-line conf and the first is to enable vi-compat mode. The one exception to this is Haskell, for which I use [Spacemacs][]. Inline typechecking triples your productivity the moment you turn it on, it's too good to give up. My shell is [tcsh][] in vi mode, a fact that causes great consternation when anyone else attempts to use my computer for anything. Terminal is [xterm][], which I will hasten to add does support Unicode; lack of Japanese text support is a dealbreaker for me. My regex "native tongue" is POSIX basic (the one where there is no logic whatsoever to which symbols need escapes) and I use [find][], [grep][], [sed][], and [xargs][] for practically everything.

Window management is a screen session on every machine, connected through [mosh][], and [xmonad][] to juggle them all. This is a spectacular way to work: I have a shell alias to create a session on the server-host named for the client-host, or reattach if it exists, and mosh means I can leave windows open through sleep/wake cycles or network changes and they pick back up automatically.

We also have a home VPN and home DNS. Being able to connect to any of your machines from any of your machines no matter where you are is so good that I can no longer live without it, and I don't understand why so many people who set up home media servers and home NAS don't do this first.

### What would be your dream setup?

One of the side benefits of doing most of your work with the people you live with and love is you get to plan infrastructure on decades-long timescales. In this spirit, instead of describing my dream setup, I'll describe the setup I intend to have in five years. If nothing else this will be a fun thing to look back on and see how right or wrong I was!

By the start of 2025, all of our systems will be running some kind of operating system orchestration framework. Ideally [Genode][] with whichever L4 kernel is suitable for a given arch, but it's possible we have to write something ourselves in the style of [Guix][]. Everything, from our desktops and laptops, down to microcontrollers and up to servers, will be provisioned automatically from a declarative specification written in an s-expression dialect. (Phones are iffy and probably depend on how [Fuchsia][] pans out.) This dialect will also serve as an interchange format we use to communicate between Scheme and Haskell, which we will standardize and release. We'll have our own stdlib and our own tooling that makes working in one or the other, or both in one project, as seamless as possible. The Scheme side will be agnostic to whichever particular Scheme we may wish to use.

We'll have a workshop suitable for working on electronics and machines. We'll have a wetlab. We'll have a burgeoning robotics company, a successful biology company, and a rocket company that has put something on the moon.

I probably will not have written the history book though.

[ath-m50x]: http://www.audio-technica.com/en-us/ath-m50x "Over-the-ear headphones."
[chicken]: https://call-cc.org/ "A Scheme compiler."
[find]: https://en.wikipedia.org/wiki/Find_%28command%29 "A command-line tool for searching for specific text in files."
[fuchsia]: https://en.wikipedia.org/wiki/Google_Fuchsia "An operating system."
[genode]: https://genode.org/ "An operating system framework."
[glibc]: https://en.wikipedia.org/wiki/GNU_C_Library "A standard library for C."
[grapheneos]: https://grapheneos.org/ "An open-source mobile OS compatible with Android."
[grep]: http://www.gnu.org/software/grep/ "A command-line tool for pattern matching in files."
[guix]: https://guix.gnu.org/manual/html_node/Package-Management.html "A package management system."
[haskell]: https://wiki.haskell.org/Haskell "A functional programming language."
[llvm]: https://llvm.org/ "A C/C++/Objective-C compiler."
[mosh]: https://mosh.org/ "A remote terminal shell system."
[musl]: https://www.musl-libc.org/ "A standard C library."
[pixel-3]: https://en.wikipedia.org/wiki/Pixel_3 "A 5.5 inch Android phone."
[qutebrowser]: https://qutebrowser.org/ "A keyboard-focused web browser."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[scheme]: https://en.wikipedia.org/wiki/Scheme_(programming_language) "An alternative dialect of the Lisp programming language."
[sed]: http://www.gnu.org/software/sed/ "Text filtering software."
[spacemacs]: https://duckduckgo.com/?q=spacemacs&t=osx&ia=software "A distribution of emacs."
[tcsh]: http://web.archive.org/web/20170618044928/http://www.tcsh.org:80/Welcome "A command-line shell."
[thinkpad-t480]: https://www.lenovo.com/us/en/p/22TP2TT4800 "A 14 inch PC laptop."
[vim]: https://www.vim.org/ "A command-line text editor."
[void]: https://voidlinux.org/ "A Linux distribution."
[xargs]: https://en.wikipedia.org/wiki/Xargs "A command-line tool to execute commands from standard input."
[xmonad]: https://xmonad.org/ "A tiling window manager for X11."
[xterm]: https://en.wikipedia.org/wiki/Xterm "Terminal software for the X Window System."
