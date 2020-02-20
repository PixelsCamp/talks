Building a Flight Tracker
=================================================

* Speaker   : **João Carvalho**
* Available : **Any day**
* Length    : **60 minutes**
* Language  : **English**

Description
-----------

Have you ever wondered how Flight Tracking websites work? I did, so I decided the
best way to learn was to build my own!

In this talk, I'll share my experience, from learning about ADS-B, getting my first
the RTL-SDR dongle and Raspberry Pi, coding a SBS-1 parser and aggregator in
Spring Kofu, and a simple UI to visualize it. All of this, running entirely cloud-free,
and accessible from anywhere in the world, for less than 100 euros.

Speaker Bio
-----------

I'm a Software Engineer at Talkdesk's SRE Team, with a passion for Reliability,
Scalability and Performance.

In my spare time, I enjoy all things aviation (just got into aviation photography),
home automation, self-hosting (I love my homelab!), tinkering with electronics
(just recently started getting into the ESP8266 and I'm still finding new applications
for it every day) and PC building (i.e. gaming).

Links
-----

* Company: https://talkdesk.com
* GitHub: https://github.com/jcarvalho/
* Photo: https://jcarvalho.dev/assets/img/avatar.jpg

Extra Information
-----------------

The idea to build my own flight tracker came to me when I started building my Homelab,
as I started playing around with different technologies (such as XenServer, Docker
Prometheus, Grafana, HomeAssistant, etc). As the Homelab evolved, so did the tracker.
From a simple Node.js API running on the same Raspberry Pi that ran the RTL-SDR dongle,
to a Prometheus exporter that displayed historical ADS-B stats in Grafana, to a Spring
Kofu real-time streaming API (that also allows replaying past messages) powering a UI
that displays surrounding aircraft on a map (all running in a dedicated VM server).

This talk will be a retelling of this story, from the first prototype to the
current version.
