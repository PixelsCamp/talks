How to Build a Reliable Checkout Experience
========================

* Speaker   : Pedro Teixeira
* Available : October 6th, 7th and 8th
* Length    : 30 mins
* Language  : English

Description
-----------

The checkout experience is usually the one part of the application that delivers the most value, but unfortunately, it's the one that usually contains the most friction. We've all been victims of this: a checkout experience that has spinner that spins indefinitely, or one that warns you to not move a muscle while the next page is loading, or even one that makes a double reservation.

Now that you have your shiny new micro-services architecture running and you're able to deploy new features and fixes several times a day, how do you deliver complex transactions to your customers? How do you deliver payments, trip reservations or purchasing an entire shopping cart with a good user experience?

HTTP has taken us far, but it's probably not the best transport to deliver complex transactions like these, specially when these transactions are performed over flaky mobile networks. A lot of error-handling logic must fall on the client: How does the client react to timeouts? Or gateway problems? Can it assume the transaction failed with no fear of duplication? Can the transaction survive client crashes? Can the client solve all these existing edge cases without making it overly complex and bug-prone?

This talk proposes an original architecture style that will sit in front of your micro-service stack and that you can attach to any existing service back-end. The author will show an implementation of this architecture pattern: a proof-of-concept application and a set of client and server open-source libraries built on top of PouchDB, and Node.js.


---------------

Speaker Bio
-----------

Pedro is Chief Futurist at YLD. His role involves exploring new technologies that can help address customers’ issues and ensuring this knowledge is shared within YLD. Pedro first taught himself how to program on a 48K ZX Spectrum when he was only 9 years old. When he’s not saving the world from bad software design he plays guitar and drums. 

Links
-----

* Blog: http://blog.yld.io/author/pedro/
* Company: http://yld.io
* Github: http://github.com/pgte