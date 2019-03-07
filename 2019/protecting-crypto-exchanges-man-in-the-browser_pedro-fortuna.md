Protecting Crypto exchanges from a new wave of man-in-the-browser attacks
=========================

* Speaker   : [Pedro Fortuna](https://www.linkedin.com/in/pedrofortuna/)
* Length    : 45m
* Language  : English

Description
-----------

In the last year or so, we have seen a massive increase in the value of cryptocurrencies and the emergence of hundreds of new coins and ICOs, getting millions of people into an investment frenzy. A lot of them being non-technical regular consumers that rushed to create new accounts in the most popular crypto exchanges like Coinbase or Bitstamp.

Crypto exchanges are naturally appealing for attackers and have been targeted since as long as we can remember. However, since last year, they are also being targeted by Man-in-the-Browser (MITB) attacks. Malware families such as Zeus Panda, Ramnit and Trickbot are already aiming at websites such as Coinbase.com or Blockchain.info.

In this talk, we will detail how these attacks work, from account takeover to moving out the coins to attacker-controlled wallets. We’ll discuss current defenses e.g. multi-factor authentication or strong SSL encryption and why they are failing to mitigate this type of attacks. 

The fact is that unless we can assure that users are not infected with trojans, which right seems an impossible task, we’d better assume a few of them will end up having sessions with web injects.

We’ll demo a new set of techniques that instead of trying to prevent web injections, they aim to detect and react to them.

These techniques, based on our work, rely on a combination of recent browser features (such as Mutation Observers) and the implementation of tamper-resistant integrity checks using a JavaScript agent running in an exchange webpage.

We’ll demo how the integrity of the exchange webpage can be protected even in the presence of a trojan installed on the client device.

We conclude with an evaluation of the effectiveness of this approach and discuss the value that it adds to existing solutions in the mitigation of MITB attacks.

Speaker's Bio
-----------

**Pedro Fortuna**

![Pedro Fortuna](https://avatars2.githubusercontent.com/u/5217265?v=4)

Pedro Fortuna is CTO and Co-Founder of Jscrambler. He is also the Chapter leader for OWASP Portugal.

Pedro has more than 12 years of experience researching and working with web application security area. He is a regular speaker in international security conferences. His main research interests lie in the fields of Application Security, Web Security, Reverse Engineering, Malware and Software Engineering.

Pedro is also the author of several patents in application security.

Links
-----

* Company: https://jscrambler.com/
* GitHub: https://github.com/pfortuna
* Linkedin: https://www.linkedin.com/in/pedrofortuna/

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
