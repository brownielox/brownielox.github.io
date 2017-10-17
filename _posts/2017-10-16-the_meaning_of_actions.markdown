---
layout: post
title:      "The meaning of actions"
date:       2017-10-16 23:55:22 -0400
permalink:  the_meaning_of_actions
---

One thing that took me longer than I would have liked to absorb is that, in Redux, “actions” merely refer to a list of actions, and the “reducers” are the actual execution of it. Once I started thinking of actions as the recipe, and reducers as the execution of the recipe, I suddenly stopped mixing them up and clicking aimlessly through the file tree when I was trying to look for the files. Calling them actions is a bit of a misnomer, though I suppose I don’t have a great alternative for right now. 

React and Redux are abstract enough that throughout the learning process I found analogies especially helpful. Once I thought of the recipes and the cooking enough times, I didn’t need to think it through anymore, like any useful memory device. I'm still on the lookout for a good analogy for the double ".then"s needed to return JSON from a promise, however. Promises themselves are well-named, but the data that comes back from the API call needs to be turned into JSON and then another .then is needed to be able to manipulate with the data. I'm still searching for an analogy for that one. 


