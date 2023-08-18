---
title: Jessie Frazelle
summary: Software engineer (Google, Docker)
date: 2016-08-23
categories:
- developer
- linux
---

### Who are you, and what do you do?

My name is [Jessie Frazelle](https://blog.jessfraz.com/ "Jessie's website.") - some people call me "Jess", but I pretty much answer to anything except "Jessica". I'm a software engineer at Google. Most notably you might know me from being a maintainer of [Docker][] and "running everything in containers". I am also a contributor to a lot of other open source projects such as [runC][] and [golang][go]. I'm currently working on making containers more secure. I absolutely love all things Linux.

### What hardware do you use?

Let's see... I have quite a few setups, so I'll go over each of them.

1. 486DX Insight box with a CRT monitor. It runs [MS-DOS 6][ms-dos]. Yes, it has a turbo button. The keyboard is not a [IBM Model M][model-m], but very similar and made by Insight as well. The CRT is an amber monochrome monitor. This computer has a story behind it - my grandpa worked for Motorola on the first computers, then opened his own consulting practice. He wrote Motorola's variation of [COBOL][], which I interpret as equivalent to a "fork" today. I actually found an old newspaper ad for his department - hence, the computer from Insight (another Arizona-based computer company). It's a custom-built machine. Thankfully when I popped it open he had labeled everything. I have a bunch of 5" and 3" floppies for it - Some games ([Flight Simulator][microsoft-flight-simulator] & [Kid Pix][kid-pix]) but mostly code he wrote himself, which I thoroughly enjoy digging into. He also gave me a crazy amount of programming books.

2. [Dell XPS 13][xps-13] running [Debian Sid][debian]. 9343/9350 model. This is my baby. I absolutely love it. It works perfectly for "Linux on the desktop". I have had both the 8GB and 16GB models and both are awesome.

3. Dell Chromebook running stock [Chrome OS][chrome-os]. It has 8GB RAM. I absolutely LOVE Chrome OS. It works perfectly and is awesome for traveling. You can give talks with Google slides or whatever your flavor, and not have to worry about `xrandr` (which I never worry about because I'm a pro - kidding :D). But it's amazing. People told me about it for a while and I didn't believe them, because I love my containers, but let me shout it to the world now: Chrome OS is AWESOME.

I also have the SONOS surround sound speakers, and I'm waiting for Matthew Garrett to come over and hack my sound system.

I use [Yubikeys][yubikey] for basically all 2FA, SSH, and GPG.

### And what software?

Globally: I use [vim][] (specifically [neovim][]), and my configuration is [here](https://github.com/jfrazelle/.vim "Jessie's vim config on GitHub."). This also works for plain old vim as well.

Dell XPS 13: I use [i3][] as my window manager and have converted SO many people to do the same. My setup is quite specific - I run literally everything in containers. I've given [a few talks on it](https://www.youtube.com/watch?v=1qlLUf7KtAw "One of Jessie's talks on YouTube, about running everything in containers.") and written a few [blog](https://blog.jessfraz.com/post/runc-containers-on-the-desktop/ "Jessie's post about runC containers on the desktop.") [posts](https://blog.jessfraz.com/post/docker-containers-on-the-desktop/ "Jessie's post about Docker containers on the desktop."). You can find [my install script](https://github.com/jfrazelle/dotfiles/blob/master/bin/install.sh "Jessie's container install script on GitHub.") in my dotfiles, plus [all the aliases](https://github.com/jfrazelle/dotfiles/blob/master/.dockerfunc "Jessie's Docker alias config on GitHub.") for running everything in containers.

Chromebook: I do not use [crouton][]. All I use if I need a terminal is the [SSH extension][secure-shell] to tunnel into a remote box. 

### What would be your dream setup?

A mainframe. Something so powerful I could just laugh mwahhahahahaha and stroke a white cat.

[chrome-os]: https://en.wikipedia.org/wiki/Chrome_OS "A Linux distribution for running web applications."
[cobol]: https://en.wikipedia.org/wiki/COBOL "A compiled programming language."
[crouton]: https://github.com/dnschneid/crouton "A set of scripts to generate a chroot in Chrome OS."
[debian]: https://www.debian.org/ "A Linux distribution."
[docker]: https://www.docker.com/ "A service and software for building and shipping distributed software."
[go]: https://go.dev/ "A compiled programming language."
[i3]: https://i3wm.org/ "An X window manager."
[kid-pix]: https://en.wikipedia.org/wiki/Kid_Pix "Bitmap drawing software aimed at kids."
[microsoft-flight-simulator]: https://en.wikipedia.org/wiki/Microsoft_Flight_Simulator "A flight simulator game."
[model-m]: https://en.wikipedia.org/wiki/Model_M_keyboard "A keyboard."
[ms-dos]: https://en.wikipedia.org/wiki/MS-DOS "A text-based operating system."
[neovim]: https://neovim.io/ "A refactored vim."
[runc]: https://github.com/opencontainers/runc "A command line tool for running containers."
[secure-shell]: https://chrome.google.com/webstore/detail/deprecated-secure-shell-a/pnhechapfaindjhompbnflcldabbghjo "A terminal Chrome extension."
[vim]: https://www.vim.org/ "A command-line text editor."
[xps-13]: http://web.archive.org/web/20230706193216/https://www.dell.com/en-us/shop/cty/pdp/spd/xps-13-9333 "A 13 inch PC laptop."
[yubikey]: https://www.yubico.com/setup/ "A USB-based tool for generating one-time passwords."
