---
title: Charles Berret
summary: Communications Ph.D. student (Columbia)
date: 2016-12-06
categories:
- developer
- linux
- mac
- researcher
---

### Who are you, and what do you do?

Hi, I'm Charles Berret, a Ph.D. student in Communications at Columbia. My work involves a lot of writing, coding, and talking -- ideally in a feedback loop that yields something resembling scholarship. Last year, I published some fairly substantial research on the present state of [data and computational journalism education](https://journalism.columbia.edu/system/files/content/teaching_data_and_computational_journalism.pdf "Charles' research on computational journalism education (PDF).") as well as the use of [SecureDrop and PGP in newsrooms](https://www.gitbook.com/book/towcenter/guide-to-securedrop/details "Charles' guide to using SecureDrop and PGP."). This year, I'm a fellow at the [Brown Institute for Media Innovation](http://brown.columbia.edu/ "A school teaching digital journalistic storytelling."), a very wonderful place that was established a few years ago between Columbia and Stanford for the sake of exploring the intersection of emerging media and journalistic storytelling. Lately, for my dissertation, I've been doing a lot of archival work on cybernetics and crypto research between the 1940s and 1970s. Most of what I'm going to describe here is what I've been using to facilitate my dissertation research.

### What hardware do you use?

The computer I use most often for work is an old [ThinkPad T420][thinkpad-t420] that's running [Ubuntu][] with the [GNOME desktop][gnome] (the [Unity][unity.2] interface started to bug me after a while). The main allure of these old ThinkPads is the keyboard -- the action is absolutely dreamy. For the amount of text I push out in a day, the keyboard really makes a difference. Also, this generation of ThinkPads comes with a hardware kill switch for its radios in case I need to be either very dilligent with work or very careful with security.

At home and when I travel, I tend to use a [13" MacBook Pro][macbook-pro]. My major hangup with the hardware is the glossy screen, but I've found that placing a matte screen protector gives it the look of a PowerBook from a decade ago. I also stick a discrete rectangle of electrical tape over the webcam because our techno-political circumstances demand it.

### And what software?

For syncing between machines, I run [OwnCloud][] on a server (also Ubuntu) that lives under my couch at home. That takes care of my files, calendars, contacts, and RSS. I also run [MediaGoblin][] for music and movies. And I sync my enormous [Zotero][] library to that machine using WebDAV. In addition to this physical server, I also run a smaller virtual server where I keep my personal email account, a few websites, and whatever platforms I feel like experimenting with. The reason for having a second server is mainly economical: since my ISP filters mail server traffic to residential connections, the monthly price of running mail through a VPS is less than the cost to upgrade to a business connection. Go figure.

Since I end up working between Mac and Linux machines, I prefer to use cross-platform tools whenever possible. [Firefox][] and Zotero do the trick for browsing and citation management. I run [Privacy Badger][privacy-badger] to block trackers, but I don't use an ad blocker since publishers really do need the money. [Homebrew][] gets me lots of the command line utilities I need that don't already come with Mac. The [Jupyter Notebook][jupyter] handles 90 percent of the mixed code/prose work I do. 

For straight prose writing or coding, I've been using [Atom][] pretty much exclusively for about a year now. To make Atom more amenable to prose writing, the Typewriter package has been great. It just centers the text within comfy, page-like margins, but that makes a huge difference. Isotope is my go-to UI theme. But why do I use Atom and not some other basic text editor, whether desktop or command line? First off, I find [Sublime][sublime-text] a little clunky. And setting up Vim and Vundle to approximate a word processor was just too much of a pain. More importantly, Atom's built-in file browser pane is a big part of my workflow. I end up moving between a lot of different files each day -- notes, drafts, memos, presentations -- and it makes a lot of sense for them to be accessible without switching applications. 

Also, I write pretty much everything in [Markdown][] and use [Pandoc][] to convert to other formats. When fancier print formatting is required, that means converting to [LaTeX][], but most of the time I just dump my work from Markdown to PDF, HTML, DOC, etc. right from the command line. (Dennis Tenen and Grant Wythoff have written an excellent introduction to this general workflow called ["Sustainable Authorship Using Markdown and Pandoc."](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown "An article about writing without using proprietary software.").)

I also use a ton of shell scripts and cron jobs to automate parts of my digital life. Just one example: for files that I work on every day, like my dissertation, I have a script that makes fresh PDFs and sends backups to several other machines a few times each day. I consider this a more civilized alternative to the paranoid dissertation backup solutions of yesteryear, like keeping a hard copy at the bank or in your refrigerator.

For the sake of a screen break, I do a lot of freehand writing. My go-to pen for getting ideas down is a [Lamy swift][swift]. It's hefty, well balanced, writes gracefully, and has an incredibly satisfying click action. (I imagine that it feels a lot like a pistol, but I've never held a pistol.) For marginal notes, I actually prefer to use cheap PaperMate pens with gray ink because they leave a light, subtle mark that doesn't dominate the other text on the page. In my experience, serious pens tend to make a mess of a book, but it's not an option for me to spend time to read something if I'm going to leave it unmarked. So cheap pens do the trick -- and often serve as a readymade bookmark, to boot.

And when I visit archives, I use my [Nexus 6P][nexus-6p] phone to collect images and [CamScanner][camscanner-android] to de-skew them. I've been really happy with this setup -- mainly its convenience in comparison to a downward-facing DSLR on a tabletop tripod -- but I really, really wish CamScanner would support ownCloud syncing, and I haven't come across a suitable alternative. As it stands, I dump my archival images to [Dropbox][] and then promptly evacuate them to my own servers.

### What would be your dream setup?

I've been asked to close by describing my dream setup, but frankly there's not a lot of technology that I covet, at least in terms of my work life. A computer needn't be particularly powerful to be useful as a tool for writing, research, and the kind of coding I do. If I really need to crunch something, I send it to my home server. And as a purely practical matter, I try to use free/open-source software and formats just because I can be reasonably certain that these will still be supported in ten or twenty years. I'm done migrating my work out of proprietary platforms. There's also an argument to be made for the environmental responsibility of using low-spec computers, low-overhead software, and basic file formats. I know some academics who do all their writing using [Vim][] on laptops where they haven't even installed a desktop interface. I don't take it that far, but suffice to say I don't find myself dreaming about adding fancy new gear to my life. I guess I'd like to build out my modular synthesizer if I ever leave New York and have some extra space, but [Tsering](http://tseringlama.com/ "Tsering's website.") would have to give me permission.

Since you've made it this far, go ahead and find me online at [charlesberret.net](http://charlesberret.net/ "Charles' website."), [academia.edu](https://columbia.academia.edu/CharlesBerret "Charles' page on Academia."), or [the twitters](https://twitter.com/cberret "Charles' Twitter account."). Thanks!

[atom]: https://github.blog/2022-06-08-sunsetting-atom/ "A text editor based on web technology."
[camscanner-android]: http://web.archive.org/web/20230520062215/https://www.camscanner.com/ "A scanning app."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[gnome]: https://www.gnome.org/ "A desktop system for *nix operating systems."
[homebrew]: https://brew.sh/ "Command-line package manager for Mac OS X."
[jupyter]: https://jupyter.org/ "Web-based live document software."
[latex]: https://www.latex-project.org/ "Typesetting software."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[markdown]: https://daringfireball.net/projects/markdown/ "An email-like format for marking up text."
[mediagoblin]: http://web.archive.org/web/20221224074359/https://mediagoblin.org/ "Open source digital media web sharing."
[nexus-6p]: http://web.archive.org/web/20210415003459/https://store.google.com/ "A 5.7 inch Android smartphone."
[owncloud]: https://owncloud.com/ "Self-hosted syncing and sharing software."
[pandoc]: https://pandoc.org/ "A Markdown document converter."
[privacy-badger]: https://privacybadger.org "A browser extension for blocking trackers and ads."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[swift]: https://www.lamyusa.com/us_en/rollerball-pen-lamy-swift.html "A rollerball pen."
[thinkpad-t420]: http://web.archive.org/web/20210506094630/https://support.lenovo.com/us/en/solutions/pd015734 "A 14 inch PC laptop."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[unity.2]: http://web.archive.org/web/20170905064051/http://unity.ubuntu.com:80/projects/unity "A desktop and notebook environment."
[vim]: https://www.vim.org/ "A command-line text editor."
[zotero]: https://www.zotero.org/ "A research tool."
