A Brief Overview of systemd
===========================

* Speaker   : [Carlos Rodrigues](https://pixels.camp/carlosefr)
* Length    : 45 minutes
* Language  : Portuguese

Description
-----------

For the last few years, `systemd` has been making its way into every major Linux distribution, displacing both the old SysV `init` as well as more recent alternatives such as `upstart`. Despite the limitations of previous init systems and the clear need for improvements in this area, `systemd` is one of the most reviled pieces of software in the open-source world, sometimes for good reason but, more often than not, just as a knee-jerk reaction to change.

The purpose of this talk is to go through some of the most relevant `systemd` features, and the pain points they solve, while busting some myths (and confirming others) along the way. It's targeted both at people that manage and troubleshoot systems, as well as people that develop software that eventually needs to be managed somehow.

Some topics that may (or may not) find their way into this talk:

  * The (external) architecture of `systemd` (eg. what "PID 1" does and doesn't do);
  * How `systemd` boots your system (eg. how it differs from previous alternatives);
  * Writing service units from scratch (for traditional services as well as containers);
  * Local customizations for existing service units;
  * System resource management (eg. cgroups and slices);
  * Security / sandboxing features for traditional services;
  * System troubleshooting (eg. the journal).

Speaker Bio
-----------

**Carlos Rodrigues**

![Speaker Image](https://avatars2.githubusercontent.com/u/937276?v=3&s=400)

For the past 14 years I've been a systems administrator and a software developer, both in the academic and corporate worlds, working with proprietary and open-source technologies on meaningless and critical systems (and applications) with various degrees of complexity and scale. I've run with scissors and broken things in production.

Links
-----

* Blog: https://medium.com/@carlosefr
* Company: https://brpx.com
* Github: https://github.com/carlosefr

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
