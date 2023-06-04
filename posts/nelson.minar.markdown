---
title: Nelson Minar
summary: Software engineer
date: 2018-06-21
categories:
- developer
- linux
- windows
---

### Who are you, and what do you do?

I'm a software engineer, these days more of a gentleman programmer. I work on a variety of projects and am interested in [maps](https://github.com/NelsonMinar/vector-river-map "Nelson's vector river map project on GitHub."), [open data][openaddresses], and [data visualization][d3.js]. I tend to follow technologies that allow you to quickly build amazing things; mapping reached that inflection point a few years ago. These days I'm getting up to speed on machine learning; it's amazing how easy it is to bash together a workmanlike learning system. I'm probably best known for my work on web services like the Google AdWords API. The most recent public thing I released is [Wanderings][], a lightweight location tracker for creating a personal record of where you've been.

### What hardware do you use?

I sit in front of Windows machines. Generic Intel desktop with a fancy gamer GPU and a single big 3440x1440 monitor that supports [G-Sync](https://en.wikipedia.org/wiki/Nvidia_G-Sync "The Wikipedia entry for G-Sync.") for nice variable framerate display. For a laptop I have a 2017 [Razer Blade][blade], also a gamer system. I like gaming and the GPU doubles as a machine learning platform. Also gamer hardware seems like higher quality fit-and-finish. 

I used to use Macs but gave up on them a couple of years ago when [macOS][] kept getting worse. PC hardware is definitely not as nice as Apple hardware, even the Razer Blade is a poor second to the best older [MacBook Pros][macbook-pro]. End of the day all I care about is if it runs a web browser and pretty much anything can do that; Leonard Lin's [use of Chromebooks](https://usesthis.com/interviews/leonard.lin/ "Leonard's Uses This interview.") caught my attention.

A lot of my real work takes place on Linux boxes running [Ubuntu][]. I have a couple of headless servers at home and a leased bare metal server in a data center in Kansas City. I've got an iPhone in my pocket and an iPad that mostly just runs the [Kindle app][kindle-ios]. Home entertainment runs off of Sonos and a [Roku][] running [Plex][]. I use Ubiquiti networking gear including a really elaborate fixed wireless setup to deal with rural geography.

### And what software?

A web browser is what's front-and-center 90% of the time I'm working. I mostly use [Firefox][], switched from [Chrome][] when [Quantum](https://blog.mozilla.org/blog/2017/11/14/introducing-firefox-quantum/ "A Mozilla post about the newer version of Firefox.") came out. [1Password][] is essential for managing logins. I rely on [uBlock Origin][ublock-origin] and [Privacy Badger][privacy-badger] to remove unwanted crap from web pages. Once I quit working on ads at Google I became zealous about blockers. The intrusions and malware shoveled into our web browsers now is [unconscionable](http://www.somebits.com/weblog/tech/bad/ad-blocking-is-self-preservation.html "Nelson's post about ad blocking.").

I have a few UI [customizations](https://nelsonslog.wordpress.com/2017/02/09/windows-customizations/ "Nelson's post about customising Windows.") that are essential to me. One is to bind Caps Lock to search Google via [an AutoHotkey script](https://gist.github.com/NelsonMinar/737478 "Nelson's AutoHotkey script gist."). Now that big fat key on the home row does something useful; copy some text and hit Caps Lock and boom, up pops a browser window. I also use [Hain][] for launching programs, I type Win-Space and the first few letters of the program name and it launches. I miss [Alfred][] for doing this on macOS, it is really lovely.

One of the ways I make Windows work for me is I run Ubuntu in it via the [Windows Subsystem for Linux][windows-subsystem-for-linux]. WSL is an amazing accomplishment by Microsoft. It's a full Linux kernel API emulator that runs actual Linux binaries under the Windows kernel. Some things like filesystems are a bit wonky but in general I have a fully working Ubuntu environment for my Windows box.

When I'm writing code I use [Sublime Text 2][sublime-text] with minimal customizations. I really just want a simple editor; back in the 90s I was a big [emacs nerd](http://www.nbi.dk/TOOLS/emacs/html-helper-mode/index.html "Nelson's html-helper-mode documentation for emacs.") but now think its tty interface, awkward keys, and overcustomizability are all damaging throwbacks to a bad old era before humane user interfaces. Sublime Text 2 is fine and looks nice. I use [Simplenote][] for quick notes where I don't want to think about where the file is saved and [mg][] when I need a tty editor in Linux.

I mostly program in [Python 3][python] and seem to be using [pandas][] a lot for data processing. I'm also a huge fan of [Jupyter Notebooks](http://www.somebits.com/weblog/tech/good/jupyter-ipython-notebooks.html "Nelson's post about Jupyter Notebooks."), they are [revolutionary](https://www.theatlantic.com/science/archive/2018/04/the-scientific-paper-is-obsolete/556676/ "An article in The Atlantic about scientific papers.") for sharing data science computation. (Check out [Observable][] if you do [JavaScript][]).

Most of my map work is custom code backed by [PostGIS][]. [GeoJSON.io][] is great for sharing geodata on a web page map and occasionally I bust out [QGIS][] for a desktop app. My visualizations are usually in JavaScript using [Leaflet][] or [Mapbox GL JS][mapbox-gl-js].

[Slack][] is my social media of choice, although of course I'm on Twitter and Facebook too. A few [Discord servers][discord] too; Discord is marketed as Slack for gamers but it works fine for other communities too. I spend a lot of time on [MetaFilter][] and [Reddit][], that's how I keep up with new stuff. Also [belong.io](http://belong.io/ "Andy Baio's collection of interesting links.").

For publishing I still run an old school [blog](http://www.somebits.com/weblog/ "Nelson's weblog.") using the ancient Perl engine [Blosxom][]. But I write much more sloppily and prolifically on [my secret work blog](https://nelsonslog.wordpress.com/ "Nelson's work weblog.") which is hosted at wordpress.com. I also run a blog of interesting links which is a [Pinboard account](https://pinboard.in/u:nelson "Nelson's Pinboard account.") published in various forms, notably a [Twitter feed](https://twitter.com/somebitslinks "Nelson's Twitter account for interesting links.").

### What would be your dream setup?

The most important problem to solve in consumer Internet right now is secure logins. Passwords are a terrible form of authentication. A password agent like 1Password or [LastPass][] helps but they are clumsy kludges. "Guess which HTML form element is a password and fake a keyboard paste to fill a random string from a third party program"; is that really the best login system we can imagine? Of course not. Also it terrifies me how tiny those two companies are that literally hold the keys to everyone's kingdoms; I assume they've both been compromised. It's a great shame [OpenID](https://en.wikipedia.org/wiki/OpenID "The Wikipedia entry for OpenID.") and [Mozilla Persona](https://en.wikipedia.org/wiki/Mozilla_Persona "The Wikipedia entry for Mozilla Persona.") failed, they had excellent technical solutions for authentication. I was about ready to say "fuck it" and let Facebook manage all my logins but given how untrustworthy they've turned out to be that's clearly not reasonable. I've thought about starting a product company for authentication but it's not really a technical problem, it's a business strategy problem. And it's a business with an enormous liability risk attached to it.

I also wish thin client cloud computing would become a reality. I spend far too much time thinking about where my data is or where various programs I use are installed or configured. (Shout out to [FreeFileSync][], a good interactive tool for shuttling files around.) Can't all my stuff just be in the cloud already? The gaming world has kind of solved that with various [cloud gaming](https://www.reddit.com/r/cloudygamer/ "The cloudygamer subreddit.") services. You'd think the latency and bandwidth requirements would make gaming the worst candidate for a remote UI but it actually seems to work (although I don't use it). I'd love the same thing for my desktop environment. There's ways to kludge it together but I don't know anyone who works that way 24/7.

I'm looking forward to the 1990s dream of ubiquitous computing becoming a reality. I don't have much in the way of smart home devices and the ones I do are garbage. But some day I'm going to be able to talk to the thin air and express my intent and a beautiful display will hover in front of my face to show me what I asked for. We still have a long way to go on voice recognition and inference for that, not to mention projection technology.

[1password]: https://1password.com "Password management software for Mac OS X."
[alfred]: https://www.alfredapp.com/ "A launcher app for the Mac."
[blade]: https://www.razer.com/gaming-laptops/razer-blade-16 "A thin gaming PC laptop."
[blosxom]: https://en.wikipedia.org/wiki/Blosxom "A self-hosted web publishing tool."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[d3.js]: https://d3js.org/ "A Javascript framework for manipulating data."
[discord]: https://discord.com/ "A voice and text chat service."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[freefilesync]: https://freefilesync.org/ "A tool for syncing files between sources."
[geojson.io]: http://geojson.io/ "A web-based GeoJSON editor."
[hain]: http://hainproject.github.io/hain/ "A program launch for Windows."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[kindle-ios]: https://apps.apple.com/gb/app/kindle/id302584613 "An iPhone app for accessing Kindle content from Amazon."
[lastpass]: https://www.lastpass.com/ "A password manager."
[leaflet]: https://leafletjs.com/ "A JavaScript library for working with maps."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[mapbox-gl-js]: https://docs.mapbox.com/mapbox-gl-js/api/ "A JavaScript library for rendering maps with WebGL."
[metafilter]: https://www.metafilter.com/ "A community website."
[mg]: https://en.wikipedia.org/wiki/Mg_(editor) "A command line text editor."
[observable]: https://observablehq.com/ "A data visualisation service."
[openaddresses]: https://openaddresses.io/ "An open dataset of addresses."
[pandas]: https://pandas.pydata.org/ "A Python data analysis library."
[plex]: https://www.plex.tv/ "Media center software."
[postgis]: http://www.refractions.net/products/postgis/ "A PostgreSQL add-on that adds geographic support."
[privacy-badger]: https://privacybadger.org "A browser extension for blocking trackers and ads."
[python]: https://www.python.org/ "An interpreted scripting language."
[qgis]: https://qgis.org/en/site/ "An open-source GIS mapping tool."
[reddit]: https://www.reddit.com/?rdt=46296 "A messageboard service."
[roku]: https://www.roku.com/intl?next=/&source=www.roku.com "A device for streaming entertainment to your TV."
[simplenote]: https://simplenote.com/ "A note-taking/syncing service."
[slack]: https://slack.com/intl/ja-jp/ "A collaboration service."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[ublock-origin]: https://en.wikipedia.org/wiki/UBlock_Origin "A browser extension for blocking elements on the web."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[wanderings]: https://wanderin.gs/ "A personal location tracking service."
[windows-subsystem-for-linux]: https://learn.microsoft.com/windows/wsl/about "A Linux environment for Windows."
