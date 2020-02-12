Architecture v2.0: Monolyths, Microservices, Startup's horrible code and how do you "clean up" 200k Lines of Code
=================================================

* Speaker   : [Miguel Mascarenhas Filipe](https://pixels.camp/msf)
* Length    : 50
* Language  : English

Description
-----------

When I joined Unbabel in March 2019. It's core system, the translation pipeline was at cross-roads of trying to refactor and re-architect a beautiful Monolyth into Microservices. It was an evolving codebase whose first commit was made by the current CEO in 2013. It is safe to say it has its fair share of shortcomings and failings. =)
In this talk I'll tell a story on how we leapfrogged our old v1.0 architecture (and what were its problems) and built a much simpler, easier to maintain and operate system.
Also, be warned, unsurprisingly, the solution isn't a micro-service based architecture. :-)

To provide a bit more detail and "juice": Complexity is our enemy. Architectures with complex tightly-coupled distributed systems have complex failure scenarios and are by definition hard to debug and operate. If you had a problematic monolith and break it into 10 pieces, it is probable that you got yourself 100 problems now.


Speaker Bio
-----------

**Miguel Filipe**

![Miguel Filipe](https://avatars0.githubusercontent.com/u/32140?v=4)

I’m a Software Engineer with 15 years of experience including start-ups and leading software corporations in three countries. I dive deep and take an end-to-end perspective. I'm always looking for hard problems to crack and high quality solutions. I currently work on the new architecture of Unbabel's translation services. Previously I worked on diverse problems such as backends for Citymapper's mobile apps, large scale distributed systems for Microsoft and Amazon Web Services where I launched DynamoDB, the world leading NoSQL Cloud Database, which led to co-authoring 13 US patents. Problems are waiting to be solved. =)

Links
-----

* Blog: https://twitter.com/m3thos
* Company: https://unbabel.com
* GitHub: https://github.com/msf
* Photo: https://s3.amazonaws.com/keybase_processed_uploads/b3b92f1a8ef25629ad5f18163278c605_360_360_square_360.png

Extra Information
-----------------

I once maintained a linux kernel rootit that was very hard to detect and didn't use the syscall table...

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
