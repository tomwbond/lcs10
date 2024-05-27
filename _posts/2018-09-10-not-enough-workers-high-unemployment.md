---
layout: post
title: "Guide to Fix 'Not Enough Workers' Even When You Have High Unemployment"
date: "2018-09-10"
permalink: "/not-enough-workers-high-unemployment/"
author: "SEPECAT"
categories: "Tips"
tags:
excerpt: "Something a lot of us run into is buildings saying they don’t have enough workers when it seems like there’s more than enough to go around. Let's try to fix it."
image: "/images/not-enough-workers-high-unemployment.jpg"
---

# Guide to Fix 'Not Enough Workers' Even When You Have High Unemployment

![Not enough workers with high unemployment](/images/not-enough-workers.jpg)

*'Not enough workers!' 13% unemployment and 800 jobs unfilled. What's going on?*

In Cities: Skylines, something a lot of us run into is buildings saying they don’t have enough workers when it seems like there’s more than enough to go around. In fact, sometimes it makes no sense at all. Hundreds, even thousands of jobs left open, with unemployment in the double digits.

It's frustrating, and more importantly, your buildings can't work efficiently. They can't process enough goods, which means your shops might struggle to fill their shelves. They'll then turn to other cities and import goods, causing additional traffic on roads not designed to cope... and on and on.

## Not enough workers when you’ve got high unemployment. What's going on?

Well, in some cases, the solution is obvious. If your unemployment is something like 2-3%, then most likely you need to zone new residential areas. Bring in new workers, and they’ll gladly fill the jobs.
But other times, that doesn’t seem to be the problem. Pull up the Population overlay and look at the unemployment number. If the UI tells you 13% of the working age population is unemployed, and yet there are 2,000 jobs available, clearly, there's a problem. Lots of people who want to work are stuck at home waiting for you to make some changes.

It's worth saying that unemployment rarely seems ever to fall below about 3%. Because the game simulates actual people, rather than doing it in the abstract, I think that's inevitable. My guess is that some people live too far away. If the job is the opposite end of the city, I think the transport simulation reckons they may time out and despawn before they get there. There's also a general churn you can't get around: the time between someone retiring from the workforce and a new person filling that job. That's why 2-3% is usually too low. A good range to aim for feels like 5-8%.

## The usual suspects

![](/images/high-unemployment.jpg)

The industry specialisations, especially, use a lot of uneducated workers. If you’ve got a well-educated population, that can be a problem. If most of your people studied at university and you’ve just built a big oil field on the edge of town, you’re going to have trouble filling those jobs.

That's not because university-educated workers will refuse jobs at a lower education level, but because they'll try to find another job first. In other words, they'll wait quite a long time for a more suitable job to open up (someone else retires, or you zone new office areas, etc). Eventually, though, they'll take that lower-education job.

Often then, the problem is only temporary. And although you can use policies like Schools Out to encourage people to leave education early and go straight to work, it's not necessary. Also,  better-educated cims produce less garbage, so universities are not a waste.

## Check the roads, junctions and public transport options

Now, although education is usually the big factor here, it's important to also check the basics. Make sure your transport options are functioning as expected.

One thing that can cause a worker shortage is people finding it hard to get to work. If you’re lacking decent public transport options and you’ve got long tailbacks on the road, workers might be struggling to fill those jobs because they can't get there quickly enough before they despawn.  Some [guidance on public transport here](2018-10-03-guide-every-type-public-transport.md).

Use the Traffic overlay to identify hotspots and also do a simple sense check that all the roads are actually connected and that you’ve not got some one-way system that’s causing people to have to leave the city and come back to get there. Check the Routes overlay for that, and make sure there's no weird behaviour going on.

This approach is especially true for big industrial areas which are often out of town. I've starved portions of industrial estates of their city services by making comprehensive one-way systems for cargo traffic, forgetting to allow for workers, the police etc. to get there if they're coming from the opposite direction.

## Sit tight and wait it out

Assuming the roads are OK and there are sufficient transport options, then what’s happening is that your educated workforce are trying to find more relevant jobs first. If you open up your industries and see that the few workers who have taken jobs are listed as over-educated, then that’s probably confirmation.

In this case, you just need to wait. Eventually, the better-educated cims will stop looking for alternatives and take jobs below their education level. There’s no downside to this (except, I guess, the costs of educating them to a lower level than they needed!), although be aware that if a more suitable job - at a new office block, say - opens up, they’ll switch over.

It's worth being cautious about expansion, too. If you've got a delicate balance and it took ages to fill the industrial jobs, you could put yourself back to square one if you zone a huge new office area because the best-educated workers will transfer, leaving gaps for you to fill.

For that reason, it's better to zone residential first and make sure you continue to have unemployment north of 10% at most times. That way, hopefully you'll get a smooth transition as your new jobs fill up. For better or worse, there's no gameplay penalty for running high unemployment, so being cautious in this way doesn't really have a downside.

## Not enough educated workers

![University and highly educated cims](/images/university-education-employment.jpg)

This one is a slightly different problem, but it’s worth mentioning because it’s related and comes back to education. 

Often, it’ll be new office zoning that lacks educated workers. Although this problem is pretty straightforward, there’s no quick solution. Open the Education panel and check that you’ve got plenty of capacity at each level of education. 

You’ll also need to be sure the whole city has physical access to those buildings. They don’t need to be nearby - and you’ll often only have a couple of universities anyway - but they do need to be easily reached by public transport.

After that, it’s just a case of watching as the number of graduates from each level steadily ticks up. Check back often to make sure it's going in the right direction. As long as it is, those higher-education jobs will naturally fill up.

## Summary

In the case of worker shortages despite high unemployment, it's important to implement quick and efficient public transport options and make sure roads are properly connected. Be sure you're not causing any strange behaviour through bad junctions of one-way systems.

Well-educated citizens will eventually take lower-education jobs, but they'll wait to see if a more suitable job opens up first. Also, if a new job arrives they'll likely switch, causing the problem all over again. For that reason, it's good to keep unemployment at 10% or so, to smooth transitions as your population grows.

Otherwise, it's a case of being patient. The Schools Out policy can help you in pinch (or in an industry-only town), but has its own downsides like more garbage. Also, if your long term plan includes being mainly an office city, Schools Out will just store up problems for later.

So there you are - I hope this is helpful. These problems are two sides of the same coin. Most of the time they come down to education - either too much of it or too little. Happy building!