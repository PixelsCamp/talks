Everyone is naked: attacking the DHT
=========================

* Speaker   : Goncalo Pestana
* Available : Any time
* Length    : 45m + QA
* Language  : English

Description
-----------

Distributed Hash Table (DHT) is an important primitive which allows network
peers to collaboratively store and retrieve data in a decentralized
network. Nowadays, millions of users are using services which rely on DHTs:
Bittorrent, IPFS, Freenet, Ethereum are some examples of networks which use
DHTs. As the Web 3.0 ecosystem becomes mainstream, the number of systems relying 
on DHTs are expected to increase.

However, naive implementations of DHTs leak critical information about user behavior 
and user metadata (e.g. who is storing and retrieving specific files in the network). 
In a DHT network, it is trivial for adversaries to collect network information 
that can be correlated to understand what the users are up to. The data leaked 
can used for mass surveillance, censorship and privacy attacks on DHT users and
services.

As P2P networks and decentralized systems (re)gain popularity among researchers
and industry alike, it is important to design and implement decentralized 
systems that preserve users’ privacy. Failing to deliver on this will render 
decentralized systems unusable and unattractive for mass adoption or as a viable
alternative to centralized systems.

In this talk, our goals are to learn what DHTs, how they are used and how to
improve privacy of existent designs. We first dive into what are DHTs, how they 
work and its privacy
vulnerabilities. After motivating the reasons of why privacy preserving networks
are important for the future the internet and society, we'll perform a
live privacy attack on a public DHT. We will see how easy it is to collect and
correlate public activity in DHTs and try to understand its consequences from an
user perspective. We wrap up by going through some mechanisms and protocols used
to harden privacy in DHTs based on the latest research, such as onion routing,
friend-to-friend routing, and others.

Speaker Bio
-----------

engineer and researcher at hashmatter, focusing primarily on metadata resistance
systems, networking and decentralization


Links
-----

* Blog: https://gpestana.com
* Company: https://hashmatter.com
* GitHub: https://github.com/gpestana

