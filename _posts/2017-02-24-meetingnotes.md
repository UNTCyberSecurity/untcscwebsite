---
layout: post
title: Meeting Notes - Cloudbleed, SHA1, and Wireshark
image: /img/misc/Cloudbleed.png
tags: [meeting, SHA1, Cloudflare, WireShark]
---

Meeting time change, SHA1 collisions, CloudBleed, and WireShark demo!

# At todays meeting we discussed:

* Moving the meeting time ahead 30 minutes (3:30 - 4:30)
* Upcoming LAN Party
* CloudBleed
* SHA1's first collision
* WireShark demo

## Meeting Time Change

Since the beginning of this semester we have had a large increase in new members, which is awesome!
However the room we used to meet in was over crowded so now we are having to locate a larger one.
Moving the time up thirty minutes will allow us to book a larger room, if you have any concerns let us know.
If this new time does not work for you fear not, for from now on all meeting notes will be posted here on the site.
For now the time will still remain 3:00 to 4:00

Do not be afraid to come in late or leave early because of classes or prior engagements we're just happy to have anyone show up!

## Upcoming LAN Party

The weekend following spring break we are hoping to host a LAN party here at Discovery Park on the weekend along with IEE CS and the American Society of Mechanical Engineers clubs.

To make this event as open as possible to our members we are going to be using one of the computer labs here, so no one needs to haul their computer up.
However this does leave us in the odd position of finding games that you can run without needing to install. If you happen to know of any good ones send us an [email](mailto:untccsi@gmail.com) or send a private message to Jesse Culver or Zach Eisenhower in Slack!

## CloudBleed

>**Between 2016-09-22 - 2017-02-18 passwords, private messages, API keys, and other sensitive data were leaked by Cloudflare to random requesters. Data was cached by search engines, and may have been collected by random adversaries over the past few months.**
>
>Requests to sites with the HTML rewrite features enabled triggered a pointer math bug. Once the bug was triggered the response would include data from ANY other Cloudflare proxy customer that happened to be in memory at the time. Meaning a request for a page with one of those features could include data from Uber or one of the many other customers that didn't use those features. So the potential impact is every single one of the sites using Cloudflare's proxy services (including HTTP & HTTPS proxy).
[Source](https://github.com/pirate/sites-using-cloudflare/blob/master/README.md)

[Google Project Zero Report](https://bugs.chromium.org/p/project-zero/issues/detail?id=1139)

[CloudFlare's Response](https://blog.cloudflare.com/incident-report-on-memory-leak-caused-by-cloudflare-parser-bug/)

## SHA1's First Collision

>Today, more than 20 years after of SHA-1 was first introduced, we are announcing the first practical technique for generating a collision. This represents the culmination of two years of research that sprung from a collaboration between the CWI Institute in Amsterdam and Google. We’ve summarized how we went about generating a collision below. As a proof of the attack, we are releasing two PDFs that have identical SHA-1 hashes but different content.
>
>For the tech community, our findings emphasize the necessity of sunsetting SHA-1 usage. Google has advocated the deprecation of SHA-1 for many years, particularly when it comes to signing TLS certificates. As early as 2014, the Chrome team announced that they would gradually phase out using SHA-1. We hope our practical attack on SHA-1 will cement that the protocol should no longer be considered secure.

[Source: Google's Security Blog](https://security.googleblog.com/2017/02/announcing-first-sha1-collision.html)

>Put another way: I doubt the sky is falling for git as a source
control management tool. Do we want to migrate to another hash? Yes.
Is it "game over" for SHA1 like people want to say? Probably not.

[Linus Torvalds Response](http://marc.info/?l=git&m=148787047422954)

[Lifetimes of Cryptographic hash functions](http://valerieaurora.org/hash.html)

## Wireshark Demo

Michael Hinderman put on a demo for how to use Wireshark and setup a virtual network in Virtualbox.
You can find his presentation [here](https://drive.google.com/file/d/0B9A3Z9_HMQERNThqTmNHWkxGMEU/view?usp=sharing)

<script async class="speakerdeck-embed" data-id="0f3c6e582a104dbda7372b24fbf3d2ce" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>

Jesse Culver
