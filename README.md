# Modul 165

KompetenzStufen
===============

Grundlagen | Stufe 1
-------------------

Diese Stufe ist als Einstieg ins Thema gedacht. Der Fokus liegt hier auf dem Verstehen von Begriffen und Zusammenhängen.

*Als Richtungshinweis: Wer alle Kompetenzen in dieser Stufe erfüllt, hat die Noten 3.0.*

Fortgeschritten | Stufe 2
------------------------

Diese Stufe definiert den Pflichtstoff, den alle Lernenden am Ende des Moduls möglichst beherrschen sollen.

*Als Richtungshinweis: Wer alle Kompetenzen in dieser Stufe erfüllt, hat die Noten 4.5*

Experte | Stufe 3

Diese Lerninhalte für Lernende gedacht, die schneller vorankommen und einen zusätzlichen Lernanreiz erhalten sollen.

*Als Richtungshinweis: Wer alle Kompetenzen in dieser Stufe erfüllt, hat die Noten 6*

Fragenkatolog
=============

Link zum [Fragenkatalog](url)

## NoSQL Grundlagen

[Wikipedia](https://de.wikipedia.org/wiki/NoSQL)

NoSQL (englisch für Not only SQL deutsch: „Nicht nur SQL“) bezeichnet Datenbanken, die einen nicht-relationalen Ansatz verfolgen und damit mit der langen Geschichte relationaler Datenbanken brechen. Diese Datenspeicher benötigen keine festgelegten Tabellenschemata und versuchen Joins zu vermeiden. Sie skalieren dabei horizontal. Im akademischen Umfeld werden sie häufig als „strukturierte Datenspeicher“ (engl. structured storage) bezeichnet.

Bekannte Implementierungen sind Riak, Apache Cassandra, CouchDB, MongoDB und Redis. 

### A1G

>Ich kann Begriffe und Konzepte der NoSQL Datenbanken erläutern. (z. B. CAP-Theorem, BASE, ACID, Indexing Strukturen, Caching, Datenanalyse, Datawarehouse, FullText Search, Netzwerke, Testing).

Fragenstellung und Lernziele
==============

- Was sind die Grundbegriffe von NoSQL Datenbanken?

- Ich kann die Grundbegriffe und Konzepte von NoSQL Datenbanken erläutern.
- Ich erstelle eine Liste von Begriffen und Konzepten von NoSQL Datenbanken.

Umsetzung
=========

Grundbegriffe
-------------------

**BASE**

BASE beschreibt die Eigenschaften von NoSQL Datenbanken. Das Akronym steht für:

+ Basically Available: Die Datenbank ist immer verfügbar, auch wenn sie nicht konsistent ist.
+ Soft State: Der Zustand der Datenbank kann sich im Laufe der Zeit ändern.
+ Eventually Consistent: Die Datenbank wird schließlich konsistent, auch wenn sie es nicht sofort ist.

**ACID**

ACID beschreibt die Eigenschaften von Transaktionen in relationalen Datenbanken. Das Akronym steht für:

+ Atomicity: Alle Operationen einer Transaktion werden entweder vollständig ausgeführt oder gar nicht.
+ Consistency: Die Datenbank befind
+ Isolation: Transaktionen werden unabhängig voneinander ausgeführt.
+ Durability: Änderungen an der Datenbank werden dauerhaft gespeichert.

**CAP-Theorem**

![theorem](/images/CAP_Theorem.png)

Das CAP-Theorem besagt, dass eine verteilte Datenbank nicht gleichzeitig Konsistenz, Verfügbarkeit und Partitionstoleranz gewährleisten kann. Es besagt, dass in einem verteilten System nur zwei der drei Eigenschaften gleichzeitig garantiert werden können.

Weitere Begriffe
====================

| Begriff       | Beschreibung                                                                 | Beispiele       |
| :------------ | :--------------------------------------------------------------------------- | :-------------- |
| Indexing Strukturen | Indexe sind Datenstrukturen, die den Zugriff auf Daten beschleunigen. | B-Bäume, Hash-Indexe |
| Caching       | Caching ist eine Technik, bei der häufig benötigte Daten zwischen gespeichert werden, um den Zugriff zu beschleunigen. | Redis, Memcached |
| Datenanalyse  | Datenanalyse ist die Untersuchung von Daten, um Muster, Trends und Informationen zu erkennen. | Hadoop, Spark |
| Datawarehouse | Ein Datawarehouse ist eine zentrale Datenbank, in der Daten aus verschiedenen Quellen zusammengeführt und analysiert werden. | Amazon Redshift, Google BigQuery |
| FullText Search | Eine Volltextsuche ist eine Suchfunktion, die es ermöglicht, in Texten nach Wörtern oder Wortteilen zu suchen. | Elasticsearch, Solr |
| Netzwerke     | Ein Netzwerk ist eine Verbindung von mehreren Rechnern, die miteinander kommunizieren können. | TCP/IP, HTTP |
| Testing       | Testing ist der Prozess, bei dem Software auf Fehler und Probleme überprüft wird. | Unit-Tests, Integrationstests |

Vertiefte Begriffe
====================

| Begriff       | Beschreibung                                                                 | Beispiele       |
| :------------ | :--------------------------------------------------------------------------- | :-------------- |
| Sharding     | Eine Methode zur horizontalen Partitionierung von Datenbanken, bei der Daten auf mehrere Server verteilt werden, um die Last zu verteilen und die Leistung zu verbessern. | MongoDB, Cassandra |
| Replikation  | Die Erstellung und Aufrechterhaltung von Kopien von Daten, um die Verfügbarkeit und Zuverlässigkeit zu verbessern. | MySQL, PostgreSQL |
| Document Store | Eine NoSQL-Datenbank, die Dokumente als Datenspeicher verwendet. | MongoDB, CouchDB |
| Key-Value Store | Eine NoSQL-Datenbank, die Daten in Form von Schlüssel-Wert-Paaren speichert. | Redis, Memcached |
| Column-Family Store | Eine NoSQL-Datenbank, die Daten in Form von Spaltenfamilien speichert. | Cassandra, HBase |
| Graph-Datenbank | Eine NoSQL-Datenbank, die Daten in Form von Graphen speichert. | Neo4j, ArangoDB |
| Schema-less | Eine Eigenschaft von NoSQL-Datenbanken, bei der es keine festen Tabellenschemata gibt. | MongoDB, CouchDB |
| Polyglot Persistence | Die Verwendung mehrerer Datenbanken für unterschiedliche Anwendungsfälle. | MongoDB, Cassandra |
| Consistency Models | Modelle, die beschreiben, wie konsistent Daten in einem verteilten System sein können. | Eventual Consistency, Strong Consistency |

Nachweis
========

> [Quizlet](https://quizlet.com/ch/999306801/nosql-grundlagen-begriff-flash-cards/?funnelUUID=d8ff1b91-b5a4-4c9e-aee5-a8512ebab0d0)


### A1F

> Ich kann eine NoSQL Datenbank gezielt für eine spezifische Anwendung auswählen. (z. B. Document Store für Videos)

Fragenstellung und Lernziele
==============

- Was sind die Anwendungsfälle für NoSQL Datenbanken?
- Wann brauche ich eine NoSQL Datenbank?
- Welche NoSQL Datenbanken eignen sich für welche Anwendungsfälle?
- Ich kenne die Vor- und Nachteile von NoSQL Datenbanken.
- Ich kann 3 NoSQL Datenbanken nennen und ihre Anwendungsfälle erläutern.

Umsetzung
=========

Was sind die Anwendungsfälle für NoSQL Datenbanken?
---------------------------------------------------

- Big Data
- Echtzeit-Analyse
- Hochverfügbarkeit
- Skalierbarkeit
- Unstrukturierte Daten

Wann brauche ich eine NoSQL Datenbank?
--------------------------------------

- Wenn die Datenmenge zu gross für eine relationale Datenbank ist
- Wenn die Datenstruktur nicht festgelegt ist
- Wenn die Daten schnell verarbeitet werden müssen
- Wenn die Daten über mehrere Server verteilt werden müssen


Welche NoSQL Datenbanken eignen sich für welche Anwendungsfälle?
---------------------------------------------------------------

**Document Store**

 Eignet sich für Anwendungen, bei denen die Daten in Form von Dokumenten gespeichert werden sollen.

**Key-Value Store**

Eignet sich für Anwendungen, bei denen die Daten in Form von Schlüssel-Wert-Paaren gespeichert werden sollen.

**Column-Family Store**

Eignet sich für Anwendungen, bei denen die Daten in Form von Spaltenfamilien gespeichert werden sollen.

**Graph-Datenbank**

Eignet sich für Anwendungen, bei denen die Daten in Form von Graphen gespeichert werden sollen.

Welche NoSQL Datenbanken gibt es?
---------------------------------

| Anwendungsfall   | Datenbank   |
| :--------- | :--------- |
| Document Store     | MongoDB, CouchDB     |
| Key-Value Store     | Redis, Memcached     |
| Column-Family Store     | Cassandra, HBase     |
| Graph-Datenbank     | Neo4j, ArangoDB     |


Welche Vor- und Nachteile haben NoSQL Datenbanken?
-------------------------------------------------


| Vorteil   | Beschreibung   |
| :--------- | :--------- |
| Skalierbarkeit     | NoSQL-Datenbanken können horizontal skalieren, d. h. sie können auf mehrere Server verteilt werden, um die Last zu verteilen und die Leistung zu verbessern.     |
| Flexibilität     | NoSQL-Datenbanken haben kein festes Tabellenschema, was es ermöglicht, die Datenstruktur flexibel anzupassen.     |
| Hochverfügbarkeit     | NoSQL-Datenbanken können Replikation und Sharding verwenden, um die Verfügbarkeit der Daten zu verbessern.     |


| Nachteil   | Beschreibung  |
| :--------- | :--------- |
| Konsistenz     | NoSQL-Datenbanken können Eventual Consistency verwenden, was bedeutet, dass es keine Garantie gibt, dass alle Kopien von Daten in einem verteilten System sofort konsistent sind.No     |
| Komplexität     | NoSQL-Datenbanken können komplexer zu konfigurieren und zu verwalten sein als relationale Datenbanken.     |
| Mangelnde Unterstützung     | NoSQL-Datenbanken haben möglicherweise nicht die gleiche Unterstützung und Tools wie relationale Datenbanken.     |

Quellen
-------

> - [MongoDB](https://www.mongodb.com/nosql-explained)
> - [CouchDB](https://couchdb.apache.org/)
> - [Redis](https://redis.io/)
> - [Memcached](https://memcached.org/)
> - [FireShip Video](https://www.youtube.com/watch?v=W2Z7fbCLSTw)


Nachweis
========

### A1E

> Ich kann den Einsatz einer NoSQL Datenbank kritisch hinterfragen und Verbesserungen vorschlagen.

Fragenstellung und Lernziele
==============

- Wie kann ich den Einsatz einer NoSQL Datenbank kritisch hinterfragen?
- Welche Verbesserungen kann ich vorschlagen?

Umsetzung
=========

Nachweis
========

## NoSQL Datenbanken implementieren

### B1G

> Ich kann ein Datenmodell für eine NoSQL Datenbank interpretieren und erläutern.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### B1F

> Ich kann ein vorgegebenes Datenmodell mit einer NoSQL Datenbank umsetzen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### B1E

> Ich kann ein Datenmodell für eine NoSQL Datenbank entwerfen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

## Daten in NoSQL Datenbank eintragen

### C1G

> Ich kann die Struktur von Daten in einer NoSQL Datenbank erläutern.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### C1F

> Ich kann Daten in eine NoSQL Datenbank übernehmen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### C1E

> Ich kann Probleme bei der Übernahme von Daten in eine NoSQL Datenbank erkennen und Lösungen aufzeigen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

## Zugriffberechtigungen anwednen

### D1G

> Ich kann die Funktion von Zugriffsberechtigungen in einer NoSQL Datenbank erläutern. (Benutzer, Rollen, Zugriffsrechte)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### D1F

> Ich kann vordefinierte Zugriffsberechtigungen in einer NoSQL Datenbank umsetzen. (z. B. Rollen)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### D1E

> Ich kann ein Konzept für Zugriffsberechtigungen einer NoSQL Datenbank entwerfen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

## Backup erstellen Restore durchführen

### E1G

> Ich kann Konzepte für ein Backup einer NoSQL Datenbank erläutern. (z. B. on-demand snapshots, continous cloud backups, legacy backups)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### E1F

> Ich kann ein Backup und Restore bei einer NoSQL Datenbank anwenden.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### E1E

> Ich kann ein Konzept für das Backup einer NoSQL Datenbank erstellen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

## Skalierung und Replikation bei einer NoSQL Datenbank anwenden

### F1G

> Ich kann das Prinzip der Skalierung und die unterschiedlichen Replikationsarten für eine NoSQL Datenbank erläutern. (z. B. Multimaster, primary and replica, Aktiv-Passiv und horizontale Skalierung)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### F1F

> Ich kann für eine NoSQL Datenbank eine Replikation anwenden.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### F1E

> Ich kann ein Konzept für die Skalierung einer NoSQL Datenbank erstellen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

## Anbindung an NoSQL Datenbank erstellen

### G1G

> Ich kann das Prinzip des Zugriffes bei einer NoSQL Datenbank erläutern. (z. B. Queries, Projections)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### G1F

> Ich kann eine Anbindung an eine NoSQL Datenbank implementieren. (z. B. API)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

### G1E

> Ich kann das Prinzip der parallelen Verarbeitung bei NoSQL Datenbanken anwenden. (z. B. MapReduce Algorithmen)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========