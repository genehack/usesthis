---
title: Chris Randall
summary: Musician, co-founder of Audio Damage 
date: 2020-07-03
categories:
- designer
- developer
- linux 
- mac
- musician
- windows
---

### Who are you, and what do you do?

My name is [Chris Randall](https://twitter.com/Chris_Randall "Chris' Twitter account."). I was born in Honolulu, Hawaii in 1968, and raised in equal parts New York City and rural Oregon. I currently live with my wife of 25 years in Phoenix, Arizona. For the last two decades, I've been the co-owner of [Audio Damage](https://www.audiodamage.com/ "Chris' music software company.") , a music software company based in Boulder, Colorado. Before that, I was a little bit famous as the lead singer of [Sister Machine Gun](https://en.wikipedia.org/wiki/Sister_Machine_Gun "The Wikipedia entry for Sister Machine Gun."), an industrial rock band that started in New York City in 1989. TL;DR: I spent the 90s in a tour bus, and from 2002 to now, I've sat in front of a computer screen. 

At Audio Damage, my main role is product designer. This means that, once we've agreed on an idea for a product, I'm in charge of how it looks, and to a lesser extent how it works. In my free time, I am still a musician, although it is no longer my principle source of income. I release an EP or album of abstract electronic and/or ambient music a couple times a year.

My hobbies include mild adventure travel (the preferred nomenclature these days is "overlanding"), extreme desert botany, hating on [macOS][] Catalina, and making contemporary abstract art (both electronically and "analog" with paint and whatnot.) 

### What hardware do you use?

I'll start with my music gear, as that is the basis of my work life. I am principally a keyboard player, and my main instruments are a 1972 [Rhodes Mk I][rhodes-mk-i] and a Moog [One][one.6] synth. I have many other keyboard instruments, but they're mostly in storage; those two are the ones I play every day. The other main electronic instrument I use is the Akai [Force][]. My main MIDI controller is a full-sized [LinnStrument][]. I am a strong proponent of MPE, and the LinnStrument is my interface of choice. I've had one for several years now, and am very comfortable with its layout. In addition, I have fairly bad RSD from years of playing guitar slung too low on stage, and the LinnStrument causes almost no pain, as opposed to a normal keyboard, which I can only play for about 30 minutes a day maximum. 

I have many fretted instruments, but the four I use most frequently are a 1980 Fender American Jazz bass (I have replaced the neck on this, so it isn't really a 1980 any more), a 1954 Silvertone arch top guitar, a 1957 Harmony Stratotone, and a 2017 Fender American Jazzmaster. My main guitar amp is a 1967 Guild Thunder 1 Reverb, but it is on permaloan to a friend, and I generally use a Sansamp and modeling software for my guitar and bass tones. 

I use a Dante audio-over-IP system for my home studio, rather than a single audio interface. This is very complicated to set up, but once it is all working, it is extremely robust, and allows you to add and remove hardware and computers easily. My main monitor controller is a Focusrite [X2P][rednet-x2p], and I also have two Focusrite [AM2][rednet-am2] units that I can move anywhere a CAT6E cable can reach in my house to add outputs if I need them. I can also theoretically move the X2P anywhere and have inputs. However, I haven't tried this yet. The X2P and AM2s are powered over the Ethernet cable, so they don't even need a wall wart to move. I have Dante virtual drivers on all my computers, so they can hook in to the network via a simple ethernet cable. I also have a small USB -> Dante interface made by Audient that I can use with laptops or iPads or whatever if I need I/O for a small device.

The other Dante I/O I always have hooked up is a Yamaha [Tio1608-D][]. This is the stage box from a Yamaha live sound system, but it has fantastic mic pres, and since it is a Dante box, you can just plug it right in to your rig, no mixer required. This gives me another 16 XLR/TRS inputs and 8 XLR outputs. I use four ins and outs for my Otari MTR-20 half-inch four-track tape deck, and two more ins and outs for an Otari MTR-12 quarter inch tape deck. These are set up as sends in my DAW, so I can always just add a tape deck to the mix. I render every track I release to the MTR-12, and I use them both for tape looping experiments. Two more inputs of the 1608 are used by the Moog One, and the remaining eight inputs have a 50' ProCo 8-channel TRS snake in them, with a box I can move to wherever I need it for inputs. 

I will eventually replace the Yamaha box with a pair of Focusrite [A16R][rednet-a16r] or a Lynx Aurora or something along those lines, but this is a fairly expensive endeavor, so it will have to wait until I have the resources. I like the Yamaha box fine, and it serves my needs without complaint, but a higher-end AD/DA would provide many more options, and the remote software for the Yamaha is not great. 

Tape looping is one of my principle tools of creation, and aside from the two big Otari decks, I have (at last count) 36 other tape decks, in varying degrees of usefulness. I also have a Caliphone card recorder, and many idiophones (from kalimbas to xylophones). 

My monitors are Adam [A7X][].

All that crap aside, the vast majority of my day is spent on the computer. My main system is a bespoke PC that I have been continually upgrading for some years. As it is an i7, it is getting to be time to swap out the motherboard; I may switch to a Ryzen Threadripper, as these are known to be very fast at compiling, which is my main bottleneck. It has 64GB of DRAM and 2TB of NVMe drive.

 I also have a current generation [Mac Mini][mac-mini], which I use to build our Apple products (both macOS and [iOS][]). I do not use this for music at all. I do our Linux builds on a dedicated Dell laptop running [Ubuntu][] 18. And finally, I have seven iPads of various flavors. I use the big [iPad Pro][ipad-pro] for ambient music experiments (mostly for my Instagram feed), in addition to it being my main development unit. Although I just (literally today) got the new 11" iPad Pro, and I think this may be a better form factor for my music use-case. 

For audio I/O on the iPad, I use a SoundDevices [MixPre-10M][], but I am very unhappy with this. They made a bad judgement when creating the CoreAudio drivers, and as a result, one can not run it from a USB hub, and thus one can not use a MIDI interface with it. I'm sure it is very good for its main use case, but I can not recommend it if you plan on using it with a mobile device. I will replace it soon with something more appropriate. It's a shame, because it is a very good device otherwise. 

I use Campbell's brand tomato soup cans for tape loop tension. 

### And what software?

For making music on the computer, my main software is either [Bitwig Studio][bitwig-studio] or Ableton [Live][]. The two DAWs are fairly similar in operation, but each has its strengths. I generally use Bitwig if I'm going to be actually playing a lot, as it is MPE-aware. If I'm just going to be doing abstract experiments, or if I need to work very fast, I will use Ableton Live with Max/MSP. As far as plugins go, I have hundreds (thousands?) from years of NFR trades, but I usually only have installed Audio Damage (for obvious reasons), Valhalla DSP, Unfiltered Audio, Newfangled Audio, and [SoundToys][]. 

For music-making on the iPad, I use the AUM modular mixer host, with our plugins and Bram Bos' excellent Rozetta suite. 

For my workday, I use [Visual Studio 2017][visual-studio], and Audio Damage uses Raw Material [JUCE][] to build our products, so I am very familiar with the JUCE environment, and often use it to make experimental instruments and control that nobody will ever use but me. ([Here](https://www.youtube.com/watch?v=EoocQlvxz70 "Chris' YouTube video of his music UI.") is an example of a touchscreen grid and gesture sequencer I made for my own edification which is running on a small Intel NUC that is sending OSC to my main system to control Max patches in Live.) I also occasionally create visual and audio art in [openFrameworks][] and [TouchDesigner][]. 

On the Mac, I use [Xcode][], of course. And that's about it.

### What would be your dream setup?

At this point, I pretty much have my dream setup. I'm going to move to a much larger curved monitor pretty soon, probably when I upgrade my main PC, and I'd like to replace the Adam A7X with [A77X][] at some point, or maybe Barefoot if I have the money. In addition, I do plan to upgrade my audio I/O as I mentioned above. And I wouldn't kick a Waldorf [Quantum][quantum.2] out of bed. But overall, I pretty much have all the gear I need at this juncture, and I'm pretty happy with it. 

I think I would like to own a Hohner [Pianet T][pianet-t].

[a77x]: https://www.adam-audio.com/en/ax-series/a77x/ "Studio monitor speakers."
[a7x]: https://www.adam-audio.com/en/ax-series/a7x/ "Studio monitor speakers."
[bitwig-studio]: https://www.bitwig.com/en/bitwig-studio.html "Digital audio workstation software."
[force]: https://force.akaipro.com/ "A music production and DJ system."
[ios]: https://www.apple.com/ios/ios-10/ "A mobile operating system."
[ipad-pro]: https://en.wikipedia.org/wiki/IPad_Pro "An iOS tablet."
[juce]: https://juce.com/ "A C++ framework."
[linnstrument]: http://www.rogerlinndesign.com/linnstrument.html "A unique MIDI controller."
[live]: https://www.ableton.com/en/live/ "Musical creation software."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[mixpre-10m]: https://www.sounddevices.com/product/mixpre-10m/ "A USB audio interface."
[one.6]: https://www.moogmusic.com/products/moog-one "A synthesiser."
[openframeworks]: http://openframeworks.cc "A C++ library for creative projects."
[pianet-t]: https://en.wikipedia.org/wiki/Pianet#Pianet_T "A electro-mechanical piano."
[quantum.2]: https://waldorfmusic.com/en/quantum "A synthesiser."
[rednet-a16r]: http://web.archive.org/web/20190420082819/https://pro.focusrite.com/category/audiooverip/item/rednet-a16r "A Dante I/O audio interface."
[rednet-am2]: https://pro.focusrite.com/category/audiooverip/item/rednet-am2 "A Power Over Ethernet output device."
[rednet-x2p]: https://pro.focusrite.com/category/audiooverip/item/rednet-x2p "A Dante audio interface."
[rhodes-mk-i]: https://en.wikipedia.org/wiki/Rhodes_piano#Later_models "A music keyboard."
[soundtoys]: https://www.soundtoys.com/ "A collection of audio plugins."
[tio1608-d]: https://usa.yamaha.com/products/proaudio/interfaces/tio1608-d/index.html "A music I/O rack."
[touchdesigner]: https://derivative.ca/product "Visual development software."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
[visual-studio]: http://www.visualstudio.com "A Windows development environment."
[xcode]: https://en.wikipedia.org/wiki/Xcode "An IDE for Mac developers."
