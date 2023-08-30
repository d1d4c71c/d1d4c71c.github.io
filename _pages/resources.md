---
permalink: /resources/
title: "resources"
---

This is a list of resources I've found useful or interesting.  If it gets too big
(which it probably will) I'll split it up into more pages, but this page should 
continue to exist as an index if that happens.  For now, though, it's just 
on one page.

# CTFs, wargames, vulnerable machines, and the like
These are all useful tools to get hands-on practice.

## Wargames, online challenges
These are online games. Some require sshing into a remote server, others provide VPN access, still others
are web-based entirely.  Some have levels organized into a group, others are "Jeopardy" style where
you pick challenges from categories.

* [Overthewire](https://overthewire.org) 
Old-school wargames site, with 13 multi-level wargames (12 currently on line), and 4 vulnerable VMs.  One of the wargames is 
very basic linux command line stuff (Bandit), one is web-app focused (Natas), the others are mostly some basic binary exploitation,
and cryptography challenges.  I think it's quite good, despite being pretty long in the tooth. A good place for beginners to start
(along with newer ones like PicoCTF below). No sign up required, free.

* [Microcorruption](https://microcorruption.com)
A really fun one - 25 levels of attacking the same "lock", with an inbrowser debugger. Goes from very simple to very advanced in 
a nice progression. The target is essentially an assembler dump of the firmware of a lock, written in MSP430 assembler, which is 
a basic, 16-bit microcontroller made by Texas Instruments. Sign up required, free.

* [PicoCTF](https://picoctf.org/)
A Jeopardy style CTF from [Carnegie Mellon University](https://cmu.edu/), expressly designed for students, age 13+. Covers
"General Skills", cryptography, web exploitation, reversing, binary exploitation, and forensics. Highly recommended for beginners.
Sign up required, free.

* [TryHackMe](https://tryhackme.com/) 
A beginner oriented set of training and labs. A great place to start if you really don't have any experience or background, 
but probably too simple for folks who have been in the industry a while. Sign up required. Some parts are free, other things
cost some money.

* [HackTheBox (EU)](https://hackthebox.eu) or [HackTheBox (US)](http://hackthebox.com)
Standalone machines to try to root with a great interface to track progress.  Lots and lots of machines, on a variety
of platforms (100s). They also have [HackTheBox Academy](https://academy.hackthebox.com/), a set of training paths
that are really quite good. Their pricing model is odd though - you have to spend credits to get access to a training, 
and then get some amount back if you complete it. You start with some free credits, but you can't get too far into
it without ponying up some dough to buy more credits or a subscription. I did the math one time and (at that time at least)
you would need approximately $500 to get through all the courses. 
The main HTB site with the vulnerable machines
is free to use to get a small number of "active" machines, but if you pay for VIP accces you get access to all of them
along with writeups and some other features. Sign up required for all of this.

## Vulnerable Machines/Images/Containers/Apps
These are standalone VMs and similar things that you can download and run. All of these are free unless 
noted otherwise, and don't require logins unless specified.

* [VulnHub](https://www.vulnhub.com/) 
A huge archive of user submitted VMs to attack, 708 of them in fact. The quality varies, but some are excellent. Includes
many of the standalone ones mentioned below, so you might want to search here first.

* [Damn Vulnerable Linux (DVL)](https://archiveos.org/dvl/)
A now discontinued Live-CD of an amazingly broken, misconfigured, and vulnerable Linux distro. It's no longer under 
development, nor does it have a website anymore, but you can still find the Live CD from [ArchiveOS](https://archiveos.org/), 
which I've linked to above.

* [Damn Vulnerable Web App (DVWA)](https://github.com/digininja/DVWA)
A PHP/MySQL web application that is, to quote the README "damn vulnerable". Helps you practice some of the most common
web vulnerabilities on one of the most common web stacks in use.

* [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)
A modern and very insecure wep application. Available in docker, or from source, and can be used easily for CTFs or training.

* [Metasploitable3](https://github.com/rapid7/metasploitable3)
The latest iteration of the "Metasploitable" VMs by [Rapid7](https://www.rapid7.com/), makers of the [Metasploit Framework](https://github.com/rapid7/metasploit-framework),
which is one of the premier penetration testing tools, and free as a community version (the paid one has some extra capabilities, of course).  There have 
also been Metasploitable2 and the original Metasploitable, which you can find on sites like VulnHub, above.


# Tools
* [Cyberchef](https://gchq.github.io/CyberChef/)
A "swiss army knife" for transforming data via a web interface, as in converting Base64 to some other encoding.  Has a TON
of features.  I use this regularly.

* [Zed Attack Proxy - ZAP](https://www.zaproxy.org/)
Capable, free, and open source intercepting web proxy. Often has excellent support for new protocols (like websockets) long
before commercial alternatives (like Burpsuite) have them.  Highly recommended.  While Burp has some nice features in the 
pro edition, and is considered an industry standard, it's not free, and can be complex to use.  ZAP is free and has an 
easier learning curve.

* [Ghidra](https://ghidra-sre.org/)
A suite of reversing tools, originally developed by the [National Security Agency, aka the NSA](https://code.nsa.gov/).  Some
people think this means it _has_ to have some sort of backdoor or something in it.  I don't think it does, but what do I know?
It's excellent reversing software though, and free and open source.  An alternative might be [Radare2](https://www.radare.org/n/), 
which some people love, but I find a little hard to use, sometimes.


