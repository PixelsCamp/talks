* Replace all text within `{{ ... }}` (also removing the braces) with the proper information.
* This file will be automatically parsed by our backoffice, all fields are mandatory unless stated otherwise.

`--8<-- DELETE THIS LINE AND EVERYTHING ABOVE IT BEFORE SUBMITTING YOUR PROPOSAL --8<--`

The Android device farm that fits in a (cloudy) pocket
=========================

* Speaker   : Bruno Verachten
* Available : Any time
* Length    : 60 minutes
* Language  : English

Description
-----------

`Android` developers are facing a common problem: how to test our applications on many devices without sacrificing too much time or money?

    * How to build and test automatically our applications for each commit?
    * How can we find those devices inside the company, whatever its size may be?
    * Could there be a directory somewhere that lists those available devices?
    * Could we use a device remotely and share it with other developers as if it were in the cloud?

What if you could answer all these questions with the help of a low cost device farm that fits into a pocket? A pocket full of clouds…

Poddingue, our proposal, aims to tackle this problem thanks to [Docker], [HypriotOS], [Armbian], [Gitlab CI] and [OpenSTF]. It’s an internal solution made of OSS readily available, but it has not yet been publicly announced as a whole.

This is a feedback about an idea on its way to production, a long journey full of different feelings.

At the end of the talk, you should know how to build your own cloudy pocket farm of Android devices and how to use it to test your applications within your ci pipeline.

And as I am cheap, you will also be surprised at how little money you need to build it.

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

I had a blast when I gave this [talk] at the 2018 [Techforum eXplore] conference. I got the best teaser award for day #2 and got very good comments at the end.

The subject I address is not new (I'm not the only one using [OpenSTF]), but the way I use it with the hardware I chose is innovative. 

> This is a feedback on experience, but there are quite a few technical takeaways.

I have also given this talk at [LinuxLab] and at [DevFestGR18].
You will find previous [slides] of my talks and twitter references [there].

[there]:https://twitter.com/i/moments/1050320228901707776
[DevFestGR18]:https://heraklion.googledevelopers.gr/devfest-greece-2018/#rockstars
[LinuxLab]:https://2018.linux-lab.it/speakers/
[slides]:https://speakerdeck.com/gounthar
[talk]: https://twitter.com/i/moments/1014591620841340929
[Techforum eXplore]: https://twitter.com/hashtag/TexWL18?src=hash
[OpenSTF]: https://github.com/openstf/stf

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
[Docker]: https://www.docker.com/
[OpenSTF]: https://github.com/openstf/stf
[HypriotOS]: https://blog.hypriot.com/
[Armbian]: https://www.armbian.com/download/
[Gitlab CI]: https://about.gitlab.com/features/gitlab-ci-cd/
