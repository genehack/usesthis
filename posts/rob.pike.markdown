---
title: Rob Pike
summary: Software developer (Unix, Plan 9)
date: 2012-10-23
categories:
- developer
- linux
- mac
---

### Who are you, and what do you do?

I'm [Rob Pike](http://research.google.com/pubs/r.html "Rob's page at Google."). I had a long stint at Bell Labs in the Computing Research Science Center, the lab that brought you Unix and C well before I got there. I helped bring the mouse to Unix. Later, I helped make the Internet [multilingual](https://plus.google.com/101960720994009339267/posts/Rz1udTvtiMg "Rob's post on UTF-8."). I'm now at Google. I work on lots of things, mostly the things under the things you work on. Most recently I was co-creator of the [Go][] programming language. I've also written some books about computing.

### What hardware do you use?

A bunch of Macs at home, Macs and Linux at work, plus of course the Google compute clusters. When I was on [Plan 9][plan-9], everything was connected and uniform. Now everything isn't connected, just connected to the cloud, which isn't the same thing. And uniform? Far from it, except in mediocrity. This is 2012 and we're still stitching together little microcomputers with HTTPS and ssh and calling it revolutionary. I sorely miss the unified system view of the world we had at Bell Labs, and the way things are going that seems unlikely to come back any time soon.

That said, my two-year-old 11" [MacBook Air][macbook-air] is the only piece of computing hardware to make me happy since I can't remember when. For what it does, as opposed to what my dream setup would be, it's fast and light and smooth and comfortable.

### And what software?

I don't install a lot of extra stuff on those Macs, mostly to reduce maintenance. I like the freedom to wipe and reinstall without losing my world (see answer to question 2). However, two things always come along: The Go installation of course, and [Plan 9 from User space][plan-9-user-space], also known as plan9port, Russ Cox's port of the Plan 9 user experience (if not world view) to Unix.

As I've [said elsewhere](http://interviews.slashdot.org/story/04/10/18/1153211/rob-pike-responds "An interview with Rob on Slashdot."), the answer to "[emacs][] or [vi][]" is "neither". I mostly live inside [acme][], an editor-shell-IDE-oddball I wrote a while ago that has a different worldview and a very different user interface but that, when used well, is powerful and expressive. Russ recently created [a nice screencast showing it off](http://research.swtch.com/acme "A screencast of Acme by Russ Cox.").

### What would be your dream setup?

I want no local storage anywhere near me other than maybe caches. No disks, no state, my world entirely in the network. Storage needs to be backed up and maintained, which should be someone else's problem, one I'm happy to pay to have them solve. Also, storage on one machine means that machine is different from another machine. At Bell Labs we worked in the Unix Room, which had a bunch of machines we called "terminals". Latterly these were mostly PCs, but the key point is that we didn't use their disks for anything except caching. The terminal was a computer but we didn't compute on it; computing was done in the computer center. The terminal, even though it had a nice color screen and mouse and network and all that, was just a portal to the real computers in the back. When I left work and went home, I could pick up where I left off, pretty much. My dream setup would drop the "pretty much" qualification from that. 

A bit like phones: You have a phone just so you can access who/what is at the other end of the connection.

Twenty years ago, you expected a phone to be provided everywhere you went, and that phone worked the same everywhere. At a friend's house, or a restaurant, or a hotel, or a pay phone, you could pick up the receiver and make a call. You didn't carry a phone around with you; phones were part of the infrastructure. Computers, well, that was a different story. As laptops came in, people started carrying computers around with them everywhere. The reason was to have the state stored on the computer, not the computer itself. You carry around a computer so you can access its disk.

In summary, it used to be that phones worked without you having to carry them around, but computers only worked if you did carry one around with you. The solution to this inconsistency was to break the way phones worked rather than fix the way computers work.

My dream setup, then, is a computing world where I don't have to carry at least three computers - laptop, tablet, phone, not even counting cameras and iPod and other oddments - around with me in order to function in the modern world. The world should provide me my computing environment and maintain it for me and make it available everywhere. If this were done right, my life would become much simpler and so could yours.

I would allow the setup to force me to carry a computer screen around, as long as it rolled up and fit inside something the size of a pen and had touch input when unrolled. As long as it had no local storage.

[acme]: https://en.wikipedia.org/wiki/Acme_(text_editor) "A text editor and graphical shell for Plan 9."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[go]: https://golang.org/ "A compiled programming language."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[plan-9-user-space]: https://swtch.com/plan9port/ "A port of Plan 9 programs to *nix."
[plan-9]: https://en.wikipedia.org/wiki/Plan_9_from_Bell_Labs "A distributed operating system."
[vi]: https://en.wikipedia.org/wiki/Vi "A command-line text editor."
