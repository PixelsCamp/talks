Memory Corruption Defenses: Past, Present, Future
========================

* Speaker   : Federico Bento
* Length    : 30-40 minutes
* Language  : Portuguese/English

Description
-----------

Network servers are under constant threat by attackers
who use maliciously crafted packets to exploit software bugs
and gain unauthorized control. In spite of significant research
addressing the underlying causes of software vulnerabilities,
such attacks remain one of the largest problems
in the security field. An arms race has developed between
increasingly sophisticated attacks and their corresponding
defenses.

Attackers have developed innovative ways to defeat most of the common 
defenses to date on modern systems. For example,
stack canaries (SSP) assume a linear stack-based buffer overflow; non-executable
memory (NX/DEP/W^X) assumes code injection; 
address space layout randomization (ASLR) assumes that information cannot be leaked.

In todays world, Return-oriented programming (ROP) has become the primary exploitation technique for
system compromise in the presence of non-executable page protections. ROP exploits are
facilitated mainly by the lack of complete address space randomization coverage or the presence
of memory disclosure vulnerabilities, necessitating additional ROP-specific mitigations.

In this talk I will present the current situation of all exploitation techniques 
(code injection attacks, code-reuse attacks (ROP/JOP), data-only attacks), their defenses 
and actual ongoing research on creating these defenses, and finally my own idea 
and implementation on combating code-reuse attacks on modern systems.

Video
-----

[![Video](https://img.youtube.com/vi/xWBAXBCq6Qo/maxresdefault.jpg)](https://www.youtube.com/watch?v=xWBAXBCq6Qo)

_Click the thumbnail above to watch the video from this talk on Youtube_

Speaker Bio
-----------

![Speaker Image](https://github.com/PixelsCamp/pixels_camp_2016_talks/blob/master/img/federico_bento.jpg?raw=true)

My name is Federico Bento, 20 years old, and a college student from Faculty of Science University of Porto.

I'm your average Computer & Network Security ninja, *BSD admin stuck in a 
GNU/Linux (insert philosophy here) world, wear multiple hats, and also do 
whatever it needs to be done, including Windows (and I don't solely mean the operating system). 

Jokes aside, I breathe security, love to break it and highly respect manual penetration testing. 
I have been fortunate enough to learn from many individuals in this industry, but i'm mostly self-taught.

Found a couple of bugs here and there, such as:

CVE-2016-2568
http://www.openwall.com/lists/oss-security/2016/02/25/6
http://www.openwall.com/lists/oss-security/2016/02/26/3

CVE-2016-2779
http://www.openwall.com/lists/oss-security/2016/02/27/1
http://www.openwall.com/lists/oss-security/2016/02/27/2

Bugtraq ID 71819/OSVDB ID 116517
http://seclists.org/fulldisclosure/2014/Dec/126 
http://www.securityfocus.com/bid/71819
http://osvdb.org/show/osvdb/116517

OSVDB ID 120995
http://osvdb.org/show/osvdb/120995

Bugtraq ID 74836
http://www.securityfocus.com/bid/74836/discuss
http://openwall.com/lists/oss-security/2015/05/26/10 

Last one is particularly funny, as I've proven, during the discussion, 
Stephane Chazelas (the man who discovered shellshock) wrong about a bash feature known as privmode. 
Tavis Ormandy (if you work in security and don't know him, you probably should) came to rescue 
and told him he was wrong. Tavis is a real inspiration to me and not over is head like most "security pros". 
Discussion is here:
http://seclists.org/oss-sec/2015/q2/566

Author of the article "s/party/hack/ like it's 1999", exposing underrated and dangerous terminal escape sequences
http://openwall.com/lists/oss-security/2015/09/17/5

Had an influence in the creation of grsecurity's HARDEN_TTY feature that prevents TIOCSTI ioctl attacks 
for unprivileged users.

You're probably running some code of mine without even knowing, contributed to bash to harden itself 
from privilege escalation attacks targeting bogus SUID binaries that use system()/popen() by abusing SHELLOPTS+PS4

My dream is to one day become a professional security engineer, slash security architect,
slash security antagonizer and be a part of a red team ;)

Nothing more to add, just that I am
''=~('(?{'.('[_).]^'^'+-@@)~').'"'.(']@@^,[[]^[@_^[@+_'^')//~@>>)~=/-~"/^}').',$/})')

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
