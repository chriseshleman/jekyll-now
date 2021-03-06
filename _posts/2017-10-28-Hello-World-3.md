---
title: "Scrap metal reprocessing"
author: "Christopher Eshleman"
date: "Oct 28, 2017"
output: html_document
subtitle: Change of course
---
I'm backing up and trying a new project. 

Lots of talk about the loss of US manufacturing employment. Here in New York, we've noticed a dip in the amount of scrap metal being shipped from the region toward other states. I wanted to take a look. 

So a few weeks ago I talked to a local scrap metal recycler and he told me to take a look at domestic metal refabrication markets. 

Much of the the steel, copper and aluminum the greater New York area exports heads to Pennsylvania and Ohio. I pulled Quarterly Census of Employment and Wages data for those states over the past few years (April data only). I stuck to NAICS code 331: primary metal manufacturing. 

And, well, maybe there was a dip last year in relevant employment. Ohio on the left, then Pennsylvania on the right (each shows metal manufacturing employment for April 2013-2016): 

![Primary metal manufacturing, Ohio.]({{site.baseurl}}/images/Ohio.png)
![Primary metal manufacturing, Pennsylvania.]({{site.baseurl}}/images/Penn.png)

If you squint (I'm not using ggplot or anything fancy right now) it looks like last year's primary metal manufacturing employment is lower in 2016 ... see? (*Squints*). 

I'll take a closer look later.


-----------------------------
Later ... 

![Primary metal manufacturing.]({{site.baseurl}}/images/Primary metal OH PA.png)
