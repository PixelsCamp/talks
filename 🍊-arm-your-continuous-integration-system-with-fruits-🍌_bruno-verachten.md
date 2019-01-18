* Replace all text within `{{ ... }}` (also removing the braces) with the proper information.
* This file will be automatically parsed by our backoffice, all fields are mandatory unless stated otherwise.

`--8<-- DELETE THIS LINE AND EVERYTHING ABOVE IT BEFORE SUBMITTING YOUR PROPOSAL --8<--`

🍊 ARM your continuous integration system with fruits! 🍌
=========================

* Speaker   : Bruno Verachten
* Available : Any time
* Length    : 60 minutes
* Language  : English

Description
-----------

Being able to build on a remote machine each time we commit has been a major progress for us, developers.

By using `Docker`, things have been easier as well! No more dependency hell when you have to build two incompatible products.
This solution looks almost perfect… until you reach a threshold.
As your [gitlab-ci] will become more and more popular within your organization, you may experience longer waiting queues until the next batch of [Runners] is released.
You maybe have a Raspberry Pi taking dust on your desk or in your drawer.
What if I told you you could transform this momentarily useless piece of hardware into a brand new Gitlab-ci Runner? This way, you could shorten the time your jobs spend in the queue.
But wait, there is more. What if there was a cheaper solution that could allow you to create a Gitlab-ci Runner for a 15€ investment? You may have heard about Banana Pi, Orange Pi, and other variations of fruit Pi(e). The competition is harsh between these manufacturers, and you can find pretty nifty machines for darn cheap. These machine can run `Docker`, and even Gitlab-Runner on top of it.
You shall leave this talk by knowing the basics to start your own Gitlab Runner for 15€.

Speaker Bio
-----------

Father of *two*, husband of *one*, geek in denial, fond of handheld devices since 1989, beekeepeer and [permie].
`#Linux #Android #Docker #ARMV8 #IOT`

* Joined [Worldline] in 1999.
* Currently works as a continuous integration for mobile development specialist in a transversal unit. 
* Fond of Linux and open source, hand-held devices ([SBC]...).
* Also interested in new techniques in gardening, woodworking by hand, bike commuting and tons of other subjects.
* Disguised as taciturn, but a chatterbox.

Trying to push the use of ARM Socs in his [job] and everywhere [else]...

[permie]: https://www.credential.net/5ufvm4zp
[Worldline]: https://worldline.com/
[SBC]: https://www.armbian.com/download/
[else]: https://github.com/gounthar
[job]: https://github.com/WorksOnArm/cluster/issues/81

Links
-----

* Blog: https://medium.com/@poddingue
* Company: https://fr.worldline.com/
* GitHub: https://github.com/gounthar/

Extra Information
-----------------

The subject I address is not new (I'm not the only one using [gitlab-ci]), but the way I use it with the hardware I chose is innovative. 
I've been working on this subject for quite a while now, and have lead a few workshops on this very subject in the [company] I work for.
I have also written a few articles on ARM/Linux/Docker/Gitlab in my company, and I am in the process of rewriting them to publish on [medium] and on [Worldline Tech].
I have given this talk at [DevFestGR18].

> This is a feedback on experience, but there are quite a few technical takeaways.

[DevFestGR18]:https://heraklion.googledevelopers.gr/devfest-greece-2018/
[company]: https://worldline.com/
[medium]: https://medium.com/@poddingue
[Worldline Tech]: https://blog.worldline.tech/

You will find previous [slides] of my talks and twitter references [there].

This talk exists in two versions:

 1. Plain Jane
 2. Star Wars edition

[there]:https://twitter.com/i/moments/1050320228901707776
[DevFestGR18]:https://heraklion.googledevelopers.gr/devfest-greece-2018/#rockstars
[LinuxLab]:https://2018.linux-lab.it/speakers/
[slides]:https://speakerdeck.com/gounthar
[talk]: https://twitter.com/i/moments/1014591620841340929
[Techforum eXplore]: https://twitter.com/hashtag/TexWL18?src=hash
[OpenSTF]: https://github.com/openstf/stf
[gitlab-ci]:https://about.gitlab.com/product/continuous-integration/
[Runners]:https://docs.gitlab.com/runner/
