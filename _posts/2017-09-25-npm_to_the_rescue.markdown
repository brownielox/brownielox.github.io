---
layout: post
title:  "npm to the rescue"
date:   2017-09-25 19:30:24 +0000
---

At one point in this React/Redux project, I realized that at some point in the future I want to add more data to it, but not immediately. As I thought that through, it occurred to me that all I'll need to do is add another component to make that happen, and suddenly one of the major advantages of React was very clear to me: scalability. Adding parts to my previous projects has taken much more work, whereas once you build what you need within the React framework, building it out becomes much easier. Rails is easy to set up but more challenging to move parts around, React to me seemed slightly more challenging to set up, but once that's don't moving things around is super easy. 

It was also fun to take advantage of a couple of the packages available to me through npm that other developers had built. My project required some calculation of distances using coordinates, but doing so isn't as simple as using the Pythagorean Theorem. On the globe, the curvature of the Earth also comes into play. Luckily, someone had built a very convenient little package that let me let them take care of the distance formula, and I was super appreciative, as I don't think I've done geometry since Mr. Passerini's class in 10th grade. Though my app primarily calculates distances within Philadelphia (though of course the user can drop your location pin wherever she wants), and I probably could have gotten away with caclulating the distances as though the area was flat, complete accuracy is clearly better. 

The [article](http://www.philly.com/philly/news/special_packages/toxic-city/philadelphia-lead-soil-fishtown-construction-dust.html) that the idea for my app came from is about former lead smelting sites in Philadelphia, and the health risk they pose to children growing up nearby. I built the app as a convenient way for parents to see their distances from various sites across the neighborhood, as the map provided in the article simply showed static locations. The map did, however, provide a list of sites in other cities, and I'd eventually like to expand to include those, too. 
