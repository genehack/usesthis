---
title: Bhautik Joshi
summary: Research engineer (ILM)
date: 2012-06-06
categories:
- developer
- mac
- researcher
- windows
---

### Who are you, and what do you do?

I'm a research engineer working at [Industrial Light & Magic](http://www.ilm.com/ "A visual effects studio."), where I work on building proprietary tools for artists to use. In my spare time I'm a [photographer](http://www.flickr.com/photos/captin_nod/ "Bhautik's photos on Flickr."), and I'm [constantly experimenting](http://cow.mooh.org/projects/ "Bhautik's photography projects.") with computational photography techniques and [hacking together](http://blog.cow.mooh.org/2010/04/fisheye-tin-cam.html "Bhautik's home-made fisheye lens.") my [own lenses](http://cow.mooh.org/projects/tiltshift/ "Bhautik's home-made tilt-shift lens.") and [camera setups](http://blog.cow.mooh.org/2009/12/phone-o-scope-attaching-slr-lenses-to.html "Bhautik's post on attaching SLR lenses to his iPhone."). I'm soon going to be a new dad and I'm looking forward to [geeking out](http://vimeo.com/39035740 "Bhautik's video of a Tron stroller.") with my kid.

### What hardware do you use?

I like to be as minimal as possible, and reliability trumps speed. I haven't owned a laptop in a long time and I don't miss having one. At home, I have three primary machines:

A 2009 24-inch [iMac][]: 3GB memory, 1.5TB hard-drive and a nVidia GT130 graphics card. This is my primary workhorse, mostly because of the good-quality display. I regularly calibrate it with a [Spyder express][spyder4-express] - it's worth noting though that the glossy glass panel sometimes confuses it. It's getting dated but Apple's excellent support for older machines means that I foresee using it for a long time to come.

[D-Link DNS-323][dns-323] Network Attached Storage Enclosure with two 1.5TB hard-drives. I use this awesome little device for storage, but after [rooting](http://bernaerts.dyndns.org/linux/178-dns323-funplug "A guide to hacking the DNS-323.") it, it's my go-to Linux box for all my odd-job scripts; it's running cron jobs 24/7. At some point I'll move all of this functionality to an [EC2 server][ec2], but with [dyndns][] I can access it from anywhere anyway and there's something nice about having physical access to my own little server.

A 2007 [HP m9000 desktop PC][pavilion-elite-m9000] with a 0.5TB drive and 4GB of memory; updated to run [Windows 7][windows-7] and [Mandriva Linux][mandriva]. This is the box for everything else. I tend to run a lot of batch jobs on this machine, mostly running simulations or image processing (I've still got an interest from my previous life in Medical Imaging and soft-body sims). If I ever get the time, it's my preferred machine for playing FPS games.

My primary camera is a [Canon 7D][eos-7d]. The image quality is great, it works well in low-light and it's a great device to get my feet wet in [shooting video](http://vimeo.com/40164073 "Bhautik's video of the Bring Your Own Big Wheel race."). The two lenses I use the most are my [Canon EF S10-22mm][ef-s-10-22mm-f3.5-4.5-usm] (superb image quality) and the [EF S f1.8 50mm][ef-50mm-f1.8-ii] (the plastic fantastic). I also build a lot of my own tilt-shift and plastic lenses for when I want to go for a different look, and these work great in concert with the smaller APS-C sensor in the camera.

Outside of that, I've got an [iPhone 3g][iphone-3g] that's been downgraded to iOS 3, making it a fast and reliable little device. I use it a lot for remotely logging into my DNS-323, and a couple of basic apps for color grading make it a remarkably good camera as well.

### And what software?

On the iMac, I'm running [OS X 10.6][macos]. I use whatever the latest version of [Firefox][] is for web browsing (I've always liked its minimal approach and the wide range of plugins available). I don't need many bells-and-whistles for my document processing, so I use [Google Docs][google-docs] for that. Day-to-day, I use [Lightroom 4][lightroom] for processing images, and I'll pop out to [Photoshop][] if a picture needs detail work. I use [hugin][] quite a lot for photo stitching and for aligning stacks of images for experiments. For the heavy-duty computational photography, I'll prototype in [PIL][] and then re-implement in [C++][c-plusplus] if I need the speed.

I love to automate whatever I can. In the past few years I've become very fond of feature-rich-out-of-the-box [Python][], and I use it to perform all sorts of odd-jobs. I like to publish a photo a day, and a couple of years ago I found that manually publishing them to different services (Flickr, Picasa, Facebook, Tumblr etc) was time-consuming. I wrote a stack of tools to automatically publish the photos using the service API's in Python. These tools get invoked automatically by a cron job in the middle of the night on the DNS-323. Now, I can focus on taking the photos rather than uploading them. Also, the DNS-323 only draws a modest amount of power so I don't have to have an entire desktop computer turned on to run my cron jobs.

I've been using virtual machines for a long time; I use [VirtualBox][]. I do my hobbyist C++ development on a Mandriva image that sits out on the network drive; I'll boot it up and use it on whichever of the desktop machines isn't busy processing data or images. For coding, mostly because I'm familiar with them, I use the KDE set of tools ([kate][], [kwrite][], [konsole][] etc) for both Mandriva and for OS X.

On the iPhone, I've recently been making a lot of use of [Mill Colour][mill-colour-ios] and [Instagram][instagram-ios]. On the phone, I focus on colour and composition and use Mill Colour to give the images a basic colour grade to fix up the strange exposure metering the iPhone does. After that, I post the images on Instagram unmolested, as I find the prepackaged filters pretty cheesy.

### What would be your dream setup?

I tend to only want what I actually need, so as far as computers go, my dream would be to have less stuff. It's useful to have two desktop machines to alternate between when one is busy doing work (I value responsiveness) but if I could get away with just one desktop I would. The only exception here is the display - if I could possibly justify it, I'd love to get a high-color-depth display, like the [HP DreamColor LP2480zx][dreamcolor-lp2480zx].

As far as cameras go: it's cheesy, but I really love digital rangefinders with big sensors. The [Leica M9][m9] paired with the [35mm f2 Summicron][summicron-m-50mm-f2] is swoon-worthy and I'd get this setup in a heartbeat if money was no object.

[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[dns-323]: https://www.cnet.com/reviews/d-link-dns-323-2-bay-network-storage-enclosure-review/ "A network storage device."
[dreamcolor-lp2480zx]: http://web.archive.org/web/20201027200453/https://www.amazon.com/Sbuy-LP2480ZX-24IN-LCD-Monitor/dp/B001B0QMGE "A 24 inch 30-bit LCD monitor."
[dyndns]: https://account.dyn.com/ "A dynamic DNS service."
[ec2]: https://aws.amazon.com/ec2/ "A web service for virtualised processing."
[ef-50mm-f1.8-ii]: https://www.usa.canon.com/cusa/consumer/products/cameras/ef_lens_lineup/ef_50mm_f_1_8_ii "A standard and medium telephoto camera lens."
[ef-s-10-22mm-f3.5-4.5-usm]: http://web.archive.org/web/20151024005028/http://www.usa.canon.com:80/cusa/consumer/products/cameras/ef_lens_lineup/ef_s_10_22mm_f_3_5_4_5_usm "A zoom lens for SLR cameras."
[eos-7d]: http://web.archive.org/web/20151105102657/http://www.usa.canon.com/cusa/consumer/products/cameras/slr_cameras/eos_7d "An 18 megapixel digital SLR."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[google-docs]: https://en.wikipedia.org/wiki/Google_Docs "A web-based office suite."
[hugin]: https://hugin.sourceforge.net/ "Open-source panorama stitching software."
[imac]: https://www.apple.com/imac-24/ "An all-in-one computer."
[instagram-ios]: https://apps.apple.com/us/app/instagram/id389801252 "A photo taking/sharing app."
[iphone-3g]: https://en.wikipedia.org/wiki/IPhone_3G "A smartphone."
[kate]: https://kate-editor.org/ "A text editor for KDE."
[konsole]: https://konsole.kde.org/ "A terminal emulator for KDE."
[kwrite]: https://kate-editor.org/ "A simple text editor for KDE."
[lightroom]: https://www.adobe.com/products/photoshop-lightroom.html "Photo management and editing software."
[m9]: https://en.wikipedia.org/wiki/Leica_M9 "An 18.5 megapixel digital camera with a full-frame sensor."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[mandriva]: https://en.wikipedia.org/wiki/Mandriva_Linux "A Linux distribution."
[mill-colour-ios]: https://apps.apple.com/us/app/mill-colour/id318704758 "An image colour editor app."
[pavilion-elite-m9000]: http://web.archive.org/web/20210126212958/https://www.pcworld.com/article/137325/article.html "A desktop PC."
[photoshop]: https://www.adobe.com/products/photoshop.html "A bitmap image editor."
[pil]: http://web.archive.org/web/20220914071003/http://www.pythonware.com/products/pil/ "An image library for Python."
[python]: https://www.python.org/ "An interpreted scripting language."
[spyder4-express]: https://spyder.datacolor.com/portfolio-view/spyder4express/ "A colour calibration system."
[summicron-m-50mm-f2]: https://www.kenrockwell.com/leica/50mm-f2-m.htm "A 50mm camera lens."
[virtualbox]: https://www.virtualbox.org/ "Open-source virtualisation software."
[windows-7]: https://en.wikipedia.org/wiki/Windows_7 "An operating system."
