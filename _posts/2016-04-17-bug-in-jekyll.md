---
layout: post
title: "Something wrong with Jekyll, surprisingly"
description: ""
category: 
tags: []
---
{% include JB/setup %}
I don't know how it came, but seemingly there was a bug in JB/setup. It led to incorrect path of css files for the default theme "bootstrap-3", hence all the pages could not be displayed well.

Considering I've been all the way following the steps on the official [Jekyll QuickStart](http://jekyllbootstrap.com/usage/jekyll-quick-start.html), I'm really surprised that such an issue could be there.

I made [a quick fix](https://github.com/cedrusx/cedrusx.github.com/commit/92e28e416b74684ca21bd5a754d787fb46a05ac9). However I cannot tell if it be proper, since I don't know whether the issue was brought by Jekyll or the theme.