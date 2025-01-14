---
title: Darius Kazemi
summary: Internet artist (Tiny Subversions)
date: 2015-01-20
categories:
- artist
- developer
- linux
credits:
  name: Ian Linkletter
  url: https://www.flickr.com/photos/linkletter/15294541806/in/photostream/
---

### Who are you, and what do you do?

I'm [Darius Kazemi](http://tinysubversions.com/ "Darius' website."), aka [@tinysubversions](http://twitter.com/tinysubversions "Darius' Twitter account."). I make weird internet stuff; art on the internet, if you will.

### What hardware do you use?

I primarily work on a [Chromebook Pixel][chromebook-pixel]. It's a beautiful piece of hardware. Kind of this gunmetal slab that feels more substantial in my hands than a [MacBook Pro][macbook-pro], but roughly the same form factor as a 13" [MacBook Air][macbook-air]. It's got one of those super high density displays so the image is gorgeous, and a touch screen for those times when I'm just lazily scrolling my way through an article or something.

I also keep a running [Google Doc][google-docs] of every project idea that comes to mind -- as such, my [Nexus 5][nexus-5] is invaluable for jotting down notes on the fly.

Sometimes I do want to take notes on paper, so since January 2012 I have carried around a tiny [UMD MITH](http://mith.umd.edu/ "The Maryland Institute for Technology in the Humanities.") branded notebook and, recently, a super high-end Santander Bank promotional pen. Of course, I have to carry this stuff around, so I use a nondescript Nike backpack purchased at TJ Maxx / Home Goods. And none of this would be possible without [this belt](http://www.target.com/p/merona-men-s-belt-brown-with-silver-buckle/-/A-10218913 "Darius' belt."), which holds up my pants.

### And what software?

You might ask, "How does he get development work done on a Chromebook Pixel? Does he develop entirely in the cloud?" And my answer to that is: no, of course I don't develop in the cloud, because among other things I value things like a low latency command line and also owning my own shit.

[Chrome OS][chrome-os], especially on a powerful machine like the Pixel, is great for web browsing and web applications, but is not so hot for anything else. So I have an [Ubuntu Linux][ubuntu] command line installed on Chrome OS. It's really easy to do using [crouton][]. crouton even lets you run [X11][xfree86] and a window manager of your choice, but I [don't bother with that](https://github.com/dnschneid/crouton#i-dont-always-use-linux-but-when-i-do-i-use-cli "The crouton instructions for installing just command-line tools."). Since everything I develop is for the web, I use [Vim][] on the command line, and I run my development servers there too.

The end result is: my entire computing experience is a browser with multiple tabs. Some of those tabs are websites I'm looking at, some of those tabs are websites I'm developing, and some of those tabs are a Linux terminal session.

For making my stuff I use [Grunt][] as my task manager, and specifically I use [grunt-init][] to scaffold my projects. All I have to do if I want a basic Twitter bot that tweets "hi" once an hour is answer a few questions, and suddenly it's tweeting. You can find my scaffolding [for Twitter bots here][grunt-init-twitter-bot], and [for text generation sites here][grunt-init-textgen]. Tools like these, along with [Corpora][], my repository of lists of things, let me very rapidly create new projects. I've released [100+ projects of various sizes](http://tinysubversions.com/projects/ "Darius' projects.") in the last 18 months. Small projects [are kind of my thing](http://tinysubversions.com/2014/05/thoughts-on-small-projects/ "Darius' post on small projects.").

### What would be your dream setup?

This is a hard question. Obviously my dream setup would be like, "Think something and it becomes willed into existence." But that's not terribly down-to-earth.

Ideally I'd have some kind of mouse that isn't fundamentally awful; even more ideally I'd have an operating system and web browser where I could quickly navigate everything without having to move my hands off the keyboard. The browser being the hard part. Having written that though, I did just google and find [Vimium][], which applies Vim keyboard shortcuts to Chrome, so I'm excited to try that!

I'd also like a very, very quiet room with good natural light. I prefer silence while I work. I envy people who can listen to music while working, but it's not for me.

[chrome-os]: https://en.wikipedia.org/wiki/Chrome_OS "A Linux distribution for running web applications."
[chromebook-pixel]: https://www.google.com/intl/en-US/chrome/devices/google-chromebook-pixel/ "A PC laptop with a Retina display."
[corpora]: https://github.com/dariusk/corpora "A data corpus collection."
[crouton]: https://github.com/dnschneid/crouton "A set of scripts to generate a chroot in Chrome OS."
[google-docs]: https://en.wikipedia.org/wiki/Google_Docs "A web-based office suite."
[grunt-init-textgen]: https://github.com/dariusk/grunt-init-textgen "A grunt-init template for generating text."
[grunt-init-twitter-bot]: https://github.com/dariusk/grunt-init-twitter-bot "A grunt-init template for a Twitter bot."
[grunt-init]: https://gruntjs.com/project-scaffolding "A command-line tool for creating new projects."
[grunt]: https://gruntjs.com/ "A task runner."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[nexus-5]: http://www.google.com/nexus/5/ "An Android smartphone."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
[vim]: https://www.vim.org/ "A command-line text editor."
[vimium]: https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb "A Chrome extension that adds vim-like hotkeys."
[xfree86]: http://www.xfree86.org/ "An open-source window system."
