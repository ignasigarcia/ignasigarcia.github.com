---
layout: post
title:  "Trusted Reviews performance talk"
date:   2014-02-12 20:59:32
categories: performance
---

Here you will find the slides of a talk that my colleague [Marcin Wawrzyniak](https://github.com/mailopl) and myself did at [IPC Media](http://www.ipcmedia.com/) about performance for the site [Trusted Reviews](http://www.trustedreviews.com).

Here you have some stats before the changes:

* Load time <span class="code">14 seconds</span>
* User could interact with the site after <span class="code">6 seconds</span>

And after:

* Load time <span class="code">5 seconds</span>
* User could interact with the site after <span class="code">1 second</span>

Not only the loading time has improved, but the time the user has to wait to interact with the site has been dramatically trimmed down, making the site more responsive to the user.

The key points of these changes are:

* Load javascript asynchronously
* Trim down the amount of CSS lines
* Simplify the DOM

[Check the slides here](/files/slides/tr-perfopt/#1)
