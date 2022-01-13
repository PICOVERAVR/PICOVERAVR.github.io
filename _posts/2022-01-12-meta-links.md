---
layout: post
title: "How To Find Interesting Tech Content"
date: 2022-01-12
category: guides
tags: [web, links]
published: true
---
_Last updated on {{ page.date | date_to_string: "ordinal", "US" }}_
  
While working at `$JOB` this past summer, an older coworker asked me how I find fairly obscure tech content. The answer is that I bookmark several content aggregation websites and check them when I have free time (and when I don't), as well as a couple frequently-updating blogs.

## General information/Upstream
### [Hacker News](https://news.ycombinator.com/)
For me, Hacker News is where I find almost all of my interesting articles and is the source of most of my current bookmarks. It functions similarly to Reddit but is more or less dedicated to tech news and interesting projects or blog posts. Some might argue that the web UI looks a little dated, but on the other hand the entire website loads in _0.86 seconds_ on my desktop, while Reddit takes 15.2 seconds to load the entire site with an ad blocker. It also works great on mobile devices because of this simplicity.
### [Phoronix](https://www.phoronix.com/scan.php?page=home)
An absolute beast of a site in terms of Linux ecosystem coverage. I find this site especially useful since I run Linux as my primary OS.

## Hardware-focused
### [AnandTech](https://www.anandtech.com/)
This site has fantastic deep dives into new CPU and GPU architectures in between product reviews I don't read. The deep dives contain enough benchmarks and specifics to satisfy my curiosity but are high-level enough that I don't feel like I'm doing research for a class. Their live coverage of major chip events is also notable.
### [Hackaday](https://hackaday.com/)
### [Chips and Cheese](https://chipsandcheese.com/)
### [ACM Queue](https://queue.acm.org/)

## Software-focused
### [Fabien Sanglard](https://fabiensanglard.net/)
### [The Old New Thing](https://devblogs.microsoft.com/oldnewthing/)

{% if page.next.url %}
<a href="{{ page.next.url }}">Next: {{ page.next.title }}</a>
{% endif %}
{% if page.prev.url %}
<a href="{{ page.previous.url }}">Previous: {{ page.previous.title }}</a>
{% endif %}
