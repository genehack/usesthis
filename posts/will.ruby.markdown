---
title: Will Ruby
summary: Designer, photographer, teacher
date: 2020-04-15
categories:
- designer
- mac
- photographer
- teacher
---

### Who are you, and what do you do?

My name is [Will Ruby](http://www.willruby.com/ "Will's website."), I'm a designer, a [photographer](https://www.instagram.com/williamruby/ "Will's Instagram account."), and a teacher. For my day job I build prototypes of new software or features, and also do installation work for [cultural](https://theblog.adobe.com/visualizing-the-invisible/ "An Adobe post about San Diego's MOPA and its interactive exhibitions.") [institutions](https://www.sfmoma.org/read/on-collaboration-sfmoma-adobe-rethink-selfie/ "An SFMOMA article about their exhibit with Adobe on rethinking selfies."). I've also recently DP'd a [music video](https://vimeo.com/376732439 "A Silverware music video on Vimeo.").

I'm a designer by [training](https://www.collegeforcreativestudies.edu/academics/undergraduate-programs/graphic-design "The communication design undergraduate program at CCS."), but most often find myself doing the work of design with code, and am really interested in tool building as a discipline, specifically, how does it effect outcomes that so many of us use the same set of tools?

### What hardware do you use?

I have a venerable 2015 15 inch [MacBook Pro][macbook-pro] with the old good keyboard that I use primarily for working. I also like that it has Thunderbolt ports for things like [Black Magic video interfaces][ultrastudio-mini] and their older cameras. Most of that stuff has moved to USB-C, but its nice to have more ports when you're working with a lot of peripherals.

For the museum work I like the idea of novel inputs and outputs as a way to distinguish a museum installation from an app you could install on your phone, so we've done stuff like attaching dishes of silicon oil to speakers, or make cymatic style light tables from frosted glass with camera's underneath. For lights on that kind of thing I like Aputure, they generally can run off of AC and hold up pretty good to always on setups, while still being pretty affordable if you have to replace them.

We've used Logitech's [BRIO webcams][brio] and I've been pretty happy with them, though I tend to prefer cameras that take manual lenses, I've used [Rokinon][14mm-f2.8-if-ed-umc] and Veydra lenses in EOS and Micro 4/3 format in cabinets at museums. The internal structure of those cabinets we build out of 80/20 which is essentially grown up erector set, and they'll precut and mill to your specifications if you order it through the site, which makes it pretty accessible if you don't have a shop setup, and sturdy.

I've also used [Raspberry PIs][raspberry-pi] for some small personal work, the [Zeros][raspberry-pi-zero] are super cool for how small and cheap they are, and I really like the accessories that PiMoroni makes, specifically their [Scroll pHAT HD][scroll-phat-hd]. The [Arduboy][] is also super fun and I've built a [few small games](https://github.com/whatsim/zaibatsu "Will's GitHub repo of games for the Arduboy.") for it.

I'm primarily a film shooter in my photographic practice and I'll spare you the whole list, but I use a Rollei [35 S][35-s], an original [Soviet LC-A][lc-a], an Olympus [Pen F][pen-f], and a Canon [P][] primarily, though that changes with the weather. The Canon P I use has a 50s vintage Summitar 5cm f/2 which takes great photos.

For film, I really like Lomo's Berlin Kino, and Kodak Color Plus right now. With the current lockdown happening in the world, I've also gotten back into home developing for black and white using the [Paterson Super System 4][super-system-4] and Rodinal.

I scan all that stuff myself with a first gen [Canon 6D][eos-6d] and the excellent [Canon EF 100mm macro][ef-100mm-f2.8l-is-usm], a 3D printed 35mm film track, a [backlight][ipad-pro], and a camera rail setup mostly from SmallRig to hold everything square and level.

I do a lot of my scan touch up on the bus with my iPhone, too.

### And what software?

I'm mostly on [macOS][], and for code, I use [Sublime Text][sublime-text], I used to spend a lot of time getting it configured just right but slowly as my themes have all broken I'm using a pretty cobbled together version of it. I use the built in macOS [Terminal][].app still pretty happily. The Adobe tool stuff I use a fair amount though mostly in a production capacity, [Photoshop][] and [Illustrator][]. [InDesign][] and [Lightroom][] I use more for photography stuff, including a custom camera profile for my film scanning stuff made with the DNG Profile Editor.

For museum stuff, particularly experimenting with cameras and shader pipelines, I use [VDMX][], though we generally install built native applications. I've recently experimented with [OPENRNDR][] for that sort of work.

I'm primarily a web platform person at this point, and really like [Glitch][glitch.3], and use it heavily for my classes and also just quick sketches of ideas. When I deploy stuff it's primarily [nodejs][node.js] or static files behind [nginx][], and I use [Certbot][] for SSL, though not as much as I should probably. My main box is on [DigitalOcean][] and I use [Cyberduck][] as my FTP client.

For libraries in JS I mostly avoid them if I can, but [ExpressJS][express.2] and [WS][] are useful enough to get over that bias. I've also used [SeriouslyJS][seriously.js] for shaders on the web a lot, I like that they mostly let you just write your own shader in GL, though have started to lean more toward [TWGL][] for that. Otherwise I tend to like my JS vanilla. SVG Filters are also cool for [quick and dirty stuff](https://sulky-gigantic-tarsier.glitch.me/ "Will's SVG filter project on Glitch.").

My [class site](http://fall2019.will.graphics/ "Will's class website.") is built on a nodejs static site generator of my own, and uses JS String Templates as its theme engine, and [Markdown][] and JSON in a folder tree as its data source. I use git to track revisions to that content over time, that's then hosted behind nginx.

For communication, I'm mostly on [Slack][] and [Messages][] at this point, and I have [Spotify][] and [Chrome][] permanently open too.

### What would be your dream setup?

I'd love if Apple just made 2015 MacBook Pro's with new guts and an equivalent number of modern ports. That'd be amazing. And a drum scanner for film that worked with modern software out of emulation would be great as well.

I used to play with [Plask][] when it was under development, and a real JS graphics card forward development environment would be killer. You can do a lot of that stuff in browser but it requires a fair amount of boiler plate, and making apps in [Electron][] still feels kind of hacky to me. Someday I'll learn [Unity][] properly.

[14mm-f2.8-if-ed-umc]: http://web.archive.org/web/20211217221744/https://www.bhphotovideo.com/c/product/769532-REG/Rokinon_FE14M_C_14mm_Ultra_Wide_Angle_f_2_8.html "A camera lens."
[35-s]: http://camera-wiki.org/wiki/Rollei_35#Rollei_35_S "A film camera."
[arduboy]: https://www.arduboy.com/ "A hackable portable game console."
[brio]: https://www.logitech.com/en-us/product/brio.html "A webcam."
[certbot]: https://certbot.eff.org/ "A tool for automatically downloading and managing SSL certificates."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[cyberduck]: https://cyberduck.io/ "An FTP/SFTP client."
[digitalocean]: https://www.digitalocean.com/ "An SSD-based web hosting service."
[ef-100mm-f2.8l-is-usm]: http://web.archive.org/web/20151008110016/http://www.usa.canon.com:80/cusa/consumer/products/cameras/ef_lens_lineup/ef_100mm_f_2_8l_macro_is_usm "A macro lens."
[electron]: https://www.electronjs.org/ "A developer tool for building desktop apps with web technology."
[eos-6d]: https://en.wikipedia.org/wiki/Canon_EOS_6D "A 20.2 megapixel DSLR."
[express.2]: http://expressjs.com "A JavaScript web framework."
[glitch.3]: https://glitch.com/ "A web-based IDE."
[illustrator]: https://www.adobe.com/products/illustrator.html "A vector graphics editor."
[indesign]: https://www.adobe.com/products/indesign.html "A desktop/web publishing application."
[ipad-pro]: https://en.wikipedia.org/wiki/IPad_Pro "An iOS tablet."
[lc-a]: https://en.wikipedia.org/wiki/Lomo_LC-A "A very popular film camera."
[lightroom]: https://www.adobe.com/products/photoshop-lightroom.html "Photo management and editing software."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[markdown]: https://daringfireball.net/projects/markdown/ "An email-like format for marking up text."
[messages]: https://en.wikipedia.org/wiki/Messages_(application) "A chat client for Mac."
[nginx]: http://nginx.org/ "A very fast web/mail server."
[node.js]: https://nodejs.org/en "A Javascript application platform."
[openrndr]: https://openrndr.org/ "A framework for creating interactive applications."
[p]: http://camera-wiki.org/wiki/Canon_P "A film camera."
[pen-f]: http://camera-wiki.org/wiki/Olympus_Pen_F "A film camera."
[photoshop]: https://www.adobe.com/products/photoshop.html "A bitmap image editor."
[plask]: http://www.plask.org/ "A multimedia programming tool."
[raspberry-pi-zero]: https://www.raspberrypi.com/news/raspberry-pi-zero/ "A tiny hackable computer."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[scroll-phat-hd]: https://shop.pimoroni.com/products/scroll-phat-hd "A set of programmable lights."
[seriously.js]: https://github.com/brianchirls/Seriously.js/ "A web-based video compositor framework."
[slack]: https://slack.com/intl/ja-jp/ "A collaboration service."
[spotify]: https://open.spotify.com/__noul__?pfhp=2c2ccb58-8a92-4713-a1c0-8b43b3090b49 "A music streaming service."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[super-system-4]: https://www.patersonphotographic.com/product/paterson-super-system-4-developing-tanks/ "Developing tank for film."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[twgl]: https://twgljs.org/ "A library for working with WebGL."
[ultrastudio-mini]: https://www.blackmagicdesign.com/products/ultrastudio "A little video capture device."
[unity]: https://unity.com/products "A cross-platform game development tool."
[vdmx]: https://vidvox.net/ "Real-time video studio software for the Mac."
[ws]: https://github.com/websockets/ws "A WebSocket library for Node."
