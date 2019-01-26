---
name:   JARDS
logo:   "../img/logos/jards.png"
anchor: jards
lang:   "PHP, JavaScript"
tools:  "Apache, Jenkins, Selenium, Composer"
link:   "https://application.fz-juelich.de/review"
---
Web application for proposals and reviews of compute time projects at supercomputing centres.
It allows to handle workflows for the three major phases of compute time projects: 
application, review and conduction phase.
Scientists submit proposals through flexibly configurable web forms. Based on a complex role system
technical and scientific reviewers are assigned, who can assess the proposals and suggest allocations
of compute time. Approved proposals are finally forwarded to the HPC system administration for 
deploying the projects on the supercomputers. This software makes heavy use of
relational databases. JavaScript implements client-side dynamic functions for tables, tooltips and 
input suggestions. Unit and integration tests are triggered via Jenkins, which ensures code
quality and security throughout the iterative development between 2014 and 2019.