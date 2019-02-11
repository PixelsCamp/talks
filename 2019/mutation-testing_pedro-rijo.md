An intro to Mutation Testing - or why coverage sucks
=========================

* Speaker   : [Pedro Rijo](https://pixels.camp/pedrorijo91)
* Length    : ~ 30min-45min
* Language  : English

Description
-----------

Mutation testing has been evolving into a real candidate to become the de facto metric for assessing the quality of a test suite, defying the throne that has been occupied by code coverage until now.

The concept of mutation testing is quite simple: mutations are introduced on the codebase and the test suite is run against the mutated code. If your test suite is strong, then it should catch the mutation, by having at least one test failing.

In this talk I plan to show how coverage by itself doesn't guarantee quality on the test suite, and how mutation testing can effectively find bugs on your code and tests.

Speaker Bio
-----------

**Pedro Rijo**

![Speaker Image](https://avatars2.githubusercontent.com/u/1999050?v=4)

Another JVM guy battling between Scala, Java, and whatever gets in the way. Code quality freak. The first functional programming moderated advocate you've met 😀.

Currently working as a backend product engineer at Feedzai, making digital payments safer. Former software engineer at Codacy and FenixEdu.

Links
-----

* Blog: https://pedrorijo.com/
* Company: [Feedzai](http://feedzai.com/)
* GitHub: https://github.com/pedrorijo91
* Twitter: https://twitter.com/pedrorijo91

Extra Information
-----------------

I've been a big advocate of having codebases with a strong test suite, and I always used coverage as a metric for how battle tested a codebase is. But after finding some legacy tests that were almost useless I started to question the utility of code coverage, and started a quest to find a real test strength metric.

I quickly got in contact with the concept of mutation testing, which at a high level can be seen as the idea of introducing small changes (mutations) on the code and checking if our test suite finds the bug. This is an equivalent approach to the famous [Netflix Chaos Monkey](https://github.com/Netflix/chaosmonkey), but mutation testing operates at a Unit Test level.

This talk aims to show the problems of relying on coverage as the ground truth for test suit strength, and how mutation testing can be a viable alternative to coverage. Furthermore I plan to cover the basic concepts of mutation testing, as well as the main difficulties and limitations.

Finally, I will cover a java mutation testing tool called [PIT](http://pitest.org/), and how we introduced mutation testing on Feedzai codebase to help catching bugs before getting into production.

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
