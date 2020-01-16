Sandboxing in Linux with zero lines of code
=================================================

* Speaker   : **Ignat Korchagin**
* Available : **any day**
* Length    : **60 minutes**
* Language  : **English**

Description
-----------

Linux seccomp is a simple, yet powerful tool to sandbox running processes and significantly decrease the application attack surface. But to utilise this framework application developers have to explicitly add sandboxing code to their projects and developers usually don’t do it as their main focus is the functionality of the code rather than security. This presentation discusses ways of adding seccomp support to any application (even proprietary one) without writing a single line of code.

Speaker Bio
-----------

Ignat is a security engineer at Cloudflare working mostly on platform and hardware security. Ignat’s interests are cryptography, hacking, and low-level programming. Before Cloudflare, Ignat worked as a senior security engineer for Samsung Electronics’ Mobile Communications Division. His solutions may be found in many older Samsung smart phones and tablets. Ignat started his career as a security researcher in the Ukrainian government’s communications services.

Links
-----

* Blog: https://pqsec.org/
* Company: https://www.cloudflare.com/
* GitHub: https://github.com/ignatk
* Photo: https://hacktivity.com/wp-content/uploads/2019/07/ignat_profile-390x390.jpg

Extra Information
-----------------

Extended abstract:

Linux seccomp is a simple, yet powerful tool to sandbox running processes and significantly decrease potential damage in case the application code gets exploited. It provides fine-grained controls for the process to declare what it can and can’t do in advance and in most cases has zero performance overhead.

The only disadvantage - to utilise this framework, application developers have to explicitly add sandboxing code to their projects and developers usually either delay this or omit completely as their main focus is mostly on the functionality of the code rather than security. Moreover, seccomp security model is based around system calls, but many developers, writing their code in high-level programming languages and frameworks, either have little knowledge to no experience with syscalls or just don’t have easy to use seccomp abstractions or libraries for their frameworks.

All this makes seccomp not that widely adopted, but what if there was a way to easily sandbox any application in any programming language without writing a single line of code? This presentation discusses potential approaches and their pros and cons.

Some talks:

* Go as a scripting language in Linux: https://youtu.be/k7oosn5HrKk
* Live-Patching Weak Crypto with OpenSSL Engines: https://youtu.be/QJtiOhPEjtU
* The Definitive Guide to Make Software Fail on ARM64: https://youtu.be/ZhIxQY-WwgQ
* Exploiting USB/IP: https://youtu.be/EjYKF-xG_VY
