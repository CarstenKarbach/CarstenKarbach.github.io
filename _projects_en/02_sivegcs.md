---
name:   SiVeGCS
logo:   "../img/logos/sivegcs.png"
anchor: sivegcs
lang:   "PHP, JavaScript"
tools:  "Apache, REST-API, Silex, Docker"
link:   "https://jards.gauss-centre.eu/gcshome"
---
Evolution of JARDS for common usage of a single installation among the three GCS centres.
Based on a comprehensive requirements analysis at major German 
HPC centres, User Stories about their processes and use cases are collected. In an agile workflow
these are evaluated, prioritised and implemented in JARDS. The implemented architecture hosts
REST-APIs for sending real-time events happening on the central web server as well as database 
interfaces for bidirectional information exchange between JARDS and local HPC administrations.
New user interfaces make use of Symfony, Silex, Composer and Bootstrap. Containerisation with 
Docker is evaluated and by relying on PDO the database back-end can be quickly exchanged.