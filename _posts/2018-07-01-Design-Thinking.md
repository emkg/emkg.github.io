---
layout: post
title:  "Getting Into Design Thinking"
date:   2018-07-01
categories: agile design product
---

{% include posts.css %}

I spent most of a year as a web developer dealing with my imposter syndrome. At this point, it is time to let it go and accept the fact that I know what I'm doing as a developer. In less than 8 months, I've shipped two big-deal web apps for weather scientists. Granted, these aren't large scale deployments, but they are useful and beloved solutions to problems that are now in the past. These apps are so useful that word of my ability to deliver tools that exceed expectations is spreading all over the building, and I'm getting more demand to build things. Of the lessons I learned from previous projects, probably the most important is that a little planning goes a long way.

In the midst of imposter syndrome, it's easy to feel like you're already in the deep end, so you don't see the danger in diving deeper to see if you've got what it takes to swim. You feel like you look weak if you suggest wading toward the shore to get your bearings. But that's what every project needs: a leader to hang back so the team doesn't get ahead of itself and get a good sense of what's truly needed and what's not. Ideally, a team works together to identify both of those things. I learned the hard way what it is like without that leadership action of not getting ahead of yourself. Pet features creep in, requirements that were "too obvious to mention" get brought to the developer's attention. And my favorite, a feature to discover "secret hidden data" is asked about at the very last minute. Some of these issues may sound silly, but I've been building apps for domain experts who are not used to talking to people who lack expertise in their domain. So, sometimes there is "secret hidden data" that they know to look for, but I sure don't.

So now all new projects I take on must go through an Agile process.

My first projects were all brought to me as immediate problems I needed to fix ("ahhh this old code is throwing 100 error messages per MINUTE help!") or as fantasy projects ("I don't know what I want but it's pretty much the same as this other thing just build that ok"). In the former case, it feels like it's too urgent to plan (you should still plan). In the latter case, it turns out the user isn't lying--they don't know what they want, but it's worse than that. They also don't know what they need. So now, I make sure I understand the task the user is trying to accomplish. I don't just ask questions, I have them describe the thing they're doing now that they need to do more easily, or the thing they need to do that they can't do. If they say "we use this other tool, and it's fine we just need one of our own", I ask "what is it about that tool that works for your purposes?", and so on. As I mention above, too, I've also learned to ask pointed questions about the domain itself so it's clear I am not a meteorologist. Together, we identify essential features.

Then I build a paper prototype.

<p class="with-image" markdown="1">
  ![My helpful screenshot]({{site.url}}/images/design-thinking1.gif)
</p>

Next, I get the users back together and I have them demo the paper prototype. We rapidly and collaboratively edit the paper thing until we have something more usable and intuitive for *them*.

<p class="with-image" markdown="1">
  ![My helpful screenshot]({{site.url}}/images/design-thinking2.gif)
</p>

And finally, once we've determined the basic outline of a soltion in a tangible form, I start coding.

<p class="with-image" markdown="1">
  ![My helpful screenshot]({{site.url}}/images/app-demo.gif)
</p>

I can be confident that I won't have to completely tear down my code to accommodate a super important, super secret feature. And if I do need to make changes, they will build onto our minimum viable product.
