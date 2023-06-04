---
title: Austin Hicks
summary: Product engineer (Backtrace.io)
date: 2020-06-12
categories:
- developer 
---

### Who are you, and what do you do?

I'm Austin Hicks, a backend product engineer at Backtrace.io, a company that does crash analysis for other companies writing software. This means I do a bit of everything. I've got a good bit of open source in my past, most notably some work on the [Rust][] compiler. The most immediately unusual thing about me is that I'm blind.

### What hardware do you use?

My main computer is a custom tower that's been through several iterations at this point. Currently it's a 6-core Skylake with 64 GB ram. I'm also a mechanical keyboard guy, namely [the CODE Keyboard][code]. I've been typing for over 20 years at this point, and non-mechanical keyboards just don't do it anymore.

The phone is an [iPhone 7][iphone-7], though I'll likely be upgrading that soon. Apple is by far the best at accessibility for phones, though sadly not for computers.

### And what software?

My OS is Windows for the accessibility. In order to use the computer as a blind programmer, I use a screen reader called [NVDA](https://www.nvaccess.org/). The simplest explanation of screen readers is that they make the computer talk, but in actuality it also comes with something like 100 additional keystrokes and most of us who program eventually have it talking at 800 words a minute or so. It takes years to learn to be efficient, and "it makes the computer talk" is definitely a simplification.

My daily drivers for programming are either [Nodepad++][notepad-plusplus] and [this NVDA add-on for it][notepad-plus-plus-add-on-for-nvda], or [VSCode][visual-studio-code]. I use the former setup for work because there's a few things that someone else scripted which are super useful for keeping code style in line with the rest of the team, but for personal projects VSCode is amazing and Microsoft's been doing a lot of good work with accessibility for screen reader users. One of these days I'm going to find the time to write scripts for VSCode to fill in the gaps that still require Notepad++ some of the time and make the final switch.

### What would be your dream setup?

For starters I'd start with more people caring about accessibility. It's easy to do color blindness and to add keystrokes to everything, but probably around half of the GUI frameworks out there flat out don't work with screen readers no matter how you try. VSCode has only been good for about a year for example, and before that there was something like a 10 year gap where most of the IDEs and editors with that level of functionality were either so inefficient for blind users as to be pointless or entirely inaccessible. A lot of stuff turns into finding the single app that works, rather than having choices or using the best thing for the job, and a lot of the things that people use to make apps could offer accessibility by default but don't because no one has put in the time.

But if I was going to be more hypothetical, I'd kill for a 2-dimensional refreshable braille display. We have 80-character braille displays now, basically a giant row of pins with motors underneath, but they cost multiple thousands of dollars and no one has scaled the technology up to multiple lines of text. Braille itself is actually very slow compared to speech and I haven't bothered with a braille display in a long time for that reason, but if someone managed to make it 2 dimensional then the world of tactile diagrams opens up. That would allow for everything from metrics charts for work to financial analysis to playing nethack. When it comes to analyzing sequences of numbers I tend to write scripts in [Python][] to extract information for me, but that only goes so far. There's some people working on this but it's actually an incredibly challenging problem, especially if you want them to be inexpensive enough that people can actually afford them.

There's also a lot of low-hanging fruit with combining speech and audio queues that's still on the table for screen readers, for example replacing announcements of control types with sounds (as in buttons might click instead of say button). A few people (including myself) have implemented this to one degree or another, but it's either expensive, hacky, or not on Windows.

[code]: https://codekeyboards.com/ "A mechanical keyboard."
[iphone-7]: https://en.wikipedia.org/wiki/IPhone_7 "A 4.7 inch iOS smartphone."
[notepad-plus-plus-add-on-for-nvda]: https://github.com/derekriemer/nvda-notepadplusplus "An accessibility extension for Notepad++"
[notepad-plusplus]: https://notepad-plus-plus.org/ "A free text/code editor for Windows."
[python]: https://www.python.org/ "An interpreted scripting language."
[rust]: https://www.rust-lang.org/ "A programming language."
[visual-studio-code]: https://code.visualstudio.com/ "A development IDE."
