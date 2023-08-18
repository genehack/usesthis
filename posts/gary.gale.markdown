---
title: Gary Gale
summary: Geotechnologist
date: 2018-08-21
categories:
- developer
- geo
- linux
- mac
---

### Who are you, and what do you do?

Hi! I'm [Gary](https://www.garygale.com/ "Gary's website."). That's the easy part out of the way. What I do is somewhat more complex.

I'm a _geotechnologist_; which really means I lead and manage teams of really clever people who make software products that use geography,
geospatial data and location data. Or to put it another way, I do _maps and stuff_. If I had a penny for every time someone's said _just put it on a map_ I'd be a very rich person.

I started out in the last millenium, as an operator (anyone remember [6250 density magtape](https://en.wikipedia.org/wiki/Magnetic_tape_data_storage "The Wikipedia entry for magbetic tape data storage.")?) and then as a programmer on [DEC VAX](https://en.wikipedia.org/wiki/VAX "The Wikipedia entry for VAX computers.") minicomputers writing assembler and [Fortran-77][fortran], then writing [C][] and [C++][c-plusplus] on the various commercial flavours of [UNIX](https://en.wikipedia.org/wiki/Unix "The Wikipedia entry for UNIX.") ([OSF/1][osf-1], [Solaris][], [Tru64 UNIX][tru64-unix] and [AIX][]) before I ending up using Linux and macOS.

These days I still try and stay hands on, because I never want to stop learning and building things, but I'm more involved in the leadership and strategy sides of technology; after 2 years as a CTO, I've spent the last year as a roving [consultant](https://malstow.com/ "Gary's consulting company.") and am just about to start a new role as a CTO again.

### What hardware do you use?

I haven't had a work desktop computer since 2006 as, for the past 12 odd years, my job has meant I've ended up working not only in an office but also, thanks to a combination of [trains, planes and automobiles](https://en.wikipedia.org/wiki/Planes,_Trains_and_Automobiles "The Wikipedia entry for the movie Plains, Trains and Automobiles."), in coffee shops, meeting rooms, conference venues and quite a few airport lounges. That means I rely on a laptop which is only infrequently plugged into an external monitor. And since 2006 that laptop has been a [MacBook Pro][macbook-pro], starting at the first generation _no it's not a PowerBook G4 it just looks like one_ model up to 2016's fourth generation _what is the touch bar for really_ model.

I'm going to pause here for a moment and reflect on the new MacBook Pro. I know it's easy to say _things aren't built like they used to be_ but with the fourth generation model, Apple seem to have lost their way. It's not clear to me what's _Pro_ about this model apart from a few more USB-C ports. I get that USB-C is _possibly_ the future but the rest of the world hasn't caught up yet. I don't get that I can't _upgrade_ the SSD or RAM once I've bought a new MacBook Pro. This model seems to be more about taking away rather than improving on previous models.

All my previous MacBook Pros have been reliable, rock solid and I've had one disk failure in all of that time, which I could and did swap out myself. I've even had one machine that survived around a meter and a half fall out of a rucksack onto a volcano in Iceland (it's a long story); granted, it had a few cracks and some _interesting_ curves in the unibody, but it continued to be used day in, day out, for a further two years after that.

Maybe it's just bad luck but maybe it's telling that as I write this my fourth generation work horse is with my local Apple store having the keyboard, SSD and logic board replaced.

But when my machine _does_ return and _when_ I am sitting at a desk, it'll be plugged into the biggest monitor I can get away with, also plugged into a [Belkin Thunderbolt 3 Express Dock][thunderbolt-3-express-dock-hd] with my backup drives and paired with a [Magic Keyboard][magic-keyboard] (with numeric keypad) and a [Magic Mouse 2][magic-mouse-2].

Lying close to my laptop or in my back pocket will be my  [iPhone 7][iphone-7], with the hope of an [iPhone X][iphone-x] coming along soon, and an [iPad mini][ipad-mini].

At home things are a little more ... _eclectic_.

Sitting behind my ISP supplied cable modem is a [Linksys 1900ACS][wrt1900acs] that's been reflashed with [DD-WRT][]. There's a [Raspberry Pi][raspberry-pi] running [Pi-Hole][] which not only blocks ads and tracking across my LAN but also uses [Cloudflare's][cloudflare] encrypted DNS. There's another Pi sitting behind the main TV which acts as the media centre for our NAS thanks to [OSMC][] plus an Amazon [Fire TV Stick][fire-tv-stick] and an old [Apple TV][apple-tv] that I can't remember when we last used it. I should probably unplug that at some point. I'm also running yet another Pi, connected to an external GPS receiver, that's an [NTP stratum 1](https://en.wikipedia.org/wiki/Network_Time_Protocol "The Wikipedia entry for the Network Time Protocol.") server for my LAN, just because I like building things like that. There's also a couple of [TiVo boxes][tivo], many disk drives and wifi points and other technical ephemera. There's even a [Windows 10][windows-10] laptop that gets used for school homework; when it's not rebooting itself to install whatever today's urgent bug fix or software update is.

### And what software?

On my _iDevices_ I read books via [Kindle][kindle-ios], and my news via [Flipboard][flipboard-ios], I also take notes via [Penultimate][penultimate-ios] and a stylus. I may even be guilty of playing the odd game occasionally, such as yet another tour around the wonders of [Monument Valley][monument-valley-ios]. But I still keep an A4 pad in my bag for random scrawling, just in case.

On my Mac, I use [Atom][] for editing, though can still drive [Vim][] for those remote SSH sessions. I keep a range of browsers for testing, but [Chrome][] is my usual browser of choice with the [1Password][], [Privacy Badger][privacy-badger] and [Pocket][] plugins, but I might yet be lured back to [Safari][] one day.

I use the command line, via a customised Mac [Terminal][] app _a lot_ and install software via [Homebrew][] whenever I can.

For poking around with geospatial data I use [`gdal`][gdal] to convert data into something usable that doesn't require enterprise software to work with, which usually means [GeoJSON](https://tools.ietf.org/html/rfc7946 "The IETF GeoJSON standard."). That also means I can try and make sense of the data with [Elasticsearch][] and [Kibana][]. For visualisation I use [QGIS][] and if I want to share a map based visualisation online [Leaflet][] has rarely let me down.

Not everything can run on [OS X][macos], sorry, _macOS_, so I tend to run a lot of virtual machines via [VirtualBox][] and [Vagrant][]. These are mainly Linux instances, either [CentOS][] or [Ubuntu][], but there's also a Windows 10 VM there too for those times when I have no choice but to run enterprise software which insists on a legacy version of [Internet Explorer][internet-explorer] or for ensuring that something runs as well on Windows as it does on a UNIX-a-like operating system.

Finally there's the usual tools of email, using my Mac's default [Mail][] client, browsing, mostly using Chrome, and a copy of [Office 365][office-365] for Mac. I much prefer Apple's [Keynote][] for slide decks, though I have nothing against [PowerPoint][].

There's a lot more than this, including local [Node][node.js], [Python][], [Ruby][], [Go][] and [PHP][] installs but I don't want to bore you to death.

### What would be your dream setup?

After 12 years of living and working in places where a desk appears around 50% of the time I've learned to be pragmatic and if I can live without something for 3 months without going over the edge, then I probably don't really need it or it's not worth obsessing over.

But if I really _had_ to dream it would look something like a third generation MacBook Pro, but with the ability to upgrade the components rather than being stuck with what you initially bought. It would have the latest and greatest set of ports but also support older hardware which still works well, so why should I have to buy a dongle or replace stuff? It would have the power of something akin to a [Mac Pro][mac-pro] but be lightweight enough to lug between offices and meetings without booking an appointment with the osteopath. It would be able to power multiple external monitors and wouldn't need a specialist docking station or half an hour of plugging stuff in followed by unplugging everything because there's _another_ meeting I absolutely have to go to. And it would have onboard cellular data connectivity because free wifi is rarely around or reliable when you really need it (and no, tethering is not the same thing as that rarely works outside of my home coutry without paying eye watering sums of money for this). I'd happily trade [Siri][] integration (I've never found the need) and the new touch bar for something like that.

Maybe I'm really talking about a [Hackintosh](https://hackintosh.com/ "A site linking instructions for building your own Hackintosh.") but apparently there's [laws and copyright](https://fossbytes.com/what-is-hackintosh-computer-laptop-legal-os-x-macos/ "A Fossbytes article on the legal risks of running a Hackintosh.") that get in the way of that. Maybe we should fix the intellectual property and copyright laws instead? Or maybe that's too much dreaming for one day.

[1password]: https://1password.com "Password management software for Mac OS X."
[aix]: https://en.wikipedia.org/wiki/IBM_AIX "A UNIX operating system."
[apple-tv]: https://en.wikipedia.org/wiki/Apple_TV "A device for viewing media on a TV."
[atom]: https://github.blog/2022-06-08-sunsetting-atom/ "A text editor based on web technology."
[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[centos]: https://www.centos.org/ "A Linux distribution."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[cloudflare]: http://web.archive.org/web/20230525002940/https://www.cloudflare.com/ "A security and content delivery service."
[dd-wrt]: http://web.archive.org/web/20180521190036/https://www.dd-wrt.com/site/index "A alternative Linux-based firmware for routers."
[elasticsearch]: http://web.archive.org/web/20230815140403/https://www.elastic.co/elasticsearch/ "Distributed search engine software."
[fire-tv-stick]: http://web.archive.org/web/20230130044925/https://www.amazon.com/Amazon-Fire-TV-Stick-With-Alexa-Voice-Remote-Streaming-Media-Player/dp/B00ZV9RDKK/ "A device for streaming media to a TV."
[flipboard-ios]: https://apps.apple.com/us/app/flipboard-your-social-news/id358801284 "A 'social magazine' for the iPad."
[fortran]: https://en.wikipedia.org/wiki/Fortran "A compiled programming language."
[gdal]: https://gdal.org/ "A library for translating geospatial data formats."
[go]: https://go.dev/ "A compiled programming language."
[homebrew]: https://brew.sh/ "Command-line package manager for Mac OS X."
[internet-explorer]: https://en.wikipedia.org/wiki/Internet_Explorer "A PC web browser."
[ipad-mini]: https://www.apple.com/ipad-mini/ "A 7.9 inch tablet device."
[iphone-7]: https://en.wikipedia.org/wiki/IPhone_7 "A 4.7 inch iOS smartphone."
[iphone-x]: https://en.wikipedia.org/wiki/IPhone_X "A 5.8 inch smartphone."
[keynote]: https://www.apple.com/keynote/ "Presentation software for the Mac."
[kibana]: https://www.elastic.co/kibana "Software for exploring data in Elasticsearch."
[kindle-ios]: https://apps.apple.com/gb/app/kindle/id302584613 "An iPhone app for accessing Kindle content from Amazon."
[leaflet]: https://leafletjs.com/ "A JavaScript library for working with maps."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[magic-keyboard]: https://en.wikipedia.org/wiki/Magic_Keyboard "A wireless keyboard."
[magic-mouse-2]: https://en.wikipedia.org/wiki/Magic_Mouse_2 "A multi-touch mouse."
[mail]: https://en.wikipedia.org/wiki/Mail_(application) "The default Mac OS X mail client."
[monument-valley-ios]: https://apps.apple.com/us/app/monument-valley/id728293409 "A pretty puzzle/adventure game."
[node.js]: https://nodejs.org/en "A Javascript application platform."
[office-365]: https://en.wikipedia.org/wiki/Office_365 "A hosted office suite."
[osf-1]: https://en.wikipedia.org/wiki/Tru64_UNIX#OSF/1 "A UNIX operating system."
[osmc]: https://osmc.tv/ "Open source media center software."
[penultimate-ios]: https://apps.apple.com/us/app/penultimate/id354098826 "A digital sketchbook app."
[php]: https://www.php.net/ "An interpreted scripting language."
[pi-hole]: https://pi-hole.net/ "Linux-based ad blocking software."
[pocket]: https://getpocket.com/en/ "A service for storing links to look at later on."
[powerpoint]: https://www.microsoft.com/en-us/microsoft-365/powerpoint "Presentation software."
[privacy-badger]: https://privacybadger.org "A browser extension for blocking trackers and ads."
[python]: https://www.python.org/ "An interpreted scripting language."
[qgis]: https://qgis.org/en/site/ "An open-source GIS mapping tool."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[safari]: https://www.apple.com/safari/ "A fast web browser."
[siri]: https://en.wikipedia.org/wiki/Siri "An intelligent personal assistant service."
[solaris]: https://www.oracle.com/us/products/servers-storage/solaris/resources/index.html "An operating system."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[thunderbolt-3-express-dock-hd]: https://www.belkin.com/thunderbolt-3-express-dock-hd---dual-4k-display-85w-psu/P-F4U095.html "A Thunderbolt dock."
[tivo]: http://web.archive.org/web/20230706210923/https://business.tivo.com/jp/ "A digital TV recording system."
[tru64-unix]: https://en.wikipedia.org/wiki/Tru64_UNIX "A UNIX operating system."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[vagrant]: https://www.vagrantup.com/ "Software for building and installing virtual dev environments."
[vim]: https://www.vim.org/ "A command-line text editor."
[virtualbox]: https://www.virtualbox.org/ "Open-source virtualisation software."
[windows-10]: https://en.wikipedia.org/wiki/Windows_10 "An operating system."
[wrt1900acs]: https://www.linksys.com/wrt1900acs-dual-band-wi-fi-router-with-ultra-fast-1.6-ghz-cpu/WRT1900ACS.html "A dual-band wifi router."
