---
layout: post
title: The Third Week
---

**What did I do this past week?** As expected, another busy week for me. I turned in my OOP project a couple days early, only to join in on the stress of other students as they discovered failing Travis builds and asked questions that made me go back and check my submission. I knocked out my Compilers project. I read a lot of Government. I applied for jobs. I administrated my organizations. Last night my old PintOS team reunited and stayed up late to compete in the annual [2016 NSA Codebreaker Challenge](https://codebreaker.ltsnet.net/home).

**What's in my way?** That Codebreaking Challenge was going really well until Task 5. The fact that no-one's completed Task 6 worries me about what lies ahead. We still have over 100 days to complete it, but my team would like to end up in the first 50 and place UT Austin within the top 10. As far as I know, we're the only ones competing for our school at the moment.

**What will I do next week?** Next week I'll be cramming for a Government exam, doing more readings from all over, and trying to make progress on the Codebreaker Challenge.

The public tests for the Collatz project were an immense source of concern for me last week. I don't mind a fraction of my grade being based on how well my software performs - in fact, I think that's a good idea for motivating students to write better code. What does worry me is the possibility of losing points because of someone else's mistake. Although we were reassured that we would not lose points from invalid tests, I still lost a great deal of confidence every time I saw my program fail on a test because I was never sure which was the culprit: the test, or my code.

There always seemed to be a new mistake to watch out for. The first one was simply overflow - that was quickly discussed and taken care of. Then there were concerns with line endings from Windows. Then there were concerns about missing a newline at the end of the file. Then there were concerns about having too many newlines at the end of the file. Without a means of definitively saying "valid" or "not valid", I was never sure if the instructors and students were aware of these issues, and awaiting feedback from Piazza could be a slow process.

Perhaps in the future, we could have an open source validation script available to us to verify our tests. Or perhaps the tests could be due earlier than the project, so we could work on the project with a reliable test suite to shape our code with. Regardless, I'd like there to be less uncertainty about factors that could affect our grade and yet are out of our control, so we can stay focused on the factors that are.

**Tip of the Week:** For those of you on Windows 10, Bash on Ubuntu on Windows is definitely worth configuring and installing to get all sorts of UNIX goodies in a Windows environment. Most programs I've tried from apt-get work well, and it is often much easier to configure the Linux versions of command line tools than their Windows "equivalents". Some things to watch out for: suspending tasks with `Ctrl+Z` is buggy for fullscreen applications, and you should never use Windows programs to write directly to Ubuntu managed directories, as they use different underlying filesystems. Instead, you can access your Windows folders from Bash, and copy/edit files into Ubuntu managed directories with no issues.