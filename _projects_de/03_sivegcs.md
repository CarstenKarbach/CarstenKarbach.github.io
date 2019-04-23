---
name:   SiVeGCS
logo:   "../img/logos/sivegcs.png"
anchor: sivegcs
lang:   "PHP, JavaScript"
tools:  "Apache, REST-API, Silex, Docker"
link:   "https://jards.gauss-centre.eu/gcshome"
---
Weiterentwicklung von JARDS zur gemeinsamen Nutzung einer Instanz durch die drei GCS-Zentren.
Über eine ausgiebige Anforderungsanalyse werden Prozesse und Nutzungsszenarien an den größten deutschen
Rechenzentren erfasst und in User Stories abgebildet. Diese werden kontinuierlich bewertet, priorisiert
und in JARDS implementiert. Die Architektur der Software umfasst REST-APIs zur Echtzeit-Benachrichtigung
über Ereignisse im System sowie Schnittstellen auf Datenbankebene zum bidirektionalen Datenaustausch zwischen
dem zentralen Server und den lokalen Verwaltungen der Rechenzentren. Bei der Implementierung der 
Nutzerschnittstellen kommen Symfony, Silex, Composer und Bootstrap zum Einsatz. Die Portierbarkeit der Anwendung
wird über Docker und die Kapselung der Datenbankzugriffe über PDO sichergestellt.