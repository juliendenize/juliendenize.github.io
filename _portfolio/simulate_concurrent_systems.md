---
title: "Simulate Concurrent Systems"
collection: portfolio
permalink: /portfolio/simulate_concurrent_systems
date: 2019-01-01
excerpt: '[Github](https://github.com/juliendenize/Simulate_concurrent_systems)'
---

## About
In IT, it's common for different processes to share resources. However, these resources must be protected so that two processes cannot access them at the same time. In some cases, this blocking of resources leads to an interlocking situation that prevents processes from running.

Let's take the example of a program that blocks two cabins and then releases them:

- Take a cabin
- Take a cabin
- Release a cabin
- Release a cabin

Now let's take two processes, P1 and P2, which execute this program as follows:

- P1 executes line 1 // 1 cabin
- P2 executes line 1 // 0 booths
- P1 blocked at line 2 // 0 booths
- P2 blocked at line 2 // 0 cab => Interlocking

It is therefore useful to be able to model programs and processes to check that there are no interlocking solutions. This is what the program finally developed does.


## Code Link

[Github](https://github.com/juliendenize/Simulate_concurrent_systems)

## Stack

Java
