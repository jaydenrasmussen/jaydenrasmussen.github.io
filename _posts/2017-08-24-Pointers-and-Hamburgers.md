---
layout: post
title: Pointers and Hamburgers
date: 2017-08-24
category: blog
---
Pointers are counter-intuitive. There's really no way around it, to new students it can be very difficult to understand the true concept of *how*, *why* and *what* pointers use is. 

Modern computing has made it possible to substantiate variables as needed with little effect on the performance of code (especially with languages like javascript). So, it can be difficult to understand why *pointing* to an address is more effective than simpling defining a new point in memory. 


Let's make a better example. Everywhere I turned when I was learning the concept of pointers I read the example of a friend's house or a business but I think that example is too ethereal and doesn't quite do the concept justice (pointers really are a beautiful concept). Let's begin with a question.


If you wanted to make a hamburger, what would you need?

    - Buns
    - Lettuce
    - Cheese
    - Hamburger

Okay... but what if we wanted to make it from scratch?

Well, then you would need grain to grind into flour, chickens to lay the eggs to mix with the flour to make the dough for the buns, an oven to cook it in, a few months time to grow the lettuce, ferment the cheese from the cow you milked (and later slaughtered), fire cook it all over and so on. This takes *a lot* of effort just for a hamburger. What if there was a place we could go and simply get a pre-made cheeseburger? That would make it *much easier*.

This is where pointers come in. While you could go through all the trouble to make all of those ingredients from scratch it's much easier to leave that to someone else. When you use a pointer to substantiate a value you are doing just that, leaving the hard part of substantiating the value with another portion of the code. This means that, on the machine it is effectively using one process to simple edit *existing* memory instead of cleaning up unused memory later. 

If you want to write fast code, you need to write it as minimally as possible.
