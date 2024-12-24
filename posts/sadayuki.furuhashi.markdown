---
title: Sadayuki Furuhashi
summary: Hacker (MessagePack, Fluentd)
date: 2012-08-24
categories:
- developer
- hacker
- mac
---

### Who are you, and what do you do?

My name is Sadayuki Furuhashi: a hacker who works hard to not work. 

I'm the original author of [MessagePack][], an open source object serialization library. I'm also the author of [Fluentd][], a log collection tool. I recently co-founded [Treasure Data, Inc.](http://treasure-data.com/ "Treasure Data's website."), a cloud-based data warehousing and analytics service. I'm responsible for the design and implementation of the platform. My primary interest is in distributed systems: I strive to build complex yet practical distributed systems on top of fragile commodity servers.

### What hardware do you use?

Computer: My only machine is a 13" [MacBook Air][macbook-air]. I switched my daily partner from Linux boxes to Mac laptops 5 years ago. I love Macs since they work well with both UNIX tools and Adobe software.

Peripherals: I have desktop setups at my home and at the office. I put the laptop into clamshell mode and connect it to a 27" [Apple Thunderbolt Display][thunderbolt-display]. I use a [Wacom Intuos tablet][intuos] instead of a mouse. People are surprised to see me using a pen tablet for everything (from coding to surfing the web), but I like the ability to click any part of the screen directly (the tablet surface and display are mapped 1:1). I haven't used a mouse for 6 years. I use a [Realforce][realforce-103u] keyboard and recommend it to all hackers. By the way, [Kenneth Reitz](http://kenneth.reitz.usesthis.com/ "Kenneth's interview.") uses [Happy Hacking Keyboard PRO][happy-hacking-keyboard], another awesome keyboard with replacement key switches made by the same manufacturer.

I have two of each device so that I have the same configuration at home and at the office. 

Servers: When I was a student, I built a "home datacenter" consisting of 8 servers so that I could research distributed systems without having to depend on school resources. With these servers (discreetly placed under my bed), I was able to implement the [Kumofs][] and [LS4][] storage systems. With the decreasing price of physical servers, I think it's a very good time to be working on distributed systems. 

There days I'm using [Amazon EC2][ec2] instead of my own physical servers. There were advantages to having the hardware right there, but those servers were too noisy and hot to live with (imagine what happened when I ran benchmark scripts on all of these servers in my tiny apartment!). I think it's very good times to research even distributed systems because the price of physical servers is decreasing.

Headphones: I listen to music while coding in order to block out distractions. I've been using a [JVC HA-FXC51][ha-fxc51] for a year now. Each time I buy a new pair, I'm impressed with how much the technology has progressed. 

### And what software?

I'm a traditionalist hacker and love using bash, vim, screen and many other small UNIX tools.

[I](https://github.com/frsyuki "Sadayuki's Github account.") use [GitHub][] to publish code and communicate with collaborators. I test with [Jenkins][] or [Travis CI][travis], and deploy to servers with [Chef][].

Because my open source work consists of performance-sensitive libraries, optimization work takes up a significant part of my free time. I used to use [gperftools][] for performance profiling, but I have recently switched to [Instruments][] (bundled with [Xcode][]). [Valgrind][] is another  indispensable tool.

[Ruby][] is my language of choice. I used to use [C++][c-plusplus], but I was enchanted by the flexibility of Ruby: it lets me focus on creating the proper design and architecture for the system. [Java][] has an older style, but I sometimes use it to leverage the JVM (especially its garbage collector) and the multithread libraries. These features make Java one of the most mature platforms around. I'll also use [C][] if I need it for performance optimizations.

As for desktop software, I use [Chrome][] for the web and [Sparrow][] for email. I use [Numbers][] to draw diagrams quickly for documentation. It may come across as an odd choice, but it's simple and just works for me. I also use [Illustrator][] to design websites (ex: [msgpack.org](http://msgpack.org/ "The MessagePack site.")) and use [InDesign][] to edit articles.

[Twitter](https://twitter.com/frsyuki "Sadayuki on Twitter.") is an important channel for communicating with open source collaborators. I use [YoruFukurou][] on Mac OS X and [Echofon][echofon-ios] on iPhone for clients. I use search tabs to look for feedback on my programs on Twitter.

I also like [Gyazo][], a simple tool to share screenshots quickly. It's like [Gist][] for screenshots.

I want to mention [Quicksilver][] as well, a small but awesome launcher utility.

### What would be your dream setup?

If anything is possible, I want a magical compiler that turns designs in my brain into working code, but I am pretty happy with my current setup =)

Footnotes:

1: MessagePack now has a community for each language implementation, and development is modular. I oversee the overall direction and philosophy of the project, but development has been handed over to the experts of each language.

2: My home servers were built from cheap parts, with the exception of Intel PRO/1000 NIC, which was needed to boost network performance.

[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[chef]: https://www.chef.io/products/chef-infra "Configuration management software."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[ec2]: https://aws.amazon.com/ec2/ "A web service for virtualised processing."
[echofon-ios]: http://web.archive.org/web/20230120201805/https://apps.apple.com/us/app/echofon-for-twitter/id286756410 "A Twitter client for iOS."
[fluentd]: https://www.fluentd.org/ "A log collector."
[gist]: https://gist.github.com/starred "A version controlled code snippets service."
[github]: https://github.com/ "A Git code repository service."
[gperftools]: https://github.com/gperftools/gperftools "A set of performance tools for C++ developers."
[gyazo]: https://gyazo.com/ "A screenshot capturing and sharing tool for the Mac."
[ha-fxc51]: http://web.archive.org/web/20151224222922/http://www.amazon.com:80/JVC-HA-FXC51-B-Micro-High-Definition-Headphone/dp/B003P19YL2 "In-ear headphones."
[happy-hacking-keyboard]: https://en.wikipedia.org/wiki/Happy_Hacking_Keyboard "A computer keyboard."
[illustrator]: https://www.adobe.com/products/illustrator.html "A vector graphics editor."
[indesign]: https://www.adobe.com/products/indesign.html "A desktop/web publishing application."
[instruments]: https://en.wikipedia.org/wiki/Instruments_(application) "A Mac developer tool for analysing an application's performance."
[intuos]: https://www.wacom.com/en-us/products/pen-tablets/wacom-intuos "A pen tablet."
[java]: http://web.archive.org/web/20221226094350/https://www.java.com/en/ "A cross-platform compiled programming language."
[jenkins]: https://www.jenkins.io/ "A continuous integration server."
[kumofs]: http://web.archive.org/web/20201109002550/http://kumofs.sourceforge.net/ "A distributed key/value storage system."
[ls4]: http://web.archive.org/web/20190506065321/http://ls4.sourceforge.net/ "A distributed storage system."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[messagepack]: https://msgpack.org/ "A binary serialisation format, similar to JSON."
[numbers]: https://www.apple.com/numbers/ "A spreadsheet application for the Mac."
[quicksilver]: https://qsapp.com/ "A data manipulator and launcher for the Mac."
[realforce-103u]: http://web.archive.org/web/20150502060328/http://elitekeyboards.com/products.php?pid=rf_se0200 "A capacitive keyboard."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[sparrow]: http://www.gmail.com/intl/en/mail/help/sparrow.html "A mail client for the Mac with a funky UI."
[thunderbolt-display]: https://www.apple.com/displays/ "A Thunderbolt-powered monitor."
[travis]: https://www.travis-ci.com/ "A hosted continuous integration service."
[valgrind]: https://valgrind.org/ "An instrumentation and analysis tool for developers."
[xcode]: https://en.wikipedia.org/wiki/Xcode "An IDE for Mac developers."
[yorufukurou]: http://web.archive.org/web/20230503120602/https://sites.google.com/site/yorufukurou/ "A Twitter client for the Mac."
