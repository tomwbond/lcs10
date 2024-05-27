---
layout: post
title: "Good Traffic Management Guide"
date: "2018-11-04"
permalink: "/traffic-management-guide/"
author: "SEPECAT"
categories: "Guides"
tags:
excerpt: "In Cities: Skylines, every city is unique. But there are general principles that always apply for good traffic flow no matter what." 
image:
---

# Good Traffic Management Guide

![Traffic overlay](/images/traffic-overlay-good-traffic.jpg)

In Cities: Skylines, every city is unique. The geography, size of your districts, mix of commercial and industrial areas, available outside connections and a hundred other factors will determine the right traffic management solution for each part of the city.

That said, the general principles always apply. There’s optimal strategies that can help you keep traffic flow well over 80% no matter how big your city gets. In this guide, I’ll talk about some of those principles. We’ll also look at a few of the game’s systems, UI and quirks.

Here’s a few other posts that complement this one: [how to reduce traffic in the first place](2018-09-02-reduce-manage-traffic-cities-skylines.md), [how to build bike highways](2018-10-20-biking-superhighways-guide-cycling.md), [how to add pedestrian crossings](2018-09-02-easily-add-crosswalks-without-junctions.md), [rundown of every public transport type](2018-10-03-guide-every-type-public-transport.md).

*Note on compatibility: I’m writing this late 2018, after the first seven expansions, including Industries. I’m talking about the unmodded game, so the advice here should work across PC, Mac, Switch, Xbox, PS4 and Linux versions.*

## What needs to go where

It’s worth just remembering that the game simulates individual people and goods. They need to literally move from one place to another. Traffic isn’t aggregated or simulated in an abstract way. If traffic can’t get through, it will eventually just despawn. That means businesses can’t fill their jobs and shops can’t stock their shelves. Left alone, those buildings will close down and get abandoned because they can’t operate.

Residents travel from home to work, or home to leisure, and then back. They don’t travel within residential areas - to visit friends, for example. So you don’t need to account for those kinds of journeys. Tourists arrive by road, rail, air or sea, make their visit, then leave the same way.

Goods and cargo travel to commercial areas. Depending on your setup, they’ll come from outside the city, your industrial areas, or a mix of both. I’ve broken that down a bit more on my [supply chain article](2018-09-09-supply-chain-specialised-industry.md).

In terms of broader city planning, we don’t want residential areas in between industrial and commercial districts - or at least, we don’t want the residential area to be the route between the two. That’s achievable by adding faster bypasses and using policies like Heavy Traffic Ban.

Just for interest, offices also export, but in their case they sell services. It’s not really clear how that works, but IT Clusters, for example, can be seen lit up in the Export tab.

## The most important concept: the hierarchy

![The traffic hierarchy](/images/road-hierarchy-small.jpg)

In every part of the city, the most important design principle is to create a road hierarchy. Think of a tree with the trunk roads bearing most of the weight, leading to increasingly small branches as vehicles get closer to their destination.

We can use small, slow two-lane roads to serve the suburbs, faster four-lane roads serving commercial areas and district centres, and fast six-lane roads or highways to link districts together.

In the picture above you can see the green roads serving houses. Those zones, top and bottom, are served by a medium-sized central road in red (with trams, a small commercial centre and service buildings). Perpendicular to that is another medium road and the rail network in blue. In a typical road system, those could be highway but I tend to go for public transport options. Whatever you use, the blue lines take people out of their district and on to another one.

What we want to do is stop traffic passing through districts that aren’t their destination. When traffic that is travelling through combines with local traffic, we get jams. During the journey, we want to funnel traffic up and down the hierarchy.

## City master planning

Once I’d got a huge 250k population city out of my system, I became much keener on making more interesting cities. Ones bound by tricky geography or built around unusual public transport setups. Now that the [Industries](2018-10-31-industries-expansion-review.md) expansion is out, I’m looking forward to building a sprawling region of small industrial towns.

What I’m trying to say is that while there’s optimal strategies for high population, I get more satisfaction from smaller, more characterful cities. I guess that’s the RPG gamer in me: wanting to play based around interesting trait and build choices.

Anyway. Regardless of that, to achieve whatever you’re trying to achieve, it’s important to have a sense of the general shape of the city from quite early on. We’re talking broad strokes here. Where the biggest industries will be, where the biggest commercial district will take shape. What will be suburbs, what will be high-density housing?

That forward-planning extends to which tiles you buy as the city expands. Without mods, you can buy a maximum of 9 tiles within a 5x5 grid. In other words, you can’t have a city that is 9x1 in shape. It also means you can’t buy more than 2 tiles in any direction from your starting tile.

## Getting off to a good start

Right at the start, it’s a good idea to bring the highway entrance well into the map. It’s important to spread demand for across multiple entrances and exits. Early on, this’ll just be small, slow basic roads. But as long as you leave space, that can eventually upgrade to highway. Once it’s the fastest road in the city, traffic will be encouraged to use it rather than using other districts as cut-throughs.

It’s especially important to leave wide corridors in your city as you expand. Later, you’ll be glad of the space to upgrade roads, or lay down parallel train tracks. In the early days, a single train line can cope with internal traffic, cargo trains and tourism. But later, you’ll probably want 3-5 separate tracks.

That’s especially true about buildings that don’t unlock until later like the cargo hub and airport. Where they go and how they get integrated into the city needs careful thought and advance planning. You might also want to start industrial towns on the outskirts and need highways leading to them.

If there isn’t space to grow, the bulldozing operation to retrofit the city will take forever and cost a fortune. I often get a notepad out. Something about getting things down on paper makes it much easier to work out.

## Encouraging traffic onto trunks roads

Before every journey, the game calculates the fastest route to the destination. Because roads have different speed limits, traffic will gravitate towards ones where they can move faster. That means even if the slower roads are a shorter path, they’ll naturally head to the main roads - in most cases.

If necessary, you could keep districts disconnected from the next one over except for the main road. But in most cases, a well thought out system can still have plenty of interconnections for short. Those don’t actually need to be sent out onto the highway.

By the way, you can replace key segments of the road network with public transport. In my current city, I’ve got railway lines the run down the whole spine of the city. There’s normal and multi-platform stations, district and express trains and multiple parallel lines. The setup is fast, high-capacity and connects all parts of the city. In this design, the railway replaces highways. Because the train is just so much faster than driving round on the roads, most people leave the car at home.

## Identifying and diagnosing problems

![Traffic overlay busy roads](/images/traffic-overlay-busy-streets.jpg)

The Traffic overlay in the UI is the most important tool for finding problems in the network. Red spots in the Traffic panel aren’t necessarily a problem. If you zoom in and see continuous, steady flow, then it’s fine. The red shows usage rather than congestion. If the traffic isn’t too backed up, then you can leave it alone.

Conversely, a high traffic flow percentage doesn’t mean there’s no issues. 85% is just the average, and in a big city, a high number can mask a couple of extremely troublesome areas.

![Imports coming into the city](/images/imports-overlay-commercial-2.jpg)

The Imports and Exports tab is also a key source of information. By looking at which companies are importing what, and from where, you’ll be able to work out if you need a new highway interchange just to deal with oil imports from outside the city, for example.

![The Routes overlay](/images/routes-overlay-trucks.jpg)

On a more local level, the Routes overlay is great for diagnosing problems with busy intersections. Having spotted a bad junction, toggle through the filters to get a live display of who is using that road now, where they came from, and where they’re headed. By separating out private cars, or cargo, it’s possible to identify what’s causing the biggest issues.

As an example, I recently had a very backed up set of junctions. After looking through the filters, I noticed a disproportionate number of garbage trucks. Because of where I’d put the recycling centres, lots of them were trying to pass through to reach more distant parts of the city. Part of the fix was putting some new centres at the other end of town, so trucks could service those areas without needing to pass through the bottleneck.

## Traffic lights, stop signs and priority roads

![Stop signs, junctions](/images/stop-signs-2.jpg)

By default, the game adds traffic lights to large junctions. Early on, that’s no problem, but as traffic load grows, lights can sometimes become inefficient. That’s especially true when they’re holding up traffic on your main roads in favour of side roads.

The stop signs make vehicles coming from that direction give way to traffic on the main road. These are often the best option as they allow generally smooth flow vehicles on the road that has priority. Cars coming from the other road only slot in when there’s a gap.

Where two roads of equal priority meet, it’s worth experimenting just turning off the lights and signs and seeing what happens. Often the result is a little messy but fairly well flowing. The priority road system turns all the stop signs in favour of the road in question. That’s handy as a starting point, but in general, it’s better to deal with each intersection individually.

Just as a side note, guides produced before the Mass Transit patch won’t usually talk about this. Before the free update launched at the time, it wasn’t possible to control traffic lights and stop signs.

## Effective interchanges and intersections

![Interchange into the city](/images/raised-roundabout-interchange.jpg)

I haven’t got many big or complex interchanges in my own cities because I tend to focus on public transport, bikes and demand reduction. I usually just need a few modifications to improve flow. But if you’re building a car-heavy city or just seem to crack a troublesome hotspot, then turning to the internet can help. The [Cities: Skylines Reddit](https://www.reddit.com/r/CitiesSkylines/) has a lot of interesting ideas. For tried and tested real-life layouts, try this brilliant [Wikipedia](https://en.wikipedia.org/wiki/Interchange_(road)) page.

![Interchange](/images/raised-highway-interchange.jpg)

Above you can see a fairly standard interchange with extra entry and exit points, and a collector lane on the right. That avoids traffic from the nearby industrial area from joining the main highway and interrupting vehicles who are passing straight through.

The main principle is that fewer, bigger interchanges usually works better. Junctions themselves shouldn’t be too close together. When laying down roads, the circles show the minimum distance to leave between intersections. If they’re closer cars will sometimes get stuck in an endless loop between the roads.

It’s a great idea to create bridges and tunnels for pedestrians that lets them avoid crossing at busy intersections. The last thing you need is hundreds of people on foot needlessly clogging up junctions that would otherwise be able to cope. Pedestrians prefer paths to sidewalks, and they’ll choose them even if the route is slightly longer.

Speaking of intersections, where possible I stick to three-way junctions. Four-way crossroads - especially in busier areas - can grind to a halt. With traffic coming from all directions, 25% of the time just isn’t enough to clear backlogs.

Wider roads are not always - or not even often - the answer. Sometimes it’s the right solution: three lanes letting traffic queue to go left, right or straight on can create three reasonable lines from one very long one. But often - because traffic chooses its lane so early - adding lanes won’t fix anything because it doesn’t solve the underlying problem.

## One way systems

![One way traffic system](/images/one-way-system-forestry.jpg)

In busy areas, one way roads can be great for improving traffic. By avoiding vehicles - cargo especially - crossing in front of each other, an orderly procession can be organised around a whole area.

![One way traffic system](/images/one-way-system-forestry-2.jpg)

The idea works in and around buildings as well as separating incoming and outgoing traffic.

## Using roundabouts

![Roundabout with passthroughs](/images/roundabout-double-passthrough.jpg)

Roundabouts can solve a lot of problems. They’re great for keeping traffic flowing in places where a simple interaction has ground to a halt. A simple circular design works well in lower flow areas.

When the standard design begins to struggle under the weight of traffic some modifications and additions can significantly improve capacity. These can include adding a through road that lets traffic going straight on keep going unimpeded.

By using a tunnel or bridge, it’s possible to have two through roads. In the example above, traffic going straight over doesn't need to interact with traffic turning. If I was making that again, I'd use smaller roads. Six lanes aren't great for this sort of use.

To keep roundabouts round, use the curved road tool and carefully measure each arm to be same length. Alternatively, draw straight roads then connect them with curved arms. Once you’ve got a circle, delete the straight parts.

## Why everyone drives in the same lane

Traffic in Cities: Skylines gets into lane early. They know well in advance which junction or exit they’re taking, and pick a lane much earlier than they need to. Actually, they’re driving well - rather than driving in an empty lane then trying to butt in.

Initially, it can create infuriating scenes where it seems like everyone is being daft and driving in a single lane. But actually, it’s a telltale sign of a problem in the city’s road layout. Mods exist (like [Traffic Manager: President Edition](https://steamcommunity.com/sharedfiles/filedetails/?id=583429740)) that let you edit the driving AI. These usually come with a performance hit, but modding isn’t the only solution.

Essentially, the problem is that too many people are going to the same place. 

There’s lots of ways to address that, but one trick involves exits on both sides of the road. Ideally, main roads should pass in between the districts they serve, so traffic gets spread left and right. But if your main road passes up the right-hand side of the city, then all the important junctions will be on the left. So spreading them out is easier said than done.

In that scenario, you can improve the worst sections by creating an exit on the opposite site that then passes over or under the main road. That way, you get a right-hand exit for a left-hand district. Mix left and right all the way up and you’ll get more lane usage.

*Thanks so much for reading! I hope you found some of this useful. It's such a broad topic it's difficult to know how high level or detailed this sort of post should be. If there's anything specific you'd like covered, let me know - I'll write about it. Thanks again!*