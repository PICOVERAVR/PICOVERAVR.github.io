---
layout: post
title: "How To Find Interesting Tech Content"
date: 2022-01-12
category: guides
tags: [web, links]
published: true
---
_Last updated on {{ page.date | date_to_string: "ordinal", "US" }}_
  
While working at `$JOB` this past summer, an older coworker asked me how I find fairly obscure tech content. The answer is that I bookmark several content aggregation websites and check them when I have free time, as well as a couple frequently-updating blogs.

## General information/Upstream
I titled this section "upstream" because content on these sites is sometimes picked up by larger "downstream" sites.
### [Hacker News](https://news.ycombinator.com/)
For me, Hacker News is where I find almost all of my interesting articles and is the source of most of my current bookmarks. It functions similarly to Reddit but is more or less dedicated to tech news and interesting projects or blog posts. Some might argue that the web UI looks a little dated, but on the other hand the entire website loads in _0.86 seconds_ on my desktop, while Reddit takes 15.2 seconds to load the entire site with an ad blocker. It also works great on mobile devices.
  
Sidenote: Any time AWS goes down, you hear about it here first. I recall waking up to "AWS is down" posts one morning last year and getting Apple News notifications about the same outage on my phone that afternoon.
### [Phoronix](https://www.phoronix.com/scan.php?page=home)
An absolute beast of a site in terms of Linux ecosystem coverage. I find this site especially useful since I run Linux as my primary OS and can get advanced notice of cool features to play with. The benchmarks they run are in-depth but I feel like most of the results can be summarized as follows:
 - Newer distros are faster, especially on new hardware
 - New versions of gcc and clang rarely produce significantly faster code or better compile times
 - Clear Linux is the fastest Linux distribution
## Hardware-focused
My favorite articles from these sites generally revolve around either computer architecture or electronics.
### [AnandTech](https://www.anandtech.com/)
This site has fantastic deep dives into new CPU and GPU architectures in between product reviews I don't read. The deep dives contain enough benchmarks and specifics to satisfy my curiosity but are high-level enough that I don't feel like I'm doing research for a class. Their live coverage of major chip events reads like a social media feed and is quite good.
### [Chips and Cheese](https://chipsandcheese.com/)
The CPU architecture deep dives these guys publish makes AnandTech look like LinusTechTips. I read their content because I aspire to one day match their level of knowledge in CPU microarchitecture. They also have a wonderfully detailed article describing how instruction sets [don't matter anymore](https://chipsandcheese.com/2021/07/13/arm-or-x86-isa-doesnt-matter/). If you're the kind of person that picks fights with undergraduate computer architecture professors, this site is a great resource.
### [Fabien Sanglard](https://fabiensanglard.net/)
Worth visiting for their article on [NVIDIA SM technology](https://fabiensanglard.net/cuda/index.html) alone, but has fantastic articles (and even entire books) on how old games were engineered. The only downside to this site is the rate at which new articles are posted.
### [The Old New Thing](https://devblogs.microsoft.com/oldnewthing/)
Lots of this site is dedicated to Windows internals I don't care about. The bits on the history of Windows, however, are great. From discussing [The Magical Excel 97 Far East Language Build Screwdriver™](https://devblogs.microsoft.com/oldnewthing/20191119-00/?p=103115) to how Windows runs on weird architectures, it's clear Raymond knows what he's talking about.
### [Hackaday](https://hackaday.com/)
Covers anything and everything related to hobbyist electronics, and is related to the [GitHub of hardware projects](https://hackaday.io/). They seem to be venturing into the world of car mods, which I enjoy in small doses.
  
I'll probably update this page with more links in the future, so maybe check back once in a while.

{% if page.next.url %}
<a href="{{ page.next.url }}">Next: {{ page.next.title }}</a>
{% endif %}
{% if page.prev.url %}
<a href="{{ page.previous.url }}">Previous: {{ page.previous.title }}</a>
{% endif %}
