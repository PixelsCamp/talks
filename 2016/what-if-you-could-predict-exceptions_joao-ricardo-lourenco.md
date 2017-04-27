What if you could predict exceptions?
========================

* Speaker   : João Ricardo Lourenço
* Length    : 30 minutes
* Language  : English (or Portuguese, it doesn't really matter, though English is the current priority)

Description
-----------

We've all heard about exceptions: most modern languages and frameworks have the exception handling mechanism in one way or another. Some of these languages change the synctatic characteristics or introduce slightly new semantics to exception handling mechanisms. For example, the Swift programming language has added interesting ways of performing specific resource cleanup using the _defer_ keyword. However, all modern exception handling mechanisms act on a base (perhaps flawed) premise: you can only react to an exception after it has happened. But **what if you could predict exceptions**?

In this talk, I will introduce a new exception model developed as part of my thesis, called **PreX -- Preventive Exception Handling**. This model defies the current preconception that you can only react to exceptions. Imagine the possibilities if you can predict an exception and act on this prediction: **you no longer write `try-catch` blocks, but, instead, write `try-prevent-catch` blocks where a specific action for a _potential_ exception can be written**. I will detail the model, its current implementation and how it compares to current revitalization strategies in our experiments. In the end, perhaps this will help you think "outside the box" when it comes to exceptions -- perhaps you don't really always have to just _handle_ them, you might be able to _prevent_ them.

Video
-----

[![Video](https://img.youtube.com/vi/6tH26mS2-OE/maxresdefault.jpg)](https://www.youtube.com/watch?v=6tH26mS2-OE)

_Click the thumbnail above to watch the video from this talk on Youtube_

Speaker Bio
-----------

![Speaker Image](https://avatars2.githubusercontent.com/u/1668225?v=3&s=400)

My name is João Ricardo Lourenço and I'm 23 years old. I finished my BSc in Computer Science ("Engenharia Informática") in 2014 and finished my MSc in Computer Science this year (2016), both in the University of Coimbra. My thesis involved the proposal, implementation and validation of a new preventive exception handling model (the theme of this talk), and was graded 20/20. I have been working as a researcher for the University of Coimbra (as a member of CISUC - Center for Informatics and Systems of the University of Coimbra) since 2012, having published several papers in the area of NoSQL databases and exception handling. I have also been an invited assistant teacher for the "Acertar o Rumo" programme for two years, where I tutored several students in basic programming skills and advanced Java Enterprise topics such as JPA, EJBs or JSF. I've been awarded several prizes and scolarships throughout my academic career.

My interests are varied and, at times, a bit eccentric. I love working with low-level programming, and have had several "personal operating systems from scratch" projects. I want to know everything I can about compilers, standard libraries, distributed systems, kernel development -- basically whatever allows me to understand the most about whatever is going on in these magical machines. My "impossible" dream is to one day browse the internet in my own web browser, in my own operating system written in my own language running on my own CPU architecture -- because why the heck not? This does not mean that I don't also like to look at things from "the big picture" and work from a more high-level architectural perspective on new software. I'm not a big fan of frontend work, though.

I originally started my masters in the area of "Intelligent Systems", working with evolutionary computation and data mining topics, although I eventually decided to "mix things up" with topics from "Software Engineering". I enjoy coding as much as I can (and, although my Github profile lacks much activity, you can somewhat get that just by looking through it). I was one of the leading developers of the "Inforestudante Mobile" official application for the University of Coimbra (a project we developed during one semester). Often, I distract myself by getting obsessed with a new topic and trying (and failing in comedic fashion) to learn all I can about it. I guess I'm just mad about everything computer science related. I started coding in C++ a long time ago, but I must admit that modern C++ is not anywhere near what it was when I started learning -- nowadays I code in whatever is needed, but mostly Java or Python. Have I mentioned I love Python? Yeah, I love Python.

All in all, I just want to have fun and share whatever knowledge I can. Computer Science is fun. Computers are fun. Programming languages are fun. Making software is fun! :)


Links
-----

* Github: http://github.com/Jorl17
* Contact: jorl17.8 at gmail.com

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
