---
layout: page
title: VulnHub Game Challenge
subtitle: Gain Root, Earn Points
images:
  - image_path: /img/hacking1.jpg
---


<div class="photo-gallery">
  {% for image in page.images %}
  <li style="list-style-type:none">
    <center>
      <a href="{{image.link}}">
        <img src="{{ image.image_path }}" alt="{{ image.title }}">
      </a>
      {{image.title}}
    </center>
  </li>
  {% endfor %}
</div>


# Introduction

we launched a new weekly challenge game start in Fall 2018! This is a challenge game aims to improve your black/white boxes pen-testing skills! We aim to help you being more comfortable when you go to compete real CTF games through practicing!

## The Rule

The rule is simple, go to [vulnhub](https://www.vulnhub.com/) download a box you perfer, then gain Root access and find the flags in the box. There are different hints or rules might different in each box, just follow the author's instuctions !

## How to gain Points?

In order to earn points and get a prize in the end of the semester, you will need to send screenshots for finding the flags and gaining the Root access to ! **make sure you include your NAME in the SCREENSHOT**, After you done all this, send your screenshots to untccsi@gmail.com

Each box worth 100 points after you complete all the flags in it. Online Walkthrough are allowed, all is about learning and we know everyone needs a place to start! But if you did a box that does not have many detalis or walkthrough (aka hard), we will give you extra points! **Imagine yourself are doing a black box pen-testing**

Bonus Points: 
If you submit a report for what you find during your hacking, we will give you extra points! A good pen-tester not only know how to break stuffs, he/she also knows how to communicate well! 

**Points breakdown**
Completion a box : 100

Submit a report : 50

A hard box : 50
 
**Highest score person will receive a prize in the end of the semester!**

Some hints for set up the lab: 

**After you download a ova box, make sure you set your attcking machine(kali) and the victim machine(the box) in a same NATNetWork, which allows those machines see each other in a LAN!!!! Really Important!!**

## SCOREBOARD

**You can see your rank in [here](https://scoreboard.untcybersecurity.com/)** 


<div class="responsive-wrap">
  <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScz7PcUEUZQLt8OiHT0TluGy8vq3DiUyQV6uje2ge9GY_TK0Q/viewform?embedded=true" width="760" height="500" frameborder="0" scrolling="yes">Loading...</iframe>
</div>
