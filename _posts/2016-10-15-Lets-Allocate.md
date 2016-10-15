---
layout: post
title: Let's Allocate
---

**What did I do this past week?** I worked on the Allocator project. The bulk of the work has been done; now it's just a matter of writing tests and documentation, which shouldn't take too long, if our code performs as it should.

**What's in my way?** The rest of the Allocator project. I also have a Compilers project I need to work on. Fortunately, there aren't any exams coming up next week.

**What will I do next week?** More busywork. This ship is smooth sailing, for now. HackTX is coming up next weekend, so I'll need to spend some time thinking of project ideas. I'm giving a [presentation on databases](https://www.facebook.com/events/1018704884909210/) next Wednesday for ISSS and HackTX, and you should attend!

I'm beginning to believe. In C++. The memory management pattern of "allocation inside constructors, deallocation inside destructors" is an effective extension of "be careful to `free` your `malloc`s" to user defined classes and is a much needed abstraction for building "bigger" types. It makes me feel better declaring user-defined types on the stack rather than the heap, knowing that those types will - for the most part - clean up after themselves after exiting the stack frame.

I've lived with the luxury of garbage collection most of my life, but I am becoming increasingly comfortable with manual memory management. It's faster and cheaper. It won't cause program execution to suddenly halt. Dr. Novak has a great practical example: it would be disastrous for a robot walking down steps to start garbage collection mid-step. Fortunately for most consumer user experiences (phones, web browsers), people are used to delays, so garbage collection can be a large, practical convenience for the programmer.

The Allocator project, although perhaps simplified, reveals the complications of heap management, and just a single math error can result in [bad stuff happening](https://piazza.com/class/irybyipu8yu6jd?cid=497). Now imagine being responsible for the actual C++ standard allocator. That's a much bigger burden to carry, and makes me appreciate that experts (I hope) are on the case.

**Tip of the Week:** [Sitting down sucks](http://www.npr.org/sections/health-shots/2015/10/06/446295001/your-chair-is-killing-you-here-s-what-you-need-to-do-to-stop-it). The Windows program [Big Stretch Reminder](http://www.monkeymatt.com/bigstretch/) is a simple background timer that tells you to get up and stretch every 20 minutes (or as configured). It's easy to lose track of time during long programming sessions, so it's nice to be reminded to move around from time to time. It also doubles as a pair programming timer.
