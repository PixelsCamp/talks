GitOps - Operations done through git
=========================

* Speaker   : Luís Faceira
* Length    : 30 minutes
* Language  : English

Description
-----------

Git is one of the most common tools you will find on a software engineer's tool belt.
Naturally, most teams organize the changes they want to produce to a software system in their source code managed in Git. 

GitOps is an operational and pipeline pattern that establishes the same concept not just for source code but for every operational
aspect of your system. 

In this approach, all system and environments configuration is defined through git, and the process of applying changes to the
infrastructure follows the same practices and quality control procedures that a change in software does, making it possible to
review, check and promote across branches/environments any change that is made to a system. 

Speaker Bio
-----------
**Luís Faceira**

![Speaker Image](https://avatars2.githubusercontent.com/u/362512)

Luís is a Continuous Delivery and DevOps practitioner, coach and speaker, who has been passionate about the intersection of
technology and business since he started his first internet company in 98, with only 14 years old. 

After be.ubi, his software development/consultancy shop, participated in an high-demanding acceleration program in
Silicon Valley in 2013, he returned to Europe and started helping other teams, from small international startups to Fortune500
enterprises, improve the same level of software delivery velocity and quality.

Links
-----

* Company: https://beubi.com
* Twitter: https://twitter.com/luisfaceira
* LinkedIn: https://linkedin.com/in/faceira
* GitHub: https://github.com/luisfaceira

Extra Information
-----------------

This talk was proposed in the context of the cooperation with DevOps Lisbon.
A first iteration of it was done on the past Agile Portugal conference.

Talks for pixelscamp, such as this one, were proposed through Pull-Requests in github. To some, that might seem like a weird way to
use git/github. GitOps is about applying a similar mindset into operations, ensuring that there is the same level of cooperation,
visiblity and quality control into operating a system as there is to developing its code.
Example: want to scale up the nodes? Open a pull-request for it. Review it, check/measure the impact, merge and see it automatically
applied to the different dynamically managed environments.
