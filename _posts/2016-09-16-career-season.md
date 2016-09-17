---
layout: post
title: The (Job) Hunt
---

**What did I do this past week?** What a week! I spent my time studying for a Government exam last Thursday, attending student organization meetings and corporate events, and applying for jobs. I've already scheduled a few interviews from online applications, so my job search has been going well so far. Protip: Most recruiters at the Career Fair will simply tell you to apply online anyway, so it never hurts to do it beforehand.

**What's in my way?** My to-do list never ends. I've got to crank out the Netflix project, and a Compilers project. At least there isn't an exam coming up (I think).

**What will I do next week?** Finishing Netflix and attending more corporate events, while consuming more free pizza than I'd like to admit. I found out last year that it's possible to get tired of free pizza.

Pair programming lives up to the hype. That is, when you do it correctly. Pay attention, respect your partner, and communicate like best friends. It's great to have a sounding board to bounce ideas off of, and it's great having a second pair of eyes watching every line of code. If it's not convenient to meet in person, punch "code together online" into Google and check out the top links. I'm very glad pair programming is actively promoted in this class, even if the projects (well, the ones we've seen) are do-able individually.

That said, I've personally found one area where pair programming doesn't always shine - intensive debugging. Rubber duck debugging is great, until a system becomes so complicated (think PintOS) that the English language no longer provides the bandwidth to explain it. Sometimes, a bug is so difficult to track down, that trying all the combinations of code and design choices and whatnot is the only way to make progress. A sort of bruteforce. In Operating Systems, there were some bugs that we'd spent hours hunting down as a team only to discover the problem later when we split up and worked individually. Our testing throughput was temporarily multiplied.

I highly doubt any bugs encountered in the Netflix project will require this extreme approach for debugging. Still, I think it's worth knowing when pair programming's effectiveness is diminished, so we can be more efficient with our time. Time *is* money, after all.

**Tip of the Week:** It's common for tech companies to send you a custom [HackerRank](https://www.hackerrank.com/) problem as your "screening" interview, a private timed online coding challenge with test cases. Some are hard, some are easy. What matters is that you're prepared for them. Here's my top 3 tips for doing your best:

 1. **Get familiar with the platform.** Check out HackerRank "the service" and do some of the medium-difficulty problems to understand the limitations of HackerRank "the platform". The provided code editor is... servicable, but not nearly as comforable as your favorite text editor or IDE. Running and compilation on the web interface is slow and time consuming. Make sure your favorite language's latest features and libraries are supported (and avoid using them if otherwise).
 2. **Carefully read the problem.** Really carefully. I once screwed myself over by interpreting the problem incorrectly, and only realizing my mistake in the last four minutes when it was too late. Again, getting familiar with the platform will make you familiar with how problems are defined. Knowing the upper bounds of your inputs, for example, will let you plan ahead for tougher hidden test cases, as the visible test cases will be significantly easier than the hidden ones. Pick your algorithms and data structures carefully from the get-go  - you probably won't have time to go back and replace them.
 3. **Allocate a lot of time for debugging.** Getting a problem right on the first try requires a great deal of luck, and you're better off leaving a good 10 minutes or more to fix and polish your code. HackerRank has no built-in debugger, so you're stuck with print statements. Put them everywhere. Know your program's state and have pen and paper ready. Draw your data structures and the way your code behaves on them.

Good hunting, and good luck!