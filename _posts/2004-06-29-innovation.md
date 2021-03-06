---
comments:  false
excerpt:   "... is more than endlessly cranking out new and improved gadgets."
image:
  feature: bars/pink.jpg
layout:    post
modified:  2016-02-21
tags:      [Web]
title:     innovation
---

I was reading an article in [Enterprise Architect](http://www.enterprise-architect.net) magazine and came across the following quote,

> "Software as a service has become viable because of the ability to deploy interoperable SOA built on web services..."

This is a common sentiment, which is, unfortunately, completely untrue.

[Don Box](http://www.gotdotnet.com/team/dbox/default.asp) was the first person I heard completely discredit this meme.
He gave a very elegant demonstration (in [emacs](http://www.gnu.org/software/emacs/emacs.html)) to show that web services
are nothing but [UNIX](http://www.opengroup.org/) ioctl() stream programming and are thus going on 40 years old:
"Open a connection, send some text, wait for some text in response, close the connection."

What is new is how technologists are thinking about how to design architectures using the
UNIX [ioctl()](http://www.opengroup.org/onlinepubs/007908799/xsh/ioctl.html) interface and that's a good thing.

Unfortunately, many people in our industry always seek to emphasize a highlight the "new toys."

Innovation is more than endlessly cranking out new and improved gadgets.
It also consists of trying to find the best use of the tools you currently have lying around the shop.
