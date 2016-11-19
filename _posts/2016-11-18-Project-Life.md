---
layout: post
title: Project Life
---

**What did I do this past week?** My partner and I finished the final project, [Life](https://www.cs.utexas.edu/users/downing/cs371p/projects/Life.html). I also finished my final Government exam.

**What's in my way?** I've got a Compilers code generator due in a few weeks. And some Finance Online to take care of this weekend.

**What will I do next week?** Writing that code generator, and eating plenty of food for Thanksgiving!

It's difficult to believe that we're nearing the end of the semester already. I can still remember the (perhaps unnecessary) long hours I spent optimizing [Collatz](https://www.cs.utexas.edu/users/downing/cs371p/projects/Collatz.html) and the discussions I had with my partner in solving [Netflix](https://www.cs.utexas.edu/users/downing/cs371p/projects/Netflix.html). One part of me is glad that they're over, but another part of me is sad that they'll be gone. It's refreshing to have a homework assignment from time to time that closely resembles, well, "real work" or "company work".

The Life project felt more like an exercise in being careful, than an implementation of a new concept. It closely resembled the Darwin project before, with a bit more added complexity, with the addition of an abstract class in the class hierarchy. The freedom to use `new` (finally!) and `delete` meant segmentation faults all over, despite efforts to follow every `new` with a `delete` elsewhere. We had logic errors, runtime errors, user errors, all sorts of errors. Fortunately, we were able to correct them by the time of submission.

I'd say at least 40% of the time I spend working on these projects is simply making sure they fit the specification. In many ways that's a good thing - getting clang-check warnings stomped out, using Valgrind to spot memory leaks, and writing documentation for Doxygen makes for, overall, better code. Getting an average of 3 unit tests per method takes a while on more complicated projects like Darwin and Life, not because they're necessarily hard to test, but because there's so many methods to test. 

I'm not a fan of the requirement, as it can also motivate lower quality tests in favor of quantity. For small trivial helper functions that can be quickly verified by means of visual inspection, I'd rather pack all their tests into a single test than write multiple (but repetitive) tests. Heck, sometimes I wanted to avoid writing helper functions so I didn't have to write 3 tests for them. I think a firm coverage goal such as "90%+ lines executed" in combination with a lesser requirement like "average 2 tests per method" would loosen up the overhead in the implementations and motivate higher quality tests.

Overall, I'm happy with how the projects turned out, and I learned a lot of useful software in the process. Now onto the exam...

**Tip of the Week:** Useful software!

- The browser plugin [HTTPS Everywhere](https://www.eff.org/Https-everywhere) by the [Electronic Frontier Foundation](https://www.eff.org/) enforces use of TLS/SSL for all websites that support it. 
 - They've also developed the plugin [Privacy Badger](https://www.eff.org/privacybadger) that blocks tracking cookies and adware.
 - [http://www.telerik.com/fiddler](Fiddler) is a tool that examines incoming and outgoing HTTP traffic on your phone/laptop/etc. Useful for debugging or reverse engineering web APIs.
 - [WinSCP](https://winscp.net/eng/download.php) is a GUI for [Secure Copy](https://en.wikipedia.org/wiki/Secure_copy) on Windows and enables easy file transfers to and from the CS lab machines. 
