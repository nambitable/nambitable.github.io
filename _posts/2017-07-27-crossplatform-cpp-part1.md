---
layout: post
title: "Crossplatform GUI options - part 1"
date: 2017-07-27
categories: gui crossplatform
---

It has been a while. I had mostly forgotten about this blog thingie. I may start this back up. Let's dive right into it though. 

One of the things that's intrigued me recently is trying to find a true crossplatform development experience. Trying to keep things simple, I'll ignore any mobile platforms and limit myself to Mac, Windows and Linux.

### Web based yuckiness
One of the first things you run across is web based solutions. Most of them are not native solutions (they don't truly use the underlying OS features) and run whatever flavor of the month javascript it is on an embedded chromium browser. Take a look at the [Chromium Embedded Frameowork](https://bitbucket.org/chromiumembedded/cef) if you're terribly interested in going down that path.

You could use an easy to use and deploy solution someone has already built, like [Electron](https://electron.atom.io/). Wow, look at that list of applications built with Electron. People writing code meant for browsers to fool people into thinking they're using native applications. 
Sure, I'll concede it's dead simple to get started. I'll concede that some of the apps come out looking beautiful. Because people can make beautiful websites. But ultimately you end up with a bunch of similar looking apps that use nice gimicks to fake the user into thinking it's a native application with the same types of limitations. Haven't you ever noticed why clicking abutton on these 'applications' takes just a smidge longer than necessary, as if you're loading a webpage? I mean they are, and that's the point. They can hide behind transition animations all they want, but it's never snappy enough.

And here's a really sweet image showcasing the power of these web solutions:

![webyucky](http://excelonwebsolutions.com/img/cwaService_opt830.png)

Look at that beautiful consistency. But it's a god damn webpage. Now think if we could achieve the same thing with native applications? We can do it with games, why not applications?

## Other langauges?

I'm gonna dive quite a bit deeper into what options we have with other languages. And finally on what we can do with C++. Till next time. 

