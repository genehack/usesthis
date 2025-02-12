---
title: Eric Mill
summary: Web developer (18F)
date: 2014-08-28
categories:
- developer
- linux
- politics
---

### Who are you, and what do you do?

I'm [Eric Mill](https://konklone.com/ "Eric's website."). Basically I make things on the Internet for work and for fun.

On the work side: for most of the last 5 or so years, I worked at the [Sunlight Foundation](http://sunlightfoundation.com/ "The Sunlight Foundation's website."), building [apps](https://scout.sunlightfoundation.com/ "A website for alerts about government events.") and [infrastructure](http://theunitedstates.io "A website of shared tools and data related to the US government.") for a more open government. I recently left and joined [18F](https://18f.gsa.gov/ "The 18F website."), a small team inside the federal government that builds open apps and infrastructure on behalf of the government. (I'm speaking for myself here and not my employer, of course.)

And on the personal side: I put maybe an [irrational amount of energy](https://konklone.com/post/isitchristmas-dot-com-2013-more-and-better "Eric's post about his isitchristmas.com site.") into making [isitchristmas.com](https://isitchristmas.com/ "A site that tells you if it's Christmas or not.") a neat place once a year. I've tried to help out the post-Snowden Internet a bit by evangelizing [personal ownership](https://konklone.com/post/take-control-of-your-email-address "Eric's post about taking control of your email address.") and a web where encryption is so [omnipresent](https://konklone.com/post/github-pages-now-supports-https-so-use-it "Eric's post about GitHub Pages adding support for HTTPS.") and [simple](https://konklone.com/post/switch-to-https-now-for-free "Eric's post about switching to HTTPS for free.") that it's just baked into the background. I [follow](https://konklone.com/post/following-the-fisa-court-new-website-new-data "Eric's post about following the FISA Court.") the work of the [Foreign Intelligence Surveillance Court](https://twitter.com/fisacourt "Eric's FISA Court Twitter account.") closely, and try to elevate the work of the US government's [oversight community](https://oversight.io/ "Eric's service for tracking Inspector General reports.").

### What hardware do you use?

For the last couple years, I've used a [Thinkpad W520][thinkpad-w520] laptop as my main companion. I get routinely mocked for how much of a tank this thing is. It is the farthest cry from a [MacBook Air][macbook-air]. I comfort myself with its 32GB of RAM, and the ability to run a hojillion things at once with impunity. 

The best symbol for the resilience of my Thinkpad is: I spilled water on it early on, and it completely disabled the trackpad and both mouse buttons. But that's okay, because the Thinkpad *has another set of mouse buttons and a [pointing stick](http://en.wikipedia.org/wiki/Pointing_stick "The Wikipedia entry for Pointing Stick.")*. This computer is prepared with full onboard mouse redundancy.
 
For a phone, I use a [Nexus 5][nexus-5]. Always Nexus. I have been the biggest [Android][] evangelist since months before Android launched - I pre-ordered a [T-Mobile G1][g1] on launch day, then went Nexus every 2 years since ([Nexus One][nexus-one], the [Galaxy Nexus][galaxy-nexus], and now the Nexus 5). In Android's earliest days, I maintained a list of the ~20 people I personally convinced to get a G1.

After years of almost exclusively shared hosting, I now host most of my work on [Amazon Web Services][aws]. It's fine: you can jam a lot of stuff on a single box, and if you reserve it for a year ahead of time it's not bad. 

But it's not the best situation, since Amazon is such a central point of failure and compromise now. I think there's a lot of lunch to be eaten from Amazon by competitors who offer a simple, secure experience and project a competitive, underdog image (and I've been messing with [DigitalOcean][], who I think is demonstrating this).

### And what software?

I'm an all-[Ubuntu][] kind of guy, at work and at home. I've been using Ubuntu all day every day since 2007, and I'm still in its corner.

I know a lot of people in the Linux and security/privacy community get down on Ubuntu now for Unity's long-time heft and instability, for abandoning Wayland, and generally [making disappointing corporate decisions](https://fixubuntu.com/ "A website for helping protect user privacy under Ubuntu."). 

But I am a simple man: I just need a friendly graphical environment and virtual workspaces, and Unity has gotten stable enough to stay out of my way. I've tried GNOME 3 and Cinnamon and found them unstable and unpleasant, and I've had friends evangelize minimalist environments I found spartan and alienating. 

And I think Canonical has learned a couple lessons about the extent of their might - they finally [made Amazon integration opt-in](http://www.omgubuntu.co.uk/2014/03/ubuntu-make-amazon-product-results-opt-unity "An article about Canonical making Amazon product results opt-in for Unity Dash."), and they [left their own system process manager behind](http://thevarguy.com/ubuntu/021814/canonical-gives-upstart-systemd-ubuntu-linux "An article about Canonical ditching Upstart.") to align with the [Debian][] community's decision. I'm hopeful that as they evolve to stay relevant in an increasingly mobile-and tablet-dominated industry, they'll keep their feet firmly rooted in the FOSS community.

My Thinkpad does keep a Windows partition around for the occasional Win- or Mac-only game, but [Steam's][steam] [surge of Linux support](http://store.steampowered.com/browse/linux/ "A list of Linux games on Steam.") and [Humble Bundle's](https://www.humblebundle.com "The gaming store that donates to various charities.") years of insistence on Linux support has made Linux support so likely for new games that I could probably ditch this now.

For a text editor, I use [Sublime Text 3][sublime-text], which is the only piece of software I've paid for on my laptop. I've never been able to stand [vim][], [emacs][], or anything that forces me into the terminal for open-ended, creative pursuits like actual coding. (Before Sublime, I used to use [Kate][].) All I really need to get things done is a fast graphical tabbed editor, syntax highlighting, and find+replace with regular expression support.

### What would be your dream setup?

I'm not a subscriber to the idea that tablets are replacing laptops. People still need to make things and get work done. 

The perfect laptop:

* is 100% FOSS, but without any rough edges. (This doesn't exist.)
* is supported by the manufacturer despite an OS not from Google, Apple, or Microsoft. (Dell recently started [doing this](http://www.dell.com/ubuntu "Dell's list of their laptops with Ubuntu pre-installed.") again.)
* ships with its full disk already encrypted, with a password you reset on first boot.
* comes with an open source USB or smartcard device designed solely for private key storage, with lots of great instructions and advice. (Can't think of anything good that exists like this.)

It would also have a document explaining (in plain language) what global institutions the laptop has been preset to blindly trust. In other words, which [certificate authorities](http://en.wikipedia.org/wiki/Certificate_authority "The Wikipedia entry for Certificate Authorities.") are trusted. That document would also explain how to disable certain institutions, in general or on a prompted basis.

The perfect phone:

* is 100% FOSS, right down to the hardware and firmware level for every bit of it. (This doesn't exist.)
* can be easily rooted, and its bootloader easily unlocked and re-locked, and a warranty that can withstand that. (The [OnePlus One][one.2] purportedly does this.)
* ships with its full disk already encrypted, with a password you reset on first boot. The disk password should be totally separate from the screen unlock password.
* uses Android's permission structure, but allows users to rescind any individual permission they wish.

It would also use a standard find-my-phone/kill-switch spec, that you can authorize (or revoke) the provider of your choice to control on your behalf. That's a useful feature that shouldn't require an irrevocable tether to a major point of failure or compromise like Google or Apple.

The perfect host:

* focuses on the latest Ubuntu server LTS. 
* has special support for managing one's own website, or email server.
* is so standards- and container-oriented that anything you create could easily be snapshotted, downloaded, and migrated seamlessly onto a Raspberry Pi.

It would also have documentation and an interface optimized for non-experts and single-use tasks. For example, a graphical UX to manage "the box's" crontab, and ways to point the box at, say, a [Dockerfile][docker] hosted on [GitHub][] and have it just go from there.

[android]: https://developers.google.com/android/?csw=1 "A mobile phone platform."
[aws]: https://aws.amazon.com/ "Amazon's web service platforms."
[debian]: https://www.debian.org/ "A Linux distribution."
[digitalocean]: https://www.digitalocean.com/ "An SSD-based web hosting service."
[docker]: https://www.docker.com/ "A service and software for building and shipping distributed software."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[g1]: https://en.wikipedia.org/wiki/HTC_Dream "An Android smartphone."
[galaxy-nexus]: http://www.google.com/nexus/ "An Android-based smartphone."
[github]: https://github.com/ "A Git code repository service."
[kate]: https://kate-editor.org/ "A text editor for KDE."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[nexus-5]: http://www.google.com/nexus/5/ "An Android smartphone."
[nexus-one]: https://en.wikipedia.org/wiki/Nexus_One "An Android-based smartphone."
[one.2]: https://oneplus.net/one/ "A 5.5 inch Android-based smartphone."
[steam]: https://store.steampowered.com/ "A digital game distribution service."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[thinkpad-w520]: https://www.amazon.com/Lenovo-ThinkPad-W520-427637U-Notebook/dp/B004U5Y9LC/ "A 15.6 inch PC laptop."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
[vim]: https://www.vim.org/ "A command-line text editor."
