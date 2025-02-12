---
title: Chris Slowe
summary: Chief scientist (Hipmunk)
date: 2011-09-23
categories:
- mac
- scientist
---

### Who are you, and what do you do?

Chief scientist at [Hipmunk][], formerly first and longest employee at reddit, and before that experimental Physics PhD at Harvard (where the scientist bit comes from). I'm 32, married, and have an almost-3-month-old daughter.
 
Since it's a small start up, we all wear a lot of hats, but on average I end up working on the projects that require the most data crunching/analysis. I do the heat maps for our hotel search (scraping Wikipedia, OpenStreetMaps, and SimpleGeo to figure out where the interesting parts of a given city are). I do a lot of work trying to maintain consistency across our hotel inventory (merging up 6 different providers with varying levels of corruption) and spent some time trying to map the data we have on hotels to some estimation of the actual quality of the place.

### What hardware do you use?

Personally, there's an [iPhone 4][iphone-4] in my pocket, a first gen [iPad][] in my backpack, a [MacBook Pro][macbook-pro] on my desk for work, and a [Mac Mini][mac-mini] hooked up to my TV. It's not that I'm a fan boy so much as I've done my time dealing with Windows and I'm too lazy/busy to deal with Linux. I also find them pretty.

At Hipmunk, we have about 15 servers somewhere on the west coast on Amazon's [EC2][] running [Ubuntu][].

### And what software?

For the software side of things, we run [Python][] for the vast majority of our scripts as well as for our webserver processes. The latter is powered by [Tornado][], which is one of the few asynchronous web frameworks, originally used to power Friendfeed. The main advantage here is speed: each Python process is single-threaded and the framework is structured in such a way that rather than blocking on I/O it switches out to work on another task that has been queued up. The hard bit about using it is that Python isn't really designed around asynchronous code and a lot of the time it feels like you're writing inside-out and backwards. At the moment we have about 20 processes running Hipmunk sitting behind a software load balancer by the name of [HAProxy][].

Since half of the site is the presentation of flight data (which is necessarily volatile), for the first few months of Hipmunk's existence we didn't actually have a back end datastore or database, but rather processed and represented flight data from third party sources (Orbitz, airlines, and later directly from ITA who typically backs the first two). Each request to Hipmunk fires off N requests to each of these sources which we process, organize, and present.

Much later, when we moved into hotel booking and started doing more detailed event tracking we added [MongoDB][] as our primary datastore. For hotels, we pull lists of available properties from each provider, merge them up by trying to find commonalities among them, and the chew on them in no small amount to try to remove bad data (of which there is a surprisingly large amount -- part of where I come in). It's this Mongo datastore that we query to find out which properties to ask each provider for when doing hotel searches.

For the front end, we do our templating in Python in [Mako][] (which we also used heavily on reddit -- a great engine IMO), though at this point Hipmunk is actually for the most part one single page, with different "pages" constructed from the contents of the url fragment (after #!) powered by a lot of [JavaScript][] and send via AJAX. We have so much JS in fact we recently invested the time in converting it to a language called [CoffeeScript][] which is just awesome, removing a lot of JS's rough edges (cleaner scoping, better handling of "this", Pythonic syntax, and avoiding type-casting around equality tests just to name a few). We also do all of our CSS work in [Sass][], which plays the same role as rough-edge-remover.

Last but not least, the software I actually run at any given time is 90% [Emacs][], [Terminal][], and [Chrome][]. A decent fraction of the last 10% may or may not be [Steam][], but, if it were, I'd say its fraction has been cut down a lot since my daughter was born in April.

Oh and [VMware][vmware-fusion]. How could I forget about that lovely piece of software? IE9 with the proper DOCSTRING acts almost like it were a real browser, and is close enough that we normally don't have to give it special treatment. It sometimes makes me feel nostalgic: like I'm working on an early [Firefox][] 3 RC.

With IE8 on the other hand, there is still no such luck, and it typically requires some special treatment to get those last few pixels of layout just so. (We don't even try any more on IE7 and less but rather encourage the user to download chrome frame). Point is, seeing as the only way to run IE is via windows (How silly is that, when you really think of it? A browser is completely different from all the rest, closed source, and running only on one OS? How quaint...), which is where VMware comes in. It's wonderful to be able to run IE8 and 9 right next to each other along with Chrome and Firefox in the same screen to squeeze out those last few pixels that IE insists must be there.

### What would be your dream setup?

Honestly and truly, I'm waiting for an awesome pair of glasses that projects the screen right on my retina.  I mean, for one, retina display or no, I have this absurdly powerful computer that I keep with me in my pocket whose capacity for video is limited by the form factor of my pocket. This seems silly. 

By the same token, I can't seem to get enough screen real estate on my desk/laptop. I've been contemplating getting a [Mac Pro][mac-pro] just so I could have a third monitor. (Though the extra RAM would probably be nice too). Other than that, my hardware demands are probably pretty typical (lots of RAM, MOAR CORES!). SSDs have been life-changing, so a bigger one of those would be nice.

Honestly, though, I feel like the worst part of these days isn't the hardware but the size of the pipe. I think I'd contentedly keep my current rig (with my piddly two huge screens and small, almost full SSD) if I could get a no-cap GBit connection to the Internet on all of my devices. If the pipe is big enough, who cares that my local computer is a little hardware anemic?

[chrome]: https://www.google.com/intl/en/chrome/browser/ "A WebKit-based browser, where each tab runs in its own thread."
[coffeescript]: https://coffeescript.org/ "A language that compiles into Javascript."
[ec2]: https://aws.amazon.com/ec2/ "A web service for virtualised processing."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[haproxy]: http://www.haproxy.org/ "TCP/HTTP load balancer software."
[hipmunk]: https://www.hipmunk.com/ "A service for finding hotels and flights."
[ipad]: https://www.apple.com/ipad/ "A tablet device."
[iphone-4]: https://en.wikipedia.org/wiki/IPhone_4 "A smartphone."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[mako]: https://www.makotemplates.org/ "A templating system for Python."
[mongodb]: https://www.mongodb.com/ "A document-based database."
[python]: https://www.python.org/ "An interpreted scripting language."
[sass]: https://sass-lang.com/ "A syntax wrapper for CSS."
[steam]: https://store.steampowered.com/ "A digital game distribution service."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[tornado]: http://www.tornadoweb.org/en/stable/ "A fast web server."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
[vmware-fusion]: https://www.vmware.com/products/fusion.html "A PC emulator for the Mac."
