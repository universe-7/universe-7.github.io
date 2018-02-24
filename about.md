---
layout: page
title: About
---

<p class="message">Pete was crowned Mr. WHS, the all-male beauty pageant of Whitney High School, despite his current unshaven and, quite frankly, sloppy appearance. During this time, he dated the Class President, who drove them to Prom in her father's Mazda Miata. Previously, he earned a one-day suspension for an incident involving a potato projectile device.</p>

Hi it's Pete. Technically, I'm a photographer. You may remember me from such publications as [**ENERGY: Cocktails to Get You Up**](https://www.itsnicethat.com/articles/pete-deevakul-energy-drink-cocktails) or the [Chicken Issue of Lucky Peach](https://www.goodreads.com/book/show/31305906-lucky-peach-issue-22) magazine (where the above bio is taken from). 

Here's a nice word: `avifauna`

You can reach me at email or phone. Or if you're feeling more adventurous, I'm connected to some pubs on [Scuttlebutt](https://staltz.com/an-off-grid-social-network.html)/[SSB](https://www.scuttlebutt.nz/). I have an instagram account but haven't been on it since Oct 2017. I was gonna hire someone to post on my behalf, but that would undermine my philosophy of reducing the number of tech monopolies in my life. Gotta eat your own cooking. 

## Why Universe 7?

Of the 12 Universe in the multiverse, Universe 7 is the most Earth-like of all. 

Here's a nice phrase: `身 勝 手 の 極 意` (migatte no gokui)


## migatte no gokui vs mugen no ai


## jekyll-ing

Here's what a code snippet would look like (and also a reminder to myself to start on this historical weather vis project that's been on my mind for too long)

```
library(rwunderground)
library(ggplot2)
library(tidyverse)

jfk <- set_location()
dec.2017 <- history_range(jfk, 
                          date_start = "20171201", 
                          date_end = "20171231",
                          limit = 10)
                          
str(dec.2017)   
```