---
title: Tim Jacobs
summary: Inventor, hacker, engineer 
date: 2019-05-02
categories:
- engineer
- hacker
- inventor
- linux
- windows
---

### Who are you, and what do you do?

My name is Tim Alex Jacobs, also known as [mitxela](https://mitxela.com/ "Tim's website."), and I am an inventor, hardware hacker, designer and all-round engineer. My work mostly involves embedded electronics and bare-metal software, but I often venture into high-level languages, graphic design, and front-end development. Many of my projects are documented on my website, [mitxela.com](https://mitxela.com/). 

### What hardware do you use?

I am a big fan of the HP EliteBooks from 2013 -- I own several of them. These things are built like tanks. The only part that ever breaks is the hard drive, and these days you can just swap that out with an SSD. I've dropped them on concrete and gotten them soaking wet, and they always come back to life. They're also amazingly powerful for what they are, I think they were designed at the peak of Moore's law. Modern laptops may have better battery life and weigh less, but in terms of raw processing power the old EliteBooks can't be beat.

I own probably half a dozen MIDI keyboards and my favourite is still the [Yamaha KX-5][kx-5]. I have two, one of which [I've extensively modified](https://mitxela.com/projects/midi_interceptor "Tim's post about his enhanced KX-5."). Most recently, I bought an [Arturia KeyStep][keystep] since I wanted a really portable keyboard with full-size MIDI connectors. Its miniature keys have aftertouch, but the keybed isn't quite as nice as I was hoping for. I also wish it had a few more knobs for sending MIDI data, but I haven't fully explored its MIDI functions just yet. 

Cameras are a really important part of what I do, and my workhorse is still the [Nikon D7100][d7100]. I only upgraded from my beloved ten-year-old [Nikon D80][d80] after the shutter mechanism jammed. I use the D7100 for video too, with my [Zoom H2n][h2n] connected to it. I find the easiest solution for video audio is to just use the H2n as a powered microphone, with its aux output connected to the camera's microphone input at a fixed gain level. This way you have reasonably good audio quality without the hassle of syncing everything up in post. For checking audio I have my [AKG K702 Headphones][k702] which are driven with a custom-built amplifier.

My favourite lens is the [Nikon 60mm f/2.8 AF-D Macro][af-micro-nikkor-60mm-f2.8d]. It really is invaluable for taking detailed pictures of electronics, and amazingly it has zero distortion. Even if you take a top-down picture of a breadboard, all the rows of pins are dead straight, down to the pixel. Away from the workbench I have a selection of prime lenses and also the Tokina 11-14mm Ultrawide. I love how crazy you can make the proportions and perspective with it. And when that's not wide enough, I also have the stereographic Samyang 8mm fisheye. I always find it hard not to laugh at the results you can get with it.

Possibly the most important bit of photographic kit I own is a metered flash. I have a few Chinese-made flash units that aren't expensive but make such a difference. Indoors, you just point it at the ceiling and let the camera's electronics work out what the exposure should be. And every time, you get perfectly diffused light around your subject. I do own a set of "proper" photographic lights, but it's a faff to set up and I'd never dream of lugging that stuff with me for anything away from home.

Other hardware that I depend on includes my metal lathe, which is imported and branded by Amadeal, and my laser cutter, which is a [modified K40](https://mitxela.com/projects/laser_cutter "Tim's post about hacking the k40 laser cutter."). I have a cheap 3D printer, but I hardly ever use it. My electronics workbench includes a Hameg HM604 oscilloscope. While it'd be nice to have a modern digital storage scope too, nothing beats the responsiveness of an analogue CRT scope. Recently, the [TS100][] has become my main soldering iron. I like how portable it is, and how fast it heats up, and how cheap it is, and that it's possible to install custom firmware on it. I'll be sure to do that as soon as I can think of a useful application.

And the final bit of hardware I should mention is the [AmScope SE400][se400-z] stereo microscope. This isn't a particularly exotic microscope, but what makes it so useful is that there's a whole nine inches between the objective and the focal plane. So for model-making and microsoldering it's worth its weight in gold. I cannot fathom how I managed to cope without it.

### And what software?

I use Windows more often than I care to admit, there are some things which I can only do with it. I'm in the rather unfortunate position that a lot of work that I do depends on Windows-only software that interacts with hardware, and because of the timing-critical USB access a lot of it misbehaves if I try and run it in a virtual machine. Within Windows, [Notepad++][notepad-plusplus] is invaluable, and until recently [MinGW][] was essential. A few months ago I started using [WSL][windows-subsystem-for-linux], and after ironing out a few problems and getting to grips with the quirks I think I do have to concede that it's better than MinGW or [Cygwin][]. 

My main laptop is running [Arch Linux][arch-linux], a distro I chose primarily because of their excellent wiki. It's a constant learning experience. If you are used to [Debian][] or [Ubuntu][] it often seems like everything is harder with Arch -- try to fix one thing and you find something else that's broken, try to fix that and before you know it the machine won't boot -- but the payoff is quite satisfying when you get everything just right, and you've learnt a lot more about how Linux works.

I use [i3][], which is a popular tiling window manager that's very easy to customize. [Vim][] (or [neovim][]) has a steep learning curve but is totally worth it, and being able to edit things just as efficiently on a headless machine is the main benefit for me. I use [git][] for everything, even things which aren't source code, such as CAD designs and circuit boards.

For electronic design work [EAGLE][] was my main program for ages (pretty much until they got bought by Autodesk), but now I've finally made the transition to [KiCad][]. The one area where KiCad lets me down is when it comes to curvy traces on PCBs, but hopefully that feature will be added soon. I don't know whether it makes a difference to the electrical characteristics at all, but curvy traces and teardrops do have the aesthetic advantage.

I can heartily endorse [OpenSCAD][], which is a very unique 3D modelling program. It is extremely lightweight and has the unusual quirk that, assuming you're comfortable typing instead of clicking, you can learn everything there is to know about it in an afternoon. It's extremely useful for quickly getting down a design while taking dimensions from a physical part. For more artistic stuff I have become a devout fan of [Blender][], which has become astonishingly good in the last few years. It does have a bit of a learning curve to it, you really need to know the keyboard shortcuts for everything to use it effectively, but once you've got that you realize it's a superb program. Just as a testament to it, I find the video sequence editor within Blender to be better than any standalone open-source video editor.

[Krita][] is a program I just started using. It isn't a replacement for Photoshop, but in some ways, particularly for digital art, it's _better_ than photoshop. 

[Sumatra][sumatra-pdf] is the best PDF reader. I feel so strongly about this that I use it on Linux under [Wine][]. 

### What would be your dream setup?

An enourmous workshop, with infinite storage space, and an infinitely long desk for leaving half-finished projects on. A big milling machine and lathe for rough work, a tiny watchmaker's lathe for precision stuff. A waterjet cutter and a press-brake. A metallurgical microscope. An AC TIG welder and an acetylene torch. A kiln. A forge. A supercomputer that can render and encode video in an instant. Oh, and a foosball table.

[keystep]: index.php?option=com_content&view=article&id=4&Itemid=1214 "A MIDI keyboard."

[af-micro-nikkor-60mm-f2.8d]: https://www.nikonusa.com/en/nikon-products/product-archive/camera-lenses/af-micro-nikkor-60mm-f%252f2.8d.html "A macro lens."
[arch-linux]: https://archlinux.org/ "A Linux distro."
[blender]: https://www.blender.org/ "A free, open-source 3D renderer."
[cygwin]: http://www.cygwin.com/ "A Linux-like environment for Windows."
[d7100]: https://en.wikipedia.org/wiki/Nikon_D7100 "A 24.1 megapixel DSLR."
[d80]: https://www.nikonusa.com/en/nikon-products/product/dslr-cameras/d80.html "A 10.2 megapixel digital SLR."
[debian]: https://www.debian.org/ "A Linux distribution."
[eagle]: http://web.archive.org/web/20221006162604/https://www.cadsoft.io/ "Software for designing printed circuit boards."
[git]: https://git-scm.com/ "A version control system."
[h2n]: https://en.wikipedia.org/wiki/Zoom_H2n_Handy_Recorder "A portable audio recorder."
[i3]: https://i3wm.org/ "An X window manager."
[k702]: http://web.archive.org/web/20190508113810/https://www.amazon.com/AKG-K702-Headphones/dp/B001RCD2DW "Headphones."
[keystep]: https://www.arturia.com/products/keystep/overview "A MIDI keyboard."
[kicad]: http://web.archive.org/web/20220324205847/https://kicad-pcb.org/ "Open-source CAD software."
[krita]: https://krita.org/ "An open-source image editor."
[kx-5]: https://en.wikipedia.org/wiki/Yamaha_KX-5 "A MIDI keyboard."
[mingw]: http://web.archive.org/web/20221229043715/http://www.mingw.org/wiki/MinGW "A compiler system for Windows based on GCC."
[neovim]: https://neovim.io/ "A refactored vim."
[notepad-plusplus]: https://notepad-plus-plus.org/ "A free text/code editor for Windows."
[openscad]: http://openscad.org/ "Open-source 3D CAD software."
[se400-z]: http://web.archive.org/web/20190506062734/https://www.amscope.com/stereo-microscopes/10x-20x-led-binocular-stereo-microscope-boom-arm-with-gooseneck-light.html "A stereo microscope."
[sumatra-pdf]: https://www.sumatrapdfreader.org/free-pdf-reader "A PDF reader for Windows."
[ts100]: https://www.getfpv.com/ts100-digital-oled-programmable-interface-mini-soldering-iron.html "A hackable soldering iron."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[vim]: https://www.vim.org/ "A command-line text editor."
[windows-subsystem-for-linux]: https://learn.microsoft.com/windows/wsl/about "A Linux environment for Windows."
[wine]: https://www.winehq.org/ "Software for running Windows software on other operating systems."
