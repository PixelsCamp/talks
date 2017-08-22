High Availability Architecture for Legacy Stuff - a 10.000 feet overview
========================

* Speaker   : Marco Amado
* Length    : 30 to 45 minutes
* Language  : (foreigners === 0) ? Portuguese : English

Description
-----------

So, you have that product that no one cared about for years, chugging along on
a shared hosting. Good ol' LAMP stack, PHP stuck on 5.6, two years ago you even
updated MySQL to MariaDB. Twenty clients a day, no biggie.

Suddenly, with no apparent reason, there are 200 visits on a single day. The
next day, 2000. The hoster emails you frantically (hey, at least he didn't just
cut your hosting). You cave and upgrade for a VPS. The next day, you have 20
visits - per second. At the end of the week, 100. You go for a quad-core, 16GiB
private server. The visits keep climbing, and next is a dual octa-core Xeons,
64GiB. You realize you're getting to a point where a 10% improvement costs you
50% more. This should be rewritten into a high-availability, load-balanced,
multi-machine setup. Maybe in a shiny new stack, to the likes of MEAN,
something with Rails or even Elixir, like that new product that you launched a
few months back.

However...

Do you really have the time? That new product is already requiring so much of
your time. And, of course, even if you *did* have the time, what would you do
while rewriting? Just let some of the clients out in the cold?

Fret not. If there's a will, there's a way. In this talk, I'll give you an
overview of the tools and tricks you could use to turn that big pile of...
Apache, PHP, and MariaDB into an awesome high-availability, load balanced,
shiny new pile of... Apache, PHP, and MariaDB. Zero, or almost zero changes to
the codebase.

This won't be in any way a full blown guide, nor a best practices showcase. One
could make the exact opposite point - this shouldn't be done, at all.
Sometimes, the need arises unexpectedly, and it's not whether it *should* be
done, but whether if there's any other solution.

Speaker Bio
-----------

**Marco Amado**

![Speaker Image](https://github.com/PixelsCamp/talks/blob/master/img/marcoamado.jpg?raw=true)

Started programming at age 6, when I inherited a ZX Spectrum from my older
brother, along the gigantic polycopied ZX BASIC manual that came along back in
the day. I've been there when EGA was a thing, my all-time favorite OS is
Windows for Workgroups 3.11, and my dad yelled at me to shut the computer down
because he wanted to call my grandma.

I've been a developer professionally for more than ten years, ranging from
fullstack web, to desktop and mobile applications (all of it at the same time).
It saddens me to say that LAMP stacks have been the bulk of my professional
work, which qualifies me to this talk, and organizing group therapy for
shellshocked web developers.

Links
-----

* Blog: [DreamsInCode](http://www.dreamsincode.com/)
* Company: [Moloni - Cloud Business Tools](https://www.moloni.com/)
* Github: [:octocat:/mjamado](http://github.com/mjamado)

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
