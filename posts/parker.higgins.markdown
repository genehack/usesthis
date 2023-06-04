---
title: Parker Higgins
summary: Artist, activist (Freedom of the Press Foundation)
date: 2018-07-03
categories:
- activist
- artist
- developer
- linux
---

### Who are you, and what do you do?

My name is Parker Higgins, and I'm the Director of Special Projects at the [Freedom of the Press Foundation](https://freedom.press/ "A non-profit defending an open press."). Before that, I was the Director of Copyright Activism at the [Electronic Frontier Foundation](https://www.eff.org/ "A non-profit fighting for digital civil liberties."). I also an a 2017 alum of [the Recurse Center](https://www.recurse.com/ "A programming retreat in New York City."), which is a wonderful programming community that helped me learn a lot of what I do and continues to be a source of inspiration.

I tweet too often at [@xor](https://twitter.com/xor "Parker's Twitter account.") and blog too seldom at [my own site](https://parkerhiggins.net/ "Parker's website."). I'm also a big fan of the microblogging software Mastodon, and I'm on the fediverse at [@xor@mastodon.xyz](https://mastodon.xyz/@xor "Parker's Mastodon account.").

When I'm not on the clock, I try to work on projects that reflect my thinking about big ideas like transparency, creativity, access to knowledge, and free culture. That sounds kind of lofty, but a lot of times the projects are pretty small. For the last few years, they've frequently manifested as Twitter bots.

A few years ago I found out that the US Department of Agriculture had a collection of thousands of watercolor paintings of fruits and nuts, which were beautiful --- and digitized --- but not available online beyond thumbnails. So I sent a [Freedom of Information Act request for more info](https://www.muckrock.com/foi/united-states-of-america-10/pomological-library-costs-and-revenues-16335/ "Parker's Freedom of Information Act request regarding the Department of Agriculture's watercolour paintings."), [wrote about the whole thing](https://parkerhiggins.net/2015/04/us-government-release-7584-fruit-pictures/ "Parker's post about his request for info on the Department of Agriculture's watercolour paintings."), and ultimately got the images released. I basically learned to program in order to [upload them all to Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:USDA_Pomological_Watercolors) and, eventually, [run a Twitter bot (@pomological)](https://twitter.com/pomological "Parker's Twitter bot showing the Department of Agriculture watercolour paintings.") that posts an image at random every three hours.

Another example is a site I run called [FOIA The Dead](https://foiathedead.org/ "Parker's project that requests FBI files on people recently listed in the New York Times obituary section."), which started as a personal project but is now [an official Freedom of the Press Foundation project](https://freedom.press/news/foia-dead-transparency-site-public-figures-are-dying-get/ "Parker's post about FOIA The Dead."). That one scrapes the New York Times obituary section each day and sends an automated request to the FBI for any files it has on the subjects of those obits. (There's a privacy exemption to the Freedom of Information Act that applies to living people, so those files would not have been available before that day.) Most of the time the FBI says it doesn't have anything, but through the power of automation I have gotten dozens of files making up thousands of pages. The most exciting part has been connecting with family members of people who didn't realize their parents or grandparents had come under FBI surveillance. I can't talk about all of those cases, but I was interviewed on [the WNYC show Note To Self about one of them](https://www.wnycstudios.org/story/foia-fbi-file/ "An interview with Parker on WYNC about his FOIA The Dead site.").

Beyond that, there's the emoji trainscape bot [@choochoobot](https://twitter.com/choochoobot "Parker's Twitter bot that shows emoji-based train landscapes."), some [archiving work](https://www.nytimes.com/2018/02/01/business/media/gawker-archives-press-freedom.html "A New York Times article about Parker's work preserving the contents of Gawker.") that I do on the job, and weird little things like [spelling out words with three-letter airport codes](https://www.atlasobscura.com/articles/how-many-words-can-you-make-with-airport-codes "An Atlas Obscura article about Parker's airport code word project.").

### What hardware do you use?

I do almost everything on a [ThinkPad T460s][thinkpad-t460s] that I specced out as far as I could afford to about two years ago. It's a really sturdy and reliable machine, and I intend to stick with it as long as I possibly can. Most of my work is not very computation-heavy, but I have felt the constraints of the machine when [dabbling with machine-learning stuff](https://twitter.com/xor/status/923685654973812736 "Parker's tweet about training a neural network on New York City dog names."), for example.

I'm a relatively late convert to the iPhone, but eventually the camera got good enough, and [Android][]'s claim to free software purity got bad enough, that I made the leap. I was happiest with an [SE][iphone-se], but it eventually slowed down to the point that I had to make the upgrade to an [iPhone 8][iphone-8]. I'd like to think about my phone as little as possible.

When I'm shooting pictures I use an Olympus [OM-D E-M10][om-d-e-m1-mark-ii], mostly because it was [Wirecutter's pick as a midrange mirrorless](https://thewirecutter.com/reviews/best-mirrorless-camera-under-1000/ "A Wirecutter article about mirrorless cameras."). But I've been really happy with the photos I've been able to get and have learned a lot about lenses and stuff.

All of my bots and my personal site and other projects live on a [DigitalOcean][] box out there in the cloud somewhere, with a little bit of [S3][] thrown in for good measure.

### And what software?

My desktop runs [Xubuntu][], which is of course a version of the popular [Ubuntu][] OS with the lightweight [Xfce][] desktop environment. For a long time I've been vaguely interested in "upgrading" to a more hardcore desktop situation, probably with a tiling window manager. Then again, at this point I mostly have open a browser with lots of tabs and a [tmux][] session with lots of tabs, so it just doesn't make that big a difference.

For editing text, I usually use the very basic [gedit][] program. When I'm writing code, [vim][]. I've written some prose in vim but I'm still not yet facile enough with it and it kind of gets in my way. I'd like to learn enough to switch over all the way.

My blog runs on [WordPress][], which is truly inspirational as a piece of software, as an organization, and as a community. It's more than I need, though, and now that [Github offers HTTPS for custom domains](https://blog.github.com/2018-05-01-github-pages-custom-domains-https/ "A GitHub weblog post about supporting HTTPS for custom domains."), I'm more likely than ever to switch over to a static site generator hosted there.

When I'm [writing code](https://github.com/thisisparker/ "Parker's GitHub account."), it's almost exclusively [Python][], with a little bit of [JavaScript][] thrown in. When I was writing [gotham-grabber][], I got really excited about the browser automation stuff that you can do with [Puppeteer][], so I had to do a little bit of [Node][node.js].

### What would be your dream setup?

Honestly I feel like I'm close! I'd maybe get a nicer keyboard and I could always get a new camera lens, but I personally feel like I'm past the point where hardware or software is holding me back. What I need is a library full of reference books so I can learn everything that's already available to me.

[android]: https://developers.google.com/android/?csw=1 "A mobile phone platform."
[digitalocean]: https://www.digitalocean.com/ "An SSD-based web hosting service."
[gedit]: https://wiki.gnome.org/Apps/Gedit "A text editor for GNOME."
[gotham-grabber]: https://github.com/freedomofpress/gotham-grabber "A set of archiving scripts for generating PDF files of particular websites."
[iphone-8]: https://en.wikipedia.org/wiki/IPhone_8 "A 4.7 inch smartphone."
[iphone-se]: https://en.wikipedia.org/wiki/IPhone_SE "A 4 inch smartphone."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[node.js]: https://nodejs.org/en "A Javascript application platform."
[om-d-e-m1-mark-ii]: https://explore.omsystem.com/us/en/e-m1-mark-ii.html "A 20 megapixel mirrorless camera."
[puppeteer]: https://github.com/puppeteer/puppeteer "A Node library for automating Chrome."
[python]: https://www.python.org/ "An interpreted scripting language."
[s3]: https://aws.amazon.com/s3/ "Cloud-based Internet storage magic."
[thinkpad-t460s]: https://www.lenovo.com/us/en/laptops/thinkpad/thinkpad-t-series/ThinkPad-T460s/p/22TP2TT460S "A 14 inch PC laptop."
[tmux]: https://sourceforge.net/projects/tmux.mirror/ "A terminal multiplexer, similar to screen."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[vim]: https://www.vim.org/ "A command-line text editor."
[wordpress]: https://wordpress.com/ "Weblog publishing software."
[xfce]: https://www.xfce.org/ "A lightweight UNIX-like desktop environment."
[xubuntu]: https://xubuntu.org/ "A lightweight version of the Ubuntu distribution."
