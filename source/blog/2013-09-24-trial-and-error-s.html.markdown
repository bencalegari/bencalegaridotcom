---
title: Trial and Error(s)
date: 2013-09-24 02:18 UTC
tags:
---

##### An exercise in frustration.


Two weeks ago I decided I wanted to make a site with a blog.

That's it. But I got greedy. I started with middleman because that's the static site generator I was recommended. Foundation looked pretty cool too, but I couldn't figure out how to coerce it into my project, so I found a repo that combined the two in a nice template. So far so good. 

Now I had to actually start making the thing. The first sample page was in HAML and I wanted to write in Markdown, neither of which I hadused before. But it's supposed to be simple and easy. Theoretically.  

I wrote my first heading and started my server. All I had was this.

`bencalegari`<br>
`===========`  

I was confused. It was supposed to be a header. The logic in my brain did not match at all with the output on my screen, but computers only do what they are told, so I searched on for a solution.

Two hours and much googling later, I realized the obvious. It's a HAML file. It doesn't know what markdown is markdown without a :markdown filter. Of course. I had changed the syntax, restarted the server, refreshed the page, RTFMed and stack overflowed, but there is nothing that you can Google that tells you that you have no clue what's going on.

The site you see now is the 8th version I created. The biggest mistake I had made before was trying to go through the brick wall instead of simply going around it. I stripped unneeded complexity out, instead adding the simplest thing that got me further along. Every file is there because I wanted it there. 

Tweaking and tinkering to get everything exactly right is part of the reason why I love coding. You can take the ideas in your head and chisel them out until you get exactly what you want. This site isn't perfect because I still have tons more to learn (looking at you Javascript) but that's part of the beauty. There's always something more to uncover in the marble if you're willing to find it. 



