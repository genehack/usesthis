---
title: Phil Hagelberg
summary: Hacker-errant (Heroku)
date: 2012-01-25
categories:
- developer
- linux
credits:
  name: Lem Malabuyo
  url: http://www.flickr.com/photos/malabooyah/5469920515/
---

### Who are you, and what do you do?

I'm [Phil Hagelberg](http://technomancy.us/colophon "Phil's colophon."). I'm currently employed by [Heroku][] improving the platform's support for the [Clojure][] programming language and building up the language's ecosystem in general.

### What hardware do you use?

I use a [ThinkPad X200s][thinkpad-x200], which is about as light a machine (1.1 kg) as you can get and still have a comfortable full-size keyboard. I prioritize mobility since I work from [coffee](http://zokacoffee.com/ "A coffee shop in Seattle that Phil works out of.") [shops](http://neptunecoffee.com/ "A coffee shop in Seattle that Phil works out of.") [around](http://trabantcoffee.com/ "A coffee shop in Seattle that Phil works out of.") [Seattle](http://www.milsteadandco.com/ "A coffee shop in Seattle that Phil works out of.") about every other day. My laptop has held up really well despite being over 2 years old. I was eying the new X220 series but just couldn't justify ditching this one. I would probably still be on my ThinkPad X60 from 2007, but my habit of [working outdoors during the summer](http://www.flickr.com/photos/technomancy/tags/remoteoffice "Phil's photos of his remote office.") makes the LED backlight a must. I do miss the excitement you used to get when buying a new machine; these days (post-SSD) new purchases are more often about adjusting to a new set of compromises than getting something objectively better.

I used to have a server at home that hosted my IRC client as well as SSH sessions for pair programming. Since joining Heroku I've moved to [an IRC bouncer][znc] hosted on Heroku. I don't pair as much as I used to, but I've started using pair.io, a service for spinning up ephemeral collaborative programming nodes. It's also hosted on Heroku. I used to feel like running your own home server was necessary as a nerd merit badge kind of thing, but now I'm just glad to be rid of the hassle as long as I can still control the software wherever it's being run.

### And what software?

I do as much as I can in [GNU Emacs][emacs] since it pains me to use monolithic software that can't be modified at runtime. Emacs is the closest you can get on a modern OS (except maybe for Smalltalk) to the dream of the fully-dynamic [Lisp Machines](http://en.wikipedia.org/wiki/Lisp_machine "A Wikipedia entry for Lisp Machines.") of the 80s - you can alter nearly any aspect at runtime without recompiling or even restarting. Also worth mentioning is that you use the same mechanisms in your extensions as the original authors use in writing it in the first place. It's hard to overstate the benefits of this setup. It's like the shift from punch cards to interactive operating systems. When the friction of tweaking your environment drops below a certain point, you can take advantage of [positive feedback loops](http://en.wikipedia.org/wiki/Cybernetics "The Wikipedia entry for Cybernetics.") and become more likely to experiment and improve things that wouldn't be worthwhile in a more conventional OS.

So apart from using Emacs for obvious stuff like [programming][swank-clojure], [version control][magit], [note taking][org-mode], [email][gnus], [shells][eshell], [IM][elim], and [IRC][erc], I also have put together interfaces for things like [presentations][epresent], [pastebinning][scpaste], and [database interaction][relax.el].

There are still a few things that aren't feasible to be implemented in Emacs Lisp yet, but [Conkeror][] lets me maintain the runtime-modifiable paradigm in the browser. It does this by being implemented in [JavaScript][] and providing a rich system of dotfiles, [REPL](http://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop "A Wikipedia entry for Read--eval--print loop."), and hooks.

For work I use Leiningen a lot. A lot of people get confused when working with Clojure because Clojure itself is just a library rather than an application, and they expect to interact directly with it. Leiningen is that application that you interact with directly. I won't say much more about it because it's pretty straightforward except to note that it has an interactive mode as well as a way to extend it using the same mechanism that was used to write it in the first place.

Outside the dynamic interactive one-big-process environments I'm a big fan of simple orthogonal tools that work well together, so I use [xbindkeys][] for all my launchers and [mpd][] for my tunes.

Emacs has spoiled me by allowing me to operate entirely from the keyboard with as few keystrokes as possible, so I've got a few hacks to make this possible outside Emacs. There's a unixy tool called [dmenu][] that allows you to pipe a list of choices in and presents the user with a list of options that dynamically narrows as you type. I built a [music picker](https://github.com/technomancy/dotfiles/blob/master/bin/music-choose "Phil's music picker script.") on top of this that lets me queue an album to play with only a handful of keystrokes as well as a tool for [connecting to wifi hotspots](https://github.com/technomancy/dotfiles/blob/master/bin/ery-net "Phil's script for connecting to wireless hotspots.") and one for [initiating Skype calls](https://github.com/technomancy/dotfiles/blob/master/bin/skyyy "Phil's script for starting Skype calls.") from the keyboard. The problem with dmenu is it only allows exact matches; there are no fuzzy matches or wildcards. So over the summer I [taught myself](http://technomancy.us/152 "Phil's post on his OCaml experience.") [OCaml][] and implemented a replacement called [Erythrina][] that has fuzzy matching.

In the bigger picture, I'm currently using [Debian][] Squeeze after having been on Ubuntu since its second release in 2005. Ubuntu's push towards Unity bothered me, but given how easy it is to replace the UI with something more helpful it was easy to ignore. On the other hand, the way they're increasingly pushing proprietary software is harder to ignore. Debian's installer is less polished, but I appreciate their conservative get-it-right-at-all-costs approach a lot more these days than when I was in college and had a lot of time to mess around with goofed-up packages. I've also just switched away from stock [GNOME][] to [XMonad][] since I just kept hearing how it's become the canonical implementation of tiling done right. Now I'm wishing I had switched sooner; it makes the classic paradigm just seem so cumbersome in comparison. It lets you re-use the existing GNOME infrastructure for things it's actually pretty good at like power management and network configuration.

### What would be your dream setup?

In terms of hardware, I think I've got it barring things like head-mounted displays, direct-neural interfaces, and infinite battery life. My main complaint is aspect ratio; I really miss the extra vertical space of the old 4:3 models, and I find the trend towards 16:9 depressing. I would like a fully-functional web browser inside Emacs, but the biggest pain point in the software I use now is definitely Skype. It's alleviated by the UI I mentioned above, but I would love to have an interoperable free software VoIP application with a UI in a dynamic, repl-accessible language. And while we're at it I'd like an office in a turret with a panoramic view.

*Hagelberg now keeps a [changelog of his latest setup](https://technomancy.us/gear "Hagelberg's setup changelog.").*

[clojure]: https://en.wikipedia.org/wiki/Clojure "A dynamic programming language using the Java Virtual Machine."
[conkeror]: http://conkeror.org/ "A keyboard-driven web browser."
[debian]: https://www.debian.org/ "A Linux distribution."
[dmenu]: https://tools.suckless.org/dmenu/ "A dynamic menu for X11."
[elim]: http://savannah.nongnu.org/projects/elim "An IM daemon for Emacs."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[epresent]: https://github.com/technomancy/epresent "A presentation system for Emacs."
[erc]: https://www.emacswiki.org/emacs/ERC "An IRC client for Emacs."
[erythrina]: https://github.com/technomancy/erythrina "A tool for allowing quick selection from a list of options."
[eshell]: http://www.gnu.org/software/emacs/manual/html_node/eshell/ "A shell for emacs."
[gnome]: https://www.gnome.org/ "A desktop system for *nix operating systems."
[gnus]: http://www.gnus.org/ "A mail and news reader for Emacs."
[heroku]: https://www.heroku.com/ "A service for running and deploying Ruby, Node.js, Clojure, Java, Python, and Scala apps."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[magit]: https://github.com/magit/magit "A git mode for Emacs."
[mpd]: http://mpd.wikia.com/wiki/Music_Player_Daemon_Wiki "A music playing server."
[ocaml]: http://caml.inria.fr/ocaml/index.en.html "An object-oriented version of the Caml programming language."
[org-mode]: https://orgmode.org/ "An Emacs mode for notes and to-do items."
[relax.el]: https://github.com/technomancy/relax.el "An Emacs interface for CouchDB."
[scpaste]: https://github.com/technomancy/scpaste "An Emacs interface for pasting text over SSH."
[swank-clojure]: https://github.com/technomancy/swank-clojure/ "A server for connecting SLIME to Clojure projects."
[thinkpad-x200]: http://shop.lenovo.com/us/notebooks/thinkpad/x-series/x200 "A 12.1 inch PC laptop."
[xbindkeys]: http://www.nongnu.org/xbindkeys/xbindkeys.html "A keyboard/mouse launcher tool for X11."
[xmonad]: https://xmonad.org/ "A tiling window manager for X11."
[znc]: https://wiki.znc.in/ZNC "An IRC bouncer."
