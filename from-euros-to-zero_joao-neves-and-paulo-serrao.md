* Replace all text within `{{ ... }}` (also removing the braces) with the proper information.
* This file will be automatically parsed by our backoffice, all fields are mandatory unless stated otherwise.
* Don't use any markup or emoji in titles. Try to avoid it in descriptions if you can.
* When you submit your proposal, paste the contents of this file as the Pull Request's description.
* Don't delete or rename this file, copy it.

`--8<-- DO NOT FORGET TO DELETE THIS LINE AND EVERYTHING ABOVE IT BEFORE SUBMITTING YOUR PROPOSAL --8<--`

From euros to zero: using Probabilistic Data Structures to reduce costs
=================================================

* Speaker   : João Neves and Paulo Serrão
* Available : first day, second day, third day
* Length    : 30 minutes
* Language  : English

Description
-----------

At Siemens CyberSecurity Center, we provide services to deal with Threat Hunting. One of these services include searching IOCs in the network traffic logs which compose our data lake.

To implement this service, we leveraged AWS Athena, to provide a queryable interface for our data lake. Although, due to the nature and pattern of the queries, this design proved to be
quite expensive. In this talk, we will show how we leveraged the nature of the queries to design a cost effective specialized solution for IOC searching using Probabilistic Data Structures. 

Speaker Bio
-----------

João works at Siemens Cyber Security Center as an ML Engineer since 2018, in Portugal. He has experience as Cloud Engineer and is certified as a Solutions Architect with AWS. Previously, he worked as a Data Engineer Consultant at Marionete and as a Software Engineer in railroad business at Siscog SA. João graduated from University of Lisbon with a Masters in Applied Mathematics. Outside of the Cloud, João enjoys everything related with football and with Benfica.

{{ Paulo Serrão's description }}

Links
-----

* Company: https://new.siemens.com/global/en/company/stories/home/cybersecurity.html
* GitHub: https://github.com/jonsnowseven and https://github.com/paulo-serrao
* Photo:
  * ![Joao Neves](img/Joao%20Neves_short_wback.jpg "Joao Neves")
  * ![Paulo Serrão](img/paulo_serrao.jpg)

Extra Information
-----------------

Cloud business has been (and still is) growing up in the last few years. The Cloud model is very attractive with respect to price (pay as go), flexibility (e.g., spin up and destroy resources as you like) and versatile with a broad range of different services. Nevertheless, Cloud resources must be used wisely on the ground that its pricing model rewards you by good design and punishes you for a poor one.

At Siemens Cybersecurity Center, we leverage Cloud to handle and analyze a huge volume of data to overcome the growth in cyber threats. The amount of ingested log data exceeds the 6 TB per day, and is, on average, scattered over 60k events per second. The data serves a myriad of security uses cases including automated threat detection.

A common use case for automation is looking for Indicators of Compromise (IoC), which are pieces of data posted by Threat Intelligence feeds such as file hashes or registry keys. This information is actionable for security professionals since it may present signs of malicious activity in the systems and as a consequence, the professional can take the appropriate action.

On our infrastructure, the former process used to scan the data lake over and over to look for these indicators of compromise. AWS Athena, service on top of Facebook Presto, was doing the map-reduce heavy lifting of searching in the entire data lake.

As a first solution, it served the purpose seamlessly whereas we could run as many scans as requested and Athena would scale the cluster according to the demand. However, as a drawback, regardless of the query results, these were billed according to the volume of data scanned, a cost that scaled linearly with the number of IOCs and volume of data stored. Looking into other cloud providers solutions, e.g. Google BigQuery, is pointless since the pricing model is identical, hence the incurred cost would be similar. Changing the cloud provider is never the solution, smart engineering is.

This is where Probabilistic Data Structures come to the rescue. These data structures allow checking for membership, count or distinct count information efficiently (speed and space) at the cost of pinpoint accuracy. By rolling out these structures into production, we were able to reduce dramatically the fluctuating costs in the serving layer, and most importantly, break the linearity between data volume and query cost.

In this talk, we will describe how we have evolved the existing solution to an optimized solution leveraging Probabilistic Data Structures. For that, we first walk through the advantages and drawbacks of the former and then, we perform the same analysis for the latter solution. Then we explain what are probabilistic data structures, what are the common use cases for each and, we show the attendees how trivial it is to implement these structures with code samples. In the end, we will describe how these structures enabled us to balance the trade-off between accuracy and costs of the queries of our serving architecture by providing a fuzzy view of our data sources.

Finally, we hope you leave the session with A) a good understanding of PDS and its practical application in real-world scenarios, and B) some bubbling ideas to apply to you big data affairs.
