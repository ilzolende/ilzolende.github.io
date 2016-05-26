---
layout: post
title: Jekyll Collections and Mesolexia
---
Site update: [Cure Mesolexia Now!](/mesolexia/)'s website has now been posted, as have some of my recordings of myself singing and reciting poetry. I'm probably going to post some recordings of prayers, but I think there's some restrictions on how it's appropriate to do that, and I figured I owe my religion at the very least the respect I give to Wikimedia Commons contributors' licenses.

Although I had initially posted the mesolexia website as a set of pages, this was a suboptimal solution. It forced me to generate navigation pages manually, instead of using Liquid to iterate through the full list of pages. I'm happy to report that I resolved this issue: [Jekyll Tips](http://jekyll.tips/) has introduced me to [Jekyll collections](http://jekyll.tips/guide/collections/).

I've also used collections for the recordings page. However, each recording collection item is just a bunch of metadata, and I don't give them their own pages.

It turns out that [Jekyll supports sorting things](http://jekyll.tips/jekyll-casts/photo-gallery/), which is nice.