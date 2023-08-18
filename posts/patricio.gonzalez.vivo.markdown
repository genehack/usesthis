---
title: Patricio Gonzalez Vivo
summary: Artist, graphical engineer (Mapzen)
date: 2016-11-17
categories:
- artist
- developer
- linux
- mac
---

### Who are you, and what do you do?

I'm [Patricio Gonzalez Vivo](https://twitter.com/patriciogv "Patricio's Twitter account."), an artist and graphical engineer working at [Mapzen][]. I make digital maps and landscapes. My creative process is led by curiosity and wonder.

At Mapzen I mostly work pushing the boundaries of what can be done with digital maps. Like [Line of Sight](http://patriciogonzalezvivo.github.io/LineOfSight "Patricio's satellite visualisation."), a visualization of satellites orbiting the world, and [RandomCity](http://patriciogonzalezvivo.github.io/RandomCity/ "Patricio's city visualisation.") a vibrant digital landscape inspired by Ryoji Ikeda installations.

As an artist I make poetic explorations like [Point Cloud City](http://patriciogonzalezvivo.com/2014/pointcloudcity/ "Patricio's Google map data simulation."), an emerging view of the public data hidden on the depths of Google's private databases, or interactive installations like [EfectoMariposa](http://patriciogonzalezvivo.com/2011/efectomariposa/ "Patricio's ecosystem simulation."), a realtime simulation of an ecosystem where people can experience the fragility of human interaction.

All these projects are made using code and some custom tools.

### What hardware do you use?

I find it crucial for my creative practice to be comfortable and have a sense of abundance during the process. For that, especially in the early stages of a project, I enjoy working with powerful gear (which is nice but usually expensive) together with inexpensive gear (so I can buy as much as I want).

Before any line of code, I usually sketch ideas using pen & paper. I really like China Markers and Bic pens. I have boxes of them! I carry a couple of each one around to have them at hand all times. You know, always ready! They are incredible allies: extremely versatile and expressive tools to think and imagine on paper. Also, they are a great distraction tool for when you have to wait.

<img src="/images/interviews/patricio.gonzalez.vivo/desk.jpg" width="500" height="281" alt="Patricio's desk." class="detail">

Once I start coding, I work on a powerful laptop (a [MacBook Pro][macbook-pro] Retina 15" with a NVIDIA GPU card) connected to a big screen. I usually use the Retina display screen for the code editor - typography works beautifully on it - while the other screen is to display whatever I'm working on. That way I can see the result right away. Shortening that distance between the code and how it looks on the screen is probably one of the most important things for me --- it keeps the rhythm and flow of the process going, so I can discover and explore naturally and organically.

Once something is working I pass it to disposable hardware. I use as many [Raspberry Pi][raspberry-pi] as I can get a hold of. Raspberry Pi are small and inexpensive ($5 ~ $35) computers that run a Linux distributions. For me they are my zen practice. Working on limited hardware forces me to be a better programmer. This is the part of the job that requires technical expertise and with time I can get really good at. If I can get something complex running smoothly on the Pi, it will run beautifully anywhere.

### And what software?

Well, for this eclectic way of working I have my own custom tools. I can also say that this way of working is made possible by the tools I work with. "We shape our tools and thereafter our tools shape us" (Marshall McLuhan) 

To pass ideas into moving images I work with GLSL shaders, which is by far the language I feel most comfortable with. I made [a little WebGL app](http://editor.thebookofshaders.com/ "Patricio's WebGL editor app.") that lets me sketch and prototype things quickly. The abstract and minimal API of the GLSL language is perfect to sketch animations and break out algorithms. There are no libraries, and no distractions.

Around this tool I'm writing [a book about shaders](http://thebookofshaders.com/ "Patricio's book about Fragment Shaders.") and developing a series of other tools to display and share these sketches.

I'm such a fan of shaders that I do most of my work with them, to the point I that barely use [Photoshop][]. I do my color correction in shaders, and for that I have a native application compatible with the GlslEditor that runs on Mac OS X, any Linux machine and of course the Raspberry Pi. It's called [glslViewer][] and you can use it directly from the console or with your favorite code editor. I really like [Sublime Text][sublime-text]; it's a joy to work with in any language, from [Python][] to [JavaScript][] or [C++][c-plusplus]. Also the Material Theme is a must for Sublime Text.

Once I have a clear understanding of what I want to do, I start composing maps using another custom tool I work on called [Tangram Play][tangram-play]. This tools helps you to edit the YAML scene files that [Tangram][] and [Tangram-ES][] use to create maps. I had also [the joy of working](https://www.youtube.com/watch?v=5AGx0_2xI6Y "A video of Patricio's WebGL map talk on YouTube.") on those two projects.

Sometimes maps need some special data to come alive, and for that I prefer parsing data with Python in Sublime Text. Ohhhhh the joy of Python in Sublime Text.

<img src="/images/interviews/patricio.gonzalez.vivo/space.jpg" width="500" height="281" alt="Patricio's ISS live stream." class="detail">

When I'm not working on the Raspberry Pi, I use it to display digital artwork or [a live video stream from the ISS](http://www.ustream.tv/channel/live-iss-stream/theater "A live stream from the International Space Station.") --- it helps me to keep an open mind :)

### What would be your dream setup?

I'm pretty happy with this setup, but I always wish I had more time for drawing and working outside.

[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[glslviewer]: https://github.com/patriciogonzalezvivo/glslViewer "A live GLSL code renderer."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[mapzen]: https://www.mapzen.com/ "An open mapping platform."
[photoshop]: https://www.adobe.com/products/photoshop.html "A bitmap image editor."
[python]: https://www.python.org/ "An interpreted scripting language."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[tangram-es]: https://github.com/tangrams/tangram-es "A C++ library for rendering maps with OpenGL ES."
[tangram-play]: http://web.archive.org/web/20180102202840/https://mapzen.com/tangram/play/ "A YAML editor for Tangram's map data."
[tangram]: https://github.com/tangrams/tangram "A JavaScript library for rendering maps with WebGL."
