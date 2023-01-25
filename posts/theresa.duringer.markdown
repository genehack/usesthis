---
title: Theresa Duringer
summary: Game developer, designer (Temple Gates Games)
date: 2018-04-03
categories:
- designer
- developer
- game
- windows
---

### Who are you, and what do you do?

I'm a second gen game dev and designer at [Temple Gates Games](http://www.templegatesgames.com/ "A video game company in San Mateo."), where we bring our favorite boardgames to lots of digital platforms like tablets, VR, phones and PC. Twenty years ago I got my first paycheck from Electronic Arts and have been Leeroy Jenkinsing it on game dev pretty much ever since.

Even though my roots are triple-A from working on the Sims, Sim City, and Spore, I've been learning how to run a cosier studio making games with the friends I met a decade ago at Maxis' board game club. We started our boardgame quest bringing the tabletop deckbuilder Ascension to VR, and recently we've released Race for the Galaxy for mobile. 

Boardgames are UI beasts - I mean they're pretty much just UI - so as a UI designer/artist/engineer, this is right up my alley. While boardgames tend to be loaded with juicy artwork, there are a lot of gaps to fill when translating them to digital, so I spend a lot of time in [Photoshop][] making mockups, slicing them out and loading them into our UI editor, fine tuning the XML to make them pixel perfect, and hooking them up with game logic in [C++][c-plusplus]. 

### What hardware do you use?

[eBay][] has become my new best friend. Jumping from PC/console dev to mobile has opened my eyes to the obscene lack of standardization and ridiculously complex configurations of phones, chipsets, OSes, not to mention the rapid rollouts of new versions which has made a tangled mess of target spec hardware. Bringing games to multiple platforms means our studio is a bit of a fun house of [Vives][vive], [Rifts][rift], Gears on top of all the tablets and phones, but my most prized bit of hardware is the [Cintiq][] on my desk that lets me draw on screen like a dream. My [Cintiq Companion][cintiq-companion-2] fixes that cafe itch when I want to get out of the office and draw around people, but still have a beefy OS so I've got access to version control, project files, etc.

### And what software?

Programming-wise, we roll handmade where it makes sense, so we've built a custom C++ engine. This lets us specialize and invest in features that make sense for our niche: digital boardgames on alternative platforms. So for example, we have to get creative to stay performant on mobile when we're double drawing geometry for VR with tricks like aggressive conical culling rather than standard frustum culling. All of this is built using [Microsoft Visual Studio][visual-studio].

We also pull in libraries where it makes sense, so we use [Opus][], an awesome encoder for our voice data. Phones have their own native echo cancellation and noise reduction (makes sense right?), but for PCs we use the [Speex codec][speex]. Since our games are multiplayer, we run servers on [Azure][] and we use [MySQL][] for a database. For versioning we use [Subversion][], with the [TortoiseSVN client][tortoisesvn] and [Assembla][] as our host.

On top of our custom engine, our homemade tools include an effects editor, material UI editor, and 3D editor for manipulating those UI files in 3D space for use in VR. If you want to write your own, the MVP features I recommend from our UI editor are the ability to recursively nest UI files and 9-slicing to scale UI elements while maintaining edge art aspect ratios. For boardgames I use this constantly. 

Art-wise, it starts with references and checking out how other teams accomplish cool stuff. [GifCam][] is a great tool to capture effects in games, and I load these into [Keep][google-keep] with search tags for speedy browsing. Another great tool for effect reference is the Chrome extension [Frame by Frame][frame-by-frame-for-youtube] for stepping through [YouTube][] game footage to visually dissect complex effects. When it comes to making art, Photoshop and [Maya][] are my bread and butter. In Photoshop I use the [AlienSkin Blowup 3 plugin][blowup] for upscaling images. For fast browsing PSDs, [XnView][] is great, especially for scoring screenshots to be used for marketing. I have an itchy Save As finger for art, so eventually I might run some [WinDirStat][] to identify bloat and save space. Finally I use [OBS][obs-studio] to record gameplay footage for trailers and B-roll.

### What would be your dream setup?

My dream setup would include Valve Employee level access to every [Steam][] game in existence, because the more you play the more ideas you have swirling in your head to synthesize or rebel against or whatever else drives your design. 

And something equivalent for phones, a Mary Poppins bag where I can grab any device on the market, and not have to rely on a beta community to identify hardware specific bugs post soft launch. Someone else would have solved versioning for non-binary files like PSDs with a reasonable browsing interface.

And all of this available in a cat cafe where they don't judge me if I order decaf.

[assembla]: https://www.assembla.com/ "A code and task management service."
[azure]: https://azure.microsoft.com/en-us/ "A cloud computing platform."
[blowup]: https://www.alienskin.com/BlowUp/ "An image enlargement Photoshop plugin."
[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[cintiq-companion-2]: http://web.archive.org/web/20190513005631/https://www.wacom.com/en-us/products/pen-displays/cintiq-companion-2 "A drawing tablet."
[cintiq]: https://www.wacom.com/en/us/cintiq "A computer screen you can draw on."
[ebay]: https://www.ebay.com/ "An auction service."
[frame-by-frame-for-youtube]: http://web.archive.org/web/20201108141323/https://chrome.google.com/webstore/detail/frame-by-frame-for-youtub/elkadbdicdciddfkdpmaolomehalghio?hl=en-GB "A Chrome extension to view YouTube videos frame by frame."
[gifcam]: http://blog.bahraniapps.com/gifcam/ "Windows GIF screen capture software."
[google-keep]: https://en.wikipedia.org/wiki/Google_Keep "A note-taking service."
[maya]: http://web.archive.org/web/20221224070508/https://www.autodesk.com/products/maya/overview "3D animation software."
[mysql]: https://www.mysql.com/ "A relational database server."
[obs-studio]: https://obsproject.com/ "Video recording and streaming software."
[opus]: https://en.wikipedia.org/wiki/Opus_(audio_format) "An audio encoding format."
[photoshop]: https://www.adobe.com/products/photoshop.html "A bitmap image editor."
[rift]: https://en.wikipedia.org/wiki/Oculus_Rift "A virtual reality helmet."
[speex]: https://en.wikipedia.org/wiki/Speex "An audio compression format."
[steam]: https://store.steampowered.com/ "A digital game distribution service."
[subversion]: http://web.archive.org/web/20200706092702/http://subversion.tigris.org/ "A version control system."
[tortoisesvn]: https://tortoisesvn.net/ "A Subversion client for Windows."
[visual-studio]: http://www.visualstudio.com "A Windows development environment."
[vive]: http://www.htcvr.com/ "A SteamVR headset."
[windirstat]: https://windirstat.net/ "A Windows tool to visualise disk usage."
[xnview]: https://www.xnview.com/en/xnview/ "Media viewer/browser software."
[youtube]: https://www.youtube.com/ "A web site for watching 80's TV commercials and bad mashups."
