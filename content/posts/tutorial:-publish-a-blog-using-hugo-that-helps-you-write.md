---
title: "Tutorial: publish a blog using Hugo that helps you write"
date: 2020-12-06T16:06:14-05:00
categories: ["Draft"]
draft: true
---

> Alternative title: how to make this blog in 2 hours and 99 cents. 

### Motivation
The most important thing about my writing pipeline is that it needs to really **help** me write, so:
* No online Wordpress or WYSIWYG editors
* No editing spartan text or Markdown files
* No coding after setup, even for publishing
* Just works from [Bear](https://bear.app/), which I already use and love
* Costs nothing (Okay, 99 cents)

This post will teach you how to put up a blog that satisfies this criteria.  You probably need some git experience / coding experience to set this up, but then you should never need to touch code again.

The pipeline we’re setting up goes: Write tagged notes in Bear → Markdown autopulled by bhugo → Autocompiled by Hugo and theme into HTML/CSS → Autopublished by local cron job onto Netlify

Disclaimer: *This may seem like I’m just stitching together many services together.  That’s because that’s exactly what I’m doing.  Works well though.*

