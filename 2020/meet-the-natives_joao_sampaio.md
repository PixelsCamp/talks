Meet the natives: from compilation to execution
=================================================

* Speaker   : [João Sampaio](https://pixels.camp/jsmp)
* Length    : 60m
* Language  : English

Description
-----------

Before your favorite Operating System can load and execute a program there are a few extra steps left after compilation. This is true no matter what the programming language is. Follow a native program and see how it is prepared and loaded for execution. In the end, things should appear less voodoo and more magical.

A native program as seen by the author is one that is loaded to run on the local processor and interfaces directly with the operating system.

Speaker Bio
-----------

**João Sampaio**

![João Sampaio](https://avatars0.githubusercontent.com/u/365809?v=4)

Software engineer at Talkdesk on the Mobile Team shipping native code.

C practitioner, iOS/macOS/Web Developer and FreeBSD afficionado, compiler enthusiast, husband and father of two awesome girls.

Links
-----

* Blog: https://jsmp.me
* Company: https://www.talkdesk.com
* GitHub: https://github.com/jsmp
* Photo: https://avatars0.githubusercontent.com/u/365809?s=460&v=4

Extra Information
-----------------

The talk should start by using different languages (eg: Asm, C, Swift and Rust) to build a single binary, by compiling them into object files, and then going into explaning how linking works to stitch the object files into a single binary. Asm (with nasm) will be used to expain calling conventions and how magling works, and avoid the trickery of just producing an IR or leveraging the fact that most of these languages have a frontend to a common backend (eg: LLVM). Still some references might be done to Link time Optimization done by llvm-ld.

After this, two topics are left, first how the OS loads the executable (eg: ELF for Linux and FreeBSD, Mach-O for macOS and iOS) and what these file formats try to archive. Loading is a complex step and its explanation should be shallow (eg: no dynamic lynking), but still cover some tricks one can play with (eg: forcing the OS to load a different library). What about Interpreters?

If both FreeBSD and Linux uses ELF what makes a Linux binary different from a FreeBSD one? How do they interact with the operating system? In the case of FreeBSD there is a compatibily layer that enables one to run linux binaries.

While Linking, Loading and Executing are the main topics, and the main arhictecture used here is x86_64, arm will also be addressed (eg: Bit code on the AppStore). The talk will focus on UNIX based operating systems mainly macOS and FreeBSD (with Linux as a special guest).

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
