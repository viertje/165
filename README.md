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

- Basically Available: Die Datenbank ist immer verfügbar, auch wenn sie nicht konsistent ist.
- Soft State: Der Zustand der Datenbank kann sich im Laufe der Zeit ändern.
- Eventually Consistent: Die Datenbank wird schliesslich konsistent, auch wenn sie es nicht sofort ist.

**ACID**

ACID beschreibt die Eigenschaften von Transaktionen in relationalen Datenbanken. Das Akronym steht für:

- Atomicity: Alle Operationen einer Transaktion werden entweder vollständig ausgeführt oder gar nicht.
- Consistency: Die Datenbank befind
- Isolation: Transaktionen werden unabhängig voneinander ausgeführt.
- Durability: Änderungen an der Datenbank werden dauerhaft gespeichert.

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

Beispielsweise bei Caching-Anwendungen, bei denen die Daten in Form von Schlüssel-Wert-Paaren gespeichert werden sollen.

**Column-Family Store**

Eignet sich für Anwendungen, bei denen die Daten in Form von Spaltenfamilien gespeichert werden sollen.

**Graph-Datenbank**

Datenbanke mit Graphen können verwendet werden, um Beziehungen zwischen Daten zu speichern.

Welche NoSQL Datenbanken gibt es?
---------------------------------

| Datenbank   | Anwendungsfall   | Databasetype |
| :--------- | :--------- | :--------- |
| MongoDB   | Dokumente speichern     | Document Store |
| CouchDB   | Offline bearbeiten und später synchronisieren   | Document Store |
| Redis   | Cache für schnellen Zugriff auf Daten   | Key-Value Store |
| Memcached   | Speichern von Schlüssel-Wert-Paaren   | Key-Value Store |
| Cassandra   | Speichern von Spaltenfamilien   | Column-Family Store |
| Neo4j   | Speichern von Graphen   | Graph-Datenbank |

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

![databasetype](/images/databaseType.png)

Quellen
-------

> - [MongoDB](https://www.mongodb.com/nosql-explained)
> - [CouchDB](https://couchdb.apache.org/)
> - [Redis](https://redis.io/)
> - [Memcached](https://memcached.org/)
> - [FireShip Video](https://www.youtube.com/watch?v=W2Z7fbCLSTw)

### A1E

> Ich kann den Einsatz einer NoSQL Datenbank kritisch hinterfragen und Verbesserungen vorschlagen.

Fragenstellung und Lernziele
==============

- Wie kann ich den Einsatz einer NoSQL Datenbank kritisch hinterfragen?
- Welche Verbesserungen kann ich vorschlagen?

- Ich kann den Einsatz einer NoSQL Datenbank kritisch hinterfragen.
- Ich kann Verbesserungen für den Einsatz einer NoSQL Datenbank vorschlagen.

Umsetzung
=========

Voraussetzung
-----

Die Voraussetzung für die kritische Hinterfragung des Einsatzes einer NoSQL-Datenbank ist ein **gutes Verständnis** der **Anforderungen** und **Einschränkungen** des Projekts.

Ich muss verstehen, welche **Daten** gespeichert werden und wie sie **verarbeitet** und **abgerufen** werden sollen. Ausserdem muss ich die **Skalierbarkeitsanforderungen** und die **Verfügbarkeit** der Datenbank berücksichtigen.

Wann brauche ich eine NoSQL Datenbank?
--------------------------------------

- Wenn die Datenmenge zu gross für eine relationale Datenbank ist
- Wenn die Datenstruktur nicht festgelegt ist
- Wenn die Daten schnell verarbeitet werden müssen
- Wenn die Daten über mehrere Server verteilt werden müssen

Wann brauche ich keine NoSQL Datenbank?
--------------------------------------

- Wenn die Datenstruktur festgelegt ist
- Wenn die Datenmenge klein ist
- Wenn die Datenbank nur auf einem Server betrieben wird
- Wenn die Datenbank nur für Transaktionen verwendet wird

![nosqlvssql](/images/nosqlVSsql.png)

Verbesserungen vorschlagen
--------------------------

| Verbesserung   | Beschreibung   |
| :--------- | :--------- |
| Optimierung der Datenstruktur     | Item 2Überprüfen, ob die Datenstruktur effizient ist und ob sie die Anforderungen des Projekts erfüllt     |
| Performance-Optimierung     | Überprüfen, ob die Datenbank die erforderliche Leistung erbringt und ob sie optimiert werden kann.     |
| Sicherheitsverbesserungen     | Überprüfen, ob die Datenbank ausreichend geschützt ist und ob zusätzliche Sicherheitsmassnahmen erforderlich sind.     |

Nachweis
========

## NoSQL Datenbanken implementieren

Im Kapitel NoSQL Datenbank implementieren wirst du schrittweise an die praktische Umsetzung von NoSQL-Datenbanken herangeführt.

- Zunächst lernst du, wie du ein bestehendes Datenmodell interpretierst und seine Struktur sowie Funktionsweise in einer NoSQL-Datenbank erläuterst.

- Anschliessend setzt du ein vorgegebenes Datenmodell in einer NoSQL-Datenbank um. Du erfährst, wie du Daten speicherst, abrufst und organisierst, um die Effizienz der Datenverwaltung sicherzustellen.
- Abschliessend entwickelst du eigene Datenmodelle für spezifische Anwendungsfälle. Hierbei lernst du, wie du Daten optimal strukturierst, um Skalierbarkeit, Performance und Anwendungsanforderungen bestmöglich zu unterstützen.

Dieses Kapitel gibt dir das Wissen und die praktischen Fähigkeiten, um NoSQL-Datenbanken effizient in Projekten zu implementieren und anzupassen.

### B1G

> Ich kann ein Datenmodell für eine NoSQL Datenbank interpretieren und erläutern.

Fragenstellung und Lernziele
==============

- Die Struktur eines Dokuments in einer dokumentenorientierten NoSQL-Datenbank verstehen.
- Eingebettete Dokumente und Arrays innerhalb eines Dokuments identifizieren und deren Zweck erläutern.
- Die Unterschiede zwischen dokumentenorientierten NoSQL-Datenbanken und relationalen Datenbanken hinsichtlich der Datenmodellierung beschreiben.
- Die Vorteile der flexiblen Schema-Struktur von NoSQL-Datenbanken für verschiedene Anwendungsfälle bewerten.

Umsetzung
=========

Dokumentenorientierte NoSQL-Datenbanken speichern Daten in einer flexiblen, hierarchischen Struktur. Anstelle von Tabellen mit festen Spalten und Zeilen verwenden sie **Dokumente**, die meist im **JSON-Format** gespeichert werden. Diese Dokumente enthalten verschiedene **Schlüssel-Wert-Paare** und können geschachtelte Strukturen wie **eingebettete Dokumente** und **Arrays** enthalten.

Wichtige Begriffe und Strukturen
---------------------------------------

Um die Struktur einer dokumentenorientierten NoSQL-Datenbank zu verstehen, müssen einige zentrale Konzepte betrachtet werden:

- **📜 Dokument** → Ein einzelner Datensatz, gespeichert als JSON-Objekt mit verschiedenen Attributen.  
- **📂 Collection** → Eine Sammlung von Dokumenten ähnlicher Art, vergleichbar mit einer Tabelle in relationalen Datenbanken.  
- **📎 Eingebettetes Dokument** → Ein Dokument, das innerhalb eines anderen Dokuments gespeichert ist. Dadurch können zusammengehörige Daten direkt in einem Eintrag gespeichert werden.  
- **📑 Array** → Eine Liste von Werten oder Dokumenten innerhalb eines Dokuments. Dies ermöglicht die Speicherung von mehreren Objekten innerhalb eines Feldes.  
- **🔑 Schlüssel-Wert-Paar** → Grundlegendes Element eines Dokuments, bestehend aus einem „Schlüssel“ und einem entsprechenden „Wert“.  

Beispiel eines Dokuments in einer „Benutzer“-Collection
-------------------------------------------------------

Ein praktisches Beispiel zeigt die Struktur eines Dokuments in einer NoSQL-Datenbank:

```json
// Collection: Benutzer
{                                             // Dokument für "Max Mustermann"
  "benutzer_id": "12345",                     // Schlüssel-Wert-Paar "benutzer_id" mit Wert "12345"
  "name": "Max Mustermann",
  "email": "<max.mustermann@example.com>",
  "adresse": {                                // Eingebettetes Dokument "adresse"
    "strasse": "Musterstrasse 1",
    "stadt": "Musterstadt",
    "plz": "12345"
  },
  "bestellungen": [                           // Array "bestellungen"
    {
      "bestell_id": "98765",                   
      "datum": "2025-03-01",
      "betrag": 99.99,
      "artikel": ["Buch", "Stift"]          // Array von Werten
    },
    {
      "bestell_id": "98766",
      "datum": "2025-03-15",
      "betrag": 49.99,
      "artikel": ["Notizbuch"]
    }
  ]
}
```

Hierbei sind mehrere NoSQL-spezifische Strukturen erkennbar:

- **Eingebettetes Dokument**: Die Adresse des Benutzers ist als Unterobjekt innerhalb des Hauptdokuments gespeichert.  
- **Array**: Das Feld `bestellungen` enthält eine Liste von Bestellobjekten, was eine 1:n-Beziehung direkt im Dokument abbildet.  

Diese Struktur ermöglicht eine **schnelle und effiziente Abfrage**, da alle relevanten Informationen direkt in einem Dokument gespeichert sind.

Unterschiede zwischen dokumentenorientierten NoSQL- und relationalen Datenbanken
-------------------------------------------------------------------------------

Die wesentlichen Unterschiede zwischen NoSQL- und relationalen Datenbanken lassen sich anhand verschiedener Aspekte aufzeigen:

| Merkmal                     | Dokumentenorientierte NoSQL-DB   | Relationale DB |
|-----------------------------|-----------------------------------|------------------|
| **Datenstruktur**           | JSON-Dokumente, eingebettete Objekte, Arrays | Tabellen mit Zeilen und Spalten |
| **Schema**                  | Flexibel, keine feste Struktur     | Fest definiert (Spalten müssen vorab definiert sein) |
| **Beziehungen**             | Daten können eingebettet sein      | Normalisierte Tabellen mit Fremdschlüsseln |
| **Skalierung**              | Horizontal (mehrere Server)        | Meist vertikal (leistungsstärkere Hardware) |
| **Performance für Lesezugriffe** | Sehr effizient für komplexe Objekte | Häufig JOIN-Operationen notwendig |

Während relationale Datenbanken für **strukturierte Daten** mit klaren Beziehungen optimiert sind, bieten dokumentenorientierte NoSQL-Datenbanken mehr **Flexibilität** und **Skalierbarkeit**.

Vorteile
========

Flexibilität in der Datenmodellierung
---------------------------------------

NoSQL-Datenbanken benötigen kein **festes Schema**. Dadurch können neue Felder hinzugefügt oder bestehende geändert werden, ohne dass komplexe **Schema-Migrationen** erforderlich sind. Dies ist besonders nützlich in agilen Entwicklungsprozessen, in denen sich Anforderungen häufig ändern.

Schnellere Lesezugriffe durch optimierte Abfragen
---------------------------------------

Da alle relevanten Daten in einem Dokument gespeichert sind, können Abfragen **schneller** ausgeführt werden, da keine **JOIN-Operationen** erforderlich sind. Besonders bei Anwendungen mit **hohem Leseaufkommen** (z. B. Webanwendungen, Echtzeitanalysen) ist dies ein grosser Vorteil.

Skalierbarkeit für grosse Datenmengen
---------------------------------------

NoSQL-Datenbanken unterstützen **horizontale Skalierung**, d. h. sie können einfach auf mehrere Server verteilt werden. Dies ist essenziell für Anwendungen mit **grossen Datenmengen** und **hohem Benutzeraufkommen**, z. B.:

- **Social Media Plattformen** (dynamische User-Daten, Kommentare, Likes)  
- **E-Commerce Systeme** (Produktkataloge, Nutzerverhalten, Transaktionen)  
- **IoT-Anwendungen** (Sensor-Daten, Echtzeitverarbeitung)  

Flexibilität in der Speicherung von unstrukturierten und semi-strukturierten Daten
---------------------------------------

Im Gegensatz zu relationalen Datenbanken, die ein **striktes Schema** erfordern, können dokumentenorientierte NoSQL-Datenbanken **heterogene Daten** speichern. Dies ist ideal für:

- **Log-Daten** (verschiedene Formate, je nach Quelle)  
- **Benutzergenerierte Inhalte** (Kommentare, Bewertungen, Posts)  
- **Maschinengenerierte Daten** (IoT- und Sensordaten)  

Fazit
------

Dokumentenorientierte NoSQL-Datenbanken bieten eine **hohe Flexibilität**, **effiziente Abfragen** und **gute Skalierbarkeit**, insbesondere für Anwendungen mit **dynamischen Datenmodellen** oder **grossen Datenmengen**. Sie eignen sich besonders gut für **Webanwendungen, Big Data und Echtzeitanalysen**, während relationale Datenbanken weiterhin eine gute Wahl für **transaktionsbasierte Systeme** mit **komplexen Beziehungen** sind.

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

- **Was ist JSON und welche Rolle spielt es in NoSQL-Datenbanken?**  
- **Wie ist die Struktur von JSON-Dokumenten aufgebaut?**  
- **Wie werden Daten in einer dokumentenorientierten NoSQL-Datenbank gespeichert?**  
- **Welche Unterschiede gibt es zwischen relationalen und NoSQL-Datenbanken?**  

Umsetzung
=========

NoSQL-Datenbanken wie MongoDB arbeiten mit einem flexiblen, schemalosen Datenmodell. Im Zentrum steht dabei das **JSON-Format**, das als Grundlage für die Darstellung und den Austausch von Daten dient.

Grundlagen von JSON verstehen
---------------------

**Definition und Bedeutung:**  
JSON (JavaScript Object Notation) ist ein leichtgewichtiges, textbasiertes Datenformat, das der Datenübertragung zwischen Anwendungen dient. Dieses Wissen ist grundlegend, um die Rolle von JSON in NoSQL-Datenbanken zu verstehen – ein zentrales Lernziel.

**Syntax-Regeln:**

- **Objekte** werden durch geschweifte Klammern `{}` eingeschlossen.  
- **Arrays** werden durch eckige Klammern `[]` dargestellt.  
- **Key-Value-Paare** sind die Grundbausteine; der Schlüssel ist immer ein String und der Wert kann ein String, eine Zahl, ein Boolean, ein Array, ein Objekt oder `null` sein.  
  Das detaillierte Verständnis dieser Regeln ermoeglicht es, die Struktur von JSON-Dokumenten zu erklaeren.
**Beispiel:**  

```json
{
  "person": {
    "vorname": "Peter",
    "nachname": "Muster",
    "alter": 30,
    "hobbys": ["Lesen", "Reisen", "Programmieren"]
  }
}
```

Gültige Elemente & Eigenschaften von Objekten und Arrays  
---------------------

**Gültige Elemente in JSON:**  
Ein JSON-Dokument darf nur bestimmte Datentypen enthalten, die als gültig definiert sind:

- Eine Zahl (integer oder floating point)
- Einen String (in doppelten Anführungszeichen)
- Einen Boolean (`true` oder `false`)
- Ein Array (in eckigen Klammern)
- Ein Objekt (in geschweiften Klammern)
- Den Wert `null`  
Alle anderen Elemente, die nicht diesen Typen entsprechen, inklusive Kommentare mit `//`, gelten als ungültig.
  
**Eigenschaften von Objekten:**  

- Objekte werden durch geschweifte Klammern `{}` eingeschlossen.
- Sie bestehen aus Key-Value-Paaren, wobei der Schlüssel stets ein String sein muss.
- Mehrere Key-Value-Paare werden durch Kommas getrennt.
- Objekte können auch andere Objekte (verschachtelte Strukturen) als Werte enthalten.

 **Eigenschaften von Arrays:**  

- Arrays werden durch eckige Klammern `[]` eingeschlossen.
- Arrays können beliebige JSON-Werte enthalten, einschließlich Objekte, Arrays, Zahlen, Strings, Booleans und `null`.
- Die Reihenfolge der Elemente in einem Array ist wichtig und bleibt erhalten.

Struktur in einer NoSQL-Datenbank (z. B. MongoDB)  
---------------------

- **Dokumente und Collections:**  
- **Dokumente:** Daten werden in JSON-ähnlichen Dokumenten gespeichert. Dies ermöglicht das flexible Speichern von Informationen
- **Collections:** Eine Collection ist eine Zusammenfassung von Dokumenten – vergleichbar mit Tabellen in relationalen Datenbanken, jedoch ohne festes Schema.  
- **Beispiel eines MongoDB-Dokuments:**  

```json
{
  "_id": "unique_identifier",
  "name": "Peter Muster",
  "kontakt": {
    "email": "peter.muster@example.com",
    "telefon": "0123456789"
  },
  "adresse": {
    "strasse": "Musterstrasse 12",
    "stadt": "Musterstadt",
    "plz": "12345"
  },
  "interessen": ["Lesen", "Reisen", "Programmieren"]
}
```  

**Flexibilität der Struktur:**  
**Individuelle Gestaltung:** Jedes Dokument kann unterschiedliche Felder enthalten, was die Anpassungsfähigkeit von NoSQL-Datenbanken unterstreicht.  
**Embedded Documents:** Informationen können innerhalb eines Dokuments verschachtelt werden, um komplexe Strukturen abzubilden.  
**Referenzen:** Statt Daten zu duplizieren, können Dokumente auch auf andere Dokumente verweisen.  

Vergleich zu relationalen Datenbanken
---------------------  

- **Schema und Struktur:**  
  - Relationale Datenbanken verwenden ein fest definiertes Schema, was zu starren Datenstrukturen führt.  
  - NoSQL-Datenbanken sind schemalos und erlauben variable Datenstrukturen.  

- **Datenbeziehungen:**  
  - Relationale Datenbanken nutzen **Joins**, um Beziehungen zwischen Tabellen herzustellen.  
  - In NoSQL-Datenbanken erfolgt die Modellierung von Beziehungen häufig durch **Embedded Documents** oder **Referenzen**.  

- **Speicherung:**  
  - Relationale Datenbanken speichern Daten nicht im Klartext, sondern in optimierten binären Formaten, die für effiziente Abfragen und Speicherplatznutzung ausgelegt sind.  
  - NoSQL-Datenbanken verwenden ebenfalls binäre Formate, wie BSON (Binary JSON) in MongoDB, um die Daten effizient zu speichern und zu verarbeiten.  

- **Skalierung:**  
  - Relationale Systeme werden in der Regel vertikal skaliert (leistungsstärkere Server).  
  - NoSQL-Datenbanken sind für horizontale Skalierung ausgelegt und können über mehrere Server verteilt werden.  

Wichtige Begriffe und Strukturen
-------------------

- **JSON (JavaScript Object Notation):**  
  Ein standardisiertes, textbasiertes Format zur Darstellung strukturierter Daten.
- **Dokumentenorientierte Datenbank:**  
  Eine Datenbank, in der Daten als Dokumente (meist im JSON-Format) gespeichert werden.
- **Collection:**  
  Eine Zusammenfassung von Dokumenten innerhalb einer Datenbank, vergleichbar mit einer Tabelle, jedoch ohne starres Schema.
- **Embedded Document:**  
  Ein innerhalb eines Dokuments verschachteltes weiteres Dokument, das komplexe Strukturen erlaubt.
- **Referenz:**  
  Ein Verweis von einem Dokument auf ein anderes, um Beziehungen zwischen Daten darzustellen.
- **Schema:**  
  In relationalen Datenbanken fest definierte Strukturen; in NoSQL-Datenbanken fehlen diese Vorgaben, was zu erhöhter Flexibilitaet fürht.

Fazit
========

NoSQL-Datenbanken wie MongoDB bieten durch ihre flexible, schemalose Datenstruktur eine innovative Alternative zu traditionellen relationalen Datenbanken.  
Die Verwendung von JSON als zentrales Format erleichtert den Datenaustausch und die Integration in verschiedenste Anwendungen.  
Die praxisnahe Anwendung, insbesondere der Import und Export von Daten, zeigt, dass NoSQL-Systeme durch ihre Flexibilitaet und Skalierbarkeit besonders für moderne, dynamische Anwendungen geeignet sind.

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
