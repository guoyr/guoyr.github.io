---
layout: post
title: In Search of a Permanent Solution of Climbing the gee-ef-double-u (Part 1)
date: 2015-03-24 21:35:56
share: y
---

My biggest frustration with traveling C**** is the lack of a stable VPN.

while there are already many VPN solutions out there, one common problem is that it's a game of cat and mouse; those services will inevitably be shut down after the technocrats catch a whiff of their existence. As a user, you don't know when it's going to happen and you don't know how long it's going to take to find an alternative; it could be minutes or days. After reading on how the GFW works, my conclusion is that the only way to climb over the wall permanently is to write your own ladder, from the ground up, and pray nobody else finds out about it. Here's a document of my attempt(s)

Surprisingly, so far it's all going rather well.

My first attempt is to use a simple local SOCKS proxy, tunnel over SSH onto an AWS box.
