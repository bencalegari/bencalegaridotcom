---
title: Trial and Error(s)
date: 2013-09-24 02:18 UTC
tags:
---

Originally dated: Sept. 19th, 2013

Ugh.

In last weekends attempt to build a project, I tried to make the website you are currently reading. I've been through 2 seperate static site generators, multiple front-end frameworks, and 7 different iterations, with the one you see now being a shell of what I hoped to accomplish. 


Brutality. Ultimate brutality. I could not have been more frustrated at my dismal lack of anything remotely significant. But that is what happens when you take 8 or nine different frameworks you only have a small grasp of and duct tape them all together, ending with a ridiculous monstrosity that deviates entirely from my original purpose. 

I wanted a site. With a blog. 

That's it. But I got greedy. I started with middleman because that's the static site generator I was recommended. Foundation looked pretty cool too, but I couldn't figure out how to coerce it into my project, so I found a repo that combined the two in a nice template. So far so good. 

Now I had to actually start making the thing. The first sample page was in Markdown and HAML, which I had never used before. No matter, I R'd T F out of of the M and felt pretty good. Its supposed to be simple! It looks so easy! 

I wrote my first heading and started my server. All I had was this.

`bencalegari`<br>
`===========`  

I was confused. The logic in my brain did not match at all with the output on my screen. There was no way in my mind it wouldn't work. But I knew the problem was me. 

Those of you who know what you're doing should already realize the problem. It's a HAML file. It won't parse markdown without a :markdown filter. It took me two more hours to realize. After changing the syntax, restarting the server, refreshing the page, RTFMing and stack overflowing to the Nth degree, I finally stumbled clumsily over my own stupidity. 

I had another problem with font-awesome which took up the entire rest of my time, but my first roadblock illustrates my point. I was left with what you see here. Just a disgrace. 

The biggest mistake of all was trying to go through the brick wall instead of simply going around it. I could have made content, developed a layout using only HTML and CSS, or simply started over. I got in way over my head and refused to admit it before it was too late. It was time I'll never get back. 

I have learned something from all this. And if you are reading this blog on a finished site that I built myself without relying on five billion gems, plugins, templates, or addons, that should be all the proof you need. 

PS. This is not the end of this fight. I will have a real, true to form blog and site soon.  