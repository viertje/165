# Modul 165

Viewer: [Liascript Viewer](https://liascript.github.io/course/?https://raw.githubusercontent.com/viertje/165/master/README.md)

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

- **Was sind die Anwendungsfälle für NoSQL Datenbanken?** Ich kann Anwendungsfälle für NoSQL Datenbanken nennen.
- **Wann brauche ich eine NoSQL Datenbank?** Ich kann die Anwendungsfälle für NoSQL Datenbanken erläutern.
- **Welche NoSQL Datenbanken eignen sich für welche Anwendungsfälle?** Ich kann 3 NoSQL Datenbanken nennen und ihre Anwendungsfälle erläutern.

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

Wenn...

- ...die Datenmenge zu gross für eine relationale Datenbank ist
- ...die Datenstruktur nicht festgelegt ist
- ...die Daten schnell verarbeitet werden müssen
- ...die Daten über mehrere Server verteilt werden müssen

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

   - **Ich kann den Einsatz einer NoSQL Datenbank kritisch hinterfragen.**

- Welche Verbesserungen kann ich vorschlagen? 

    - **Ich kann Verbesserungen vorschlagen.**

Umsetzung
=========

Voraussetzung
-----

Die Voraussetzung für die kritische Hinterfragung des Einsatzes einer NoSQL-Datenbank ist ein **gutes Verständnis** der **Anforderungen** und **Einschränkungen** des Projekts.

Ich muss verstehen, welche **Daten** gespeichert werden und wie sie **verarbeitet** und **abgerufen** werden sollen. Ausserdem muss ich die **Skalierbarkeitsanforderungen** und die **Verfügbarkeit** der Datenbank berücksichtigen.

Wann brauche ich eine NoSQL Datenbank?
--------------------------------------

Wenn...

- ...die Datenmenge zu gross für eine relationale Datenbank ist
- ...die Datenstruktur nicht festgelegt ist
- ...die Daten schnell verarbeitet werden müssen
- ...die Daten über mehrere Server verteilt werden müssen

Wann brauche ich keine NoSQL Datenbank?
--------------------------------------

Wenn...

- ...die Datenstruktur festgelegt ist
- ...die Datenmenge klein ist
- ...die Datenbank nur auf einem Server betrieben wird
- ...die Datenbank nur für Transaktionen verwendet wird

![nosqlvssql](/images/nosqlVSsql.png)

Verbesserungen vorschlagen
--------------------------

| Verbesserung   | Beschreibung   |
| :--------- | :--------- |
| Optimierung der Datenstruktur     | Überprüfen, ob die Datenstruktur effizient ist und ob sie die Anforderungen des Projekts erfüllt     |
| Performance-Optimierung     | Überprüfen, ob die Datenbank die erforderliche Leistung erbringt und ob sie optimiert werden kann.     |
| Sicherheitsverbesserungen     | Überprüfen, ob die Datenbank ausreichend geschützt ist und ob zusätzliche Sicherheitsmassnahmen erforderlich sind.     |

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

- Wie kann ich ein vorgegebenes Datenmodell in einer NoSQL-Datenbank umsetzen? **Ich kann ein vorgegebenes Datenmodell in einer NoSQL-Datenbank umsetzen.**

- Wie erstelle ich eine NoSQL-Datenbank? **Ich kann eine NoSQL-Datenbank erstellen.**

- Wie speichere ich Daten in einer NoSQL-Datenbank? **Ich kann Daten in einer NoSQL-Datenbank speichern.**

Umsetzung
=========

Um ein vorgegebenes Datenmodell in einer NoSQL-Datenbank umzusetzen, sind folgende Schritte erforderlich:

- Die Struktur des Datenmodells verstehen und analysieren.
- Die NoSQL-Datenbank auswählen, die am besten zu den Anforderungen des Projekts passt. (MongoDB)
- Eine NoSQL-Datenbank erstellen und konfigurieren.

Das Datenmodell sieht wie folgt aus:

![erd](images/erd.png)

```json users
{
  "_id": ObjectId,
  "username": "johndoe",
  "email": "john@example.com",
  "created_at": ISODate
}
```

```json posts
{
  "_id": ObjectId,
  "title": "My First Post",
  "content": "This is the content of the post.",
  "author_id": ObjectId,
  "tags": ["mongodb", "nosql"],
  "created_at": ISODate,
  "comments": [
    {
      "author_id": ObjectId,
      "content": "Nice post!",
      "created_at": ISODate
    },
    {
      "author_id": ObjectId,
      "content": "Thanks for sharing!",
      "created_at": ISODate
    }
  ]
}
```
Um dieses Datenmodell in einer NoSQL-Datenbank umzusetzen, muss eine Datenbank erstellt werden.

Um eine MongoDB-Datenbank zu erstellen kann ein Docker-Container verwendet werden:

```yml docker-compose.yml

services:
  mongo:
    image: mongo:7
    container_name: mongodb
    ports:
      - "27017:27017"
    volumes:
      - mongo-data:/data/db

volumes:
  mongo-data:
```
Docker Desktop erlaubt es, ein Terminial zu öffnen, um mit der MongoDB-Datenbank zu kommunizieren. Hier können die Daten in die Datenbank eingefügt werden.

```bash bash
# connect to the MongoDB container
mongosh

# switch to the database
use blogdb

# insert a user
const userId = ObjectId();
db.users.insertOne({
  _id: userId,
  username: "johndoe",
  email: "john@example.com",
  created_at: new Date()
});

# insert a post
db.posts.insertOne({
  title: "My First Post",
  content: "This is the content of the post.",
  author_id: userId,
  tags: ["mongodb", "nosql"],
  created_at: new Date(),
  comments: [
    {
      author_id: userId,
      content: "Nice post!",
      created_at: new Date()
    }
  ]
});

```
Somit sind die Daten in der MongoDB-Datenbank gespeichert. Die Daten können nun abgerufen und bearbeitet werden.

![query](images/query_simple.png)

Zusammenfassung
-----------------

NoSQL-Datenbanken wie MongoDB verwenden eine flexible, schemalose Struktur, die es ermöglicht, Daten in Form von Dokumenten zu speichern. Diese Dokumente können komplexe Strukturen enthalten, wie z. B. eingebettete Dokumente und Arrays.

Ein Datenmodell umzusetzen ist daher ein einfacher Prozess, der es ermöglicht, Daten in einer NoSQL-Datenbank zu speichern und abzurufen. Die Flexibilität und Skalierbarkeit von NoSQL-Datenbanken machen sie zu einer idealen Wahl für moderne Anwendungen.

### B1F Praktischer Nachweis


ERD Ausgangslage
------------

![books erd](images/b1f/book_erd.png)

- Bücher haben Titel, Autor, Erscheinungsjahr, Genres.
- Nutzer können Bücher bewerten (1–5 Sterne) und einen Kommentar hinterlassen.
- Jede Bewertung gehört zu einem Buch und einem Nutzer.

Struktur des Datenmodells in MongoDB
-------------


User

```js
{
  "_id": ObjectId,
  "username": "booklover42",
  "email": "reader@example.com",
  "registeredAt": ISODate
}
```

Book

```js
{
  "_id": ObjectId,
  "title": "Clean Code",
  "author": "Robert C. Martin",
  "published_year": 2008,
  "genres": ["Programming", "Software Engineering"]
}
```

Rating

```js
{
  "_id": ObjectId,
  "book_id": ObjectId, // Referenz zum Buch
  "user_id": ObjectId, // Referenz zum Nutzer
  "stars": 5,
  "comment": "Fragwürdige Empfehlungen!",
  "created_at": ISODate
}
```

Mit Container von oben Verbinden und in `library` Datenbank wechseln:	

```bash
docker exec -it mongodb mongosh
use library
```

Benutzer anlegen

```js
# Benutzer anlegen
const userId = ObjectId();
db.users.insertOne({
  _id: userId,
  username: "reader123",
  email: "reader@example.com",
  registered_at: new Date()
});
```

Buch anlegen

```js
const bookId = ObjectId();
db.books.insertOne({
  _id: bookId,
  title: "Clean Code",
  author: "Robert C. Martin",
  published_year: 2008,
  genres: ["Programming", "Software Engineering"]
});
```

Bewertung erstellen

```js
db.ratings.insertOne({
  book_id: bookId,
  user_id: userId,
  stars: 5,
  comment: "Fragwürdige Empfehlungen!",
  created_at: new Date()
});
```

Abfragebeispiel mit Aggregation
------------

```js
db.ratings.aggregate([
  {
    $lookup: {
      from: "books",
      localField: "book_id",
      foreignField: "_id",
      as: "book"
    }
  },
  { $unwind: "$book" },
  {
    $lookup: {
      from: "users",
      localField: "user_id",
      foreignField: "_id",
      as: "user"
    }
  },
  { $unwind: "$user" },
  {
    $project: {
      book_title: "$book.title",
      reviewer: "$user.username",
      stars: 1,
      comment: 1,
      created_at: 1
    }
  }
]);
```

Screenshots
---------

Insert Book and User

![book_insert_1](images/b1f/book_insert_1.png)

Insert rating and show aggregation

![book_insert_2](images/b1f/book_insert_2.png)

### B1E

> Ich kann ein Datenmodell für eine NoSQL Datenbank entwerfen.

Fragenstellung und Lernziele
==============

**Fragenstellung**: Wie entwirft man ein flexibles und performantes Datenmodell für eine NoSQL-Datenbank?

**Lernziele**:

- Verständnis der Kernkonzepte des NoSQL-Datenmodell-Designs, insbesondere im Kontext von Dokumentendatenbanken.
- Fähigkeit, die Anforderungen einer Anwendung in ein geeignetes NoSQL-Datenmodell zu übersetzen.
- Analyse und Begründung von Designentscheidungen wie Denormalisierung, Einbettung (Embedding) vs. Referenzierung (Linking).
- Erstellung eines beispielhaften Datenmodells (z.B. im JSON-Format)
- Bewertung der Auswirkungen des Datenmodells auf typische Abfragemuster und Skalierbarkeit

Umsetzung
=========

Kernkonzepte des NoSQL-Datenmodell-Designs (Dokumentendatenbanken)
----------------

Im Gegensatz zu relationalen Datenbanken, die auf normalisierten Tabellen mit festen Schemata basieren, bieten NoSQL-Dokumentendatenbanken (wie MongoDB oder Couchbase) mehr Flexibilität. Die Kernkonzepte umfassen:

1. Aggregat-Orientierung: Daten, die zusammengehören und häufig gemeinsam abgerufen werden, sollten idealerweise in einem einzigen Dokument (Aggregat) gespeichert werden. Dies minimiert die Notwendigkeit von Joins.
2. Schema-Flexibilität: Dokumente in derselben Sammlung müssen nicht dieselbe Struktur haben. Felder können hinzugefügt oder entfernt werden, ohne das gesamte Schema zu ändern. Dies ist vorteilhaft für agile Entwicklung und sich entwickelnde Anforderungen.
3. Priorisierung von Leseleistung: NoSQL-Datenmodelle werden oft so optimiert, dass die häufigsten Lesezugriffe sehr schnell erfolgen, auch wenn dies zu einer gewissen Datenredundanz (Denormalisierung) und komplexeren Schreibvorgängen führen kann.
4. Skalierbarkeit: Durch die Verteilung von Daten auf viele Server (Sharding) können NoSQL-Datenbanken horizontal skalieren. Das Datenmodell sollte dies unterstützen.

Anforderungen einer Anwendung in ein NoSQL-Datenmodell übersetzen
----------------

Der Prozess beginnt mit dem Verständnis der Anwendungsanforderungen:

1. Entitäten identifizieren: Welche Hauptobjekte gibt es in Ihrer Anwendung (z.B. Benutzer, Produkte, Bestellungen)?
2. Beziehungen definieren: Wie stehen diese Entitäten zueinander (z.B. ein Benutzer hat viele Bestellungen, eine Bestellung enthält viele Produkte)?
3. Abfragemuster analysieren: Welche Daten werden am häufigsten zusammen gelesen? Welche Filter und Sortierungen werden benötigt? Wie sehen typische Schreibvorgänge aus?
4. Performance- und Skalierbarkeitsziele: Wie viele Lese-/Schreibvorgänge pro Sekunde werden erwartet? Wie gross werden die Datenmengen?

**Beispielanwendung**: Ein einfaches Blog-System mit Benutzern, Blog-Posts und Kommentaren.

Entitäten: User, Post, Comment

Beziehungen:

- Ein `User` kann viele `Posts` schreiben.
- Ein `User` kann viele `Comments` schreiben.
- Ein `Post` wird von einem `User` geschrieben.
- Ein `Post` kann viele `Comments` haben.

Typische Abfragemuster:

- Anzeige eines Posts mit allen zugehörigen Kommentaren und Autoreninformationen.
- Auflistung aller Posts eines bestimmten Benutzers.
- Anzeige der neuesten Posts.

Designentscheidungen: Denormalisierung, Einbettung vs. Referenzierung
-----------------

Basierend auf den Anforderungen werden Entscheidungen über die Datenstruktur getroffen.

Denormalisierung
------------------

Hierbei werden redundante Datenkopien gespeichert, um Lesezugriffe zu beschleunigen, indem Joins vermieden werden.

- **Beispiel**: Statt nur die `user_id` im Post-Dokument zu speichern, könnte man auch den `username` direkt im `Post`-Dokument speichern. Wenn der Benutzername angezeigt werden soll, muss nicht extra das `User`-Dokument geladen werden.
- **Nachteil**: Bei Änderungen (z.B. Benutzername ändert sich) müssen alle redundanten Kopien aktualisiert werden, was Schreibvorgänge komplexer macht.

Einbettung (Embedding) vs. Referenzierung (Linking)
-----------------

Dies ist eine zentrale Entscheidung im Dokumentenmodell-Design.

**Einbettung (Embedding)**: Verknüpfte Daten werden direkt in das übergeordnete Dokument integriert.

Beispiel: Kommentare (Comments) könnten als Array direkt in das Post-Dokument eingebettet werden. 

```json
{
  "_id": "post123",
  "title": "Mein erster Post",
  "content": "...",
  "author_id": "userABC",
  "author_username": "Alice", // Denormalisiert
  "comments": [
    { "commenter_id": "userXYZ", "commenter_username": "Bob", "text": "Toller Post!", "date": "..." },
    { "commenter_id": "userDEF", "commenter_username": "Charlie", "text": "Interessant.", "date": "..." }
  ]
}
```

| Vorteile | Nachteile |
|----------|-----------|
| Daten können in einer einzigen Leseoperation abgerufen werden (Post + Kommentare) | Dokumente können sehr gross werden, was die Performance beeinträchtigen und zu Grössenbeschränkungen (z.B. 16MB in MongoDB) führen kann |
| Atomare Operationen auf dem Hauptdokument sind einfacher (wenn die Datenbank dies unterstützt) | Das Aktualisieren eines einzelnen eingebetteten Elements (z.B. eines Kommentars) erfordert das Neuschreiben des gesamten Hauptdokuments |
|  | Das separate Abfragen der eingebetteten Elemente (z.B. alle Kommentare eines bestimmten Benutzers über alle Posts hinweg) ist oft ineffizient oder unmöglich |

**Referenzierung (Linking)**: Verknüpfte Daten werden in separaten Sammlungen (Collections) gespeichert, und im Hauptdokument wird nur eine Referenz (z.B. die ID) auf das verknüpfte Dokument gespeichert.

Beispiel: Kommentare werden in einer eigenen Comments-Sammlung gespeichert, und im Post-Dokument wird nur eine Liste von comment_ids oder gar keine direkte Referenz gehalten (Kommentare referenzieren den Post).

**Posts Collection**:

```json
{
  "_id": "post123",
  "title": "Mein erster Post",
  "content": "...",
  "author_id": "userABC",
  "author_username": "Alice", // Denormalisiert
  "comment_count": 2 // Denormalisiert, optional
}
```

**Comments Collection**:

```json
[
  {
    "_id": "comment789",
    "post_id": "post123",
    "commenter_id": "userXYZ",
    "commenter_username": "Bob",
    "text": "Toller Post!",
    "date": "..."
  },
  {
    "_id": "comment790",
    "post_id": "post123",
    "commenter_id": "userDEF",
    "commenter_username": "Charlie",
    "text": "Interessant.",
    "date": "..."
  }
]
```

| Vorteile | Nachteile |
|----------|-----------|
| Dokumente bleiben kleiner und übersichtlicher | Um alle Daten zu erhalten (z.B. Post und seine Kommentare), sind mehrere Abfragen an die Datenbank notwendig (Application-Level Join) |
| Verknüpfte Daten können unabhängig voneinander abgefragt und modifiziert werden | Einige Datenbanken bieten $lookup (MongoDB) für serverseitige Joins, was aber die Komplexität der Abfrage erhöht |
| Besser geeignet für "many-to-many"-Beziehungen oder wenn die Anzahl der verknüpften Elemente sehr gross sein kann | |

**Entscheidungsfindung**:

- **"One-to-few" Beziehungen**: Einbettung ist oft gut, wenn die Anzahl der eingebetteten Elemente begrenzt ist und sie meist zusammen mit dem Elternelement gelesen werden (z.B. Adressen eines Benutzers).
- **"One-to-many" / "One-to-squillions" Beziehungen**: Referenzierung ist meist besser, besonders wenn die Anzahl der "many"-Elemente gross ist oder sie oft unabhängig vom Elternelement bearbeitet/abgefragt werden (z.B. Kommentare zu einem populären Blog-Post).
- **Häufigkeit des Zugriffs**: Werden die Daten fast immer zusammen benötigt? Dann Einbettung. Werden sie oft getrennt benötigt? Dann Referenzierung.
- **Datenkonsistenz**: Bei Denormalisierung oder Zählern (wie comment_count) muss die Konsistenz bei Schreibvorgängen sichergestellt werden (z.B. durch Transaktionen, falls unterstützt, oder durch eventual consistency).

Beispielhaftes Datenmodell (JSON-Format)
----------------

Für unser Blog-System entscheiden wir uns für eine Mischung: Wir referenzieren Kommentare, da ein Post potenziell sehr viele Kommentare haben kann, und denormalisieren einige Autoreninformationen für eine schnelle Anzeige.

1. Users Collection (users)

```json
[
  {
    "_id": "userABC",
    "username": "Alice",
    "email": "alice@example.com",
    "join_date": "2023-01-15T10:00:00Z"
  },
  {
    "_id": "userXYZ",
    "username": "Bob",
    "email": "bob@example.com",
    "join_date": "2023-02-20T14:30:00Z"
  }
]
```

2. Posts Collection (posts)

```json
[
  {
    "_id": "post123",
    "title": "Einführung in NoSQL",
    "content": "NoSQL-Datenbanken bieten viele Vorteile...",
    "author_id": "userABC", // Referenz zum User
    "author_username": "Alice", // Denormalisiert für schnelle Anzeige
    "created_at": "2024-06-01T12:00:00Z",
    "tags": ["NoSQL", "Datenbanken", "Tutorial"],
    "comment_count": 1 // Denormalisierter Zähler, optional
  },
  {
    "_id": "post456",
    "title": "Datenmodellierung für Performance",
    "content": "Ein gutes Datenmodell ist entscheidend...",
    "author_id": "userXYZ", // Referenz zum User
    "author_username": "Bob", // Denormalisiert für schnelle Anzeige
    "created_at": "2024-06-05T09:30:00Z",
    "tags": ["Datenmodellierung", "Performance"],
    "comment_count": 0
  }
]
```

3. Comments Collection (comments)

```json
[
  {
    "_id": "comment789",
    "post_id": "post123", // Referenz zum Post
    "commenter_id": "userXYZ", // Referenz zum kommentierenden User
    "commenter_username": "Bob", // Denormalisiert
    "text": "Sehr informativer Artikel, Alice!",
    "commented_at": "2024-06-01T15:20:00Z"
  }
]
```

Bewertung der Auswirkungen des Datenmodells auf typische Abfragemuster und Skalierbarkeit
----------------

Abfragemuster
------------

Anzeige eines Posts mit Autoreninfo und Kommentaren:

1. Lade den Post aus `posts` anhand der `_id`. (1 Abfrage)

- `author_username` ist bereits im Post-Dokument enthalten (denormalisiert).
- Lade alle Kommentare aus `comments`, bei denen `post_id` der ID des geladenen Posts entspricht. (1 Abfrage, Index auf `comments.post_id` notwendig)
- `commenter_username` ist bereits im Kommentar-Dokument enthalten.
- Performance: Zwei schnelle, indizierte Abfragen. Dies ist performanter als viele Joins in einer relationalen DB für denselben Anwendungsfall und vermeidet das Problem riesiger Dokumente bei Einbettung.

2. Auflistung aller Posts eines bestimmten Benutzers (z.B. "Alice"):
- Suche in `posts` nach `author_id`: "userABC". (1 Abfrage, Index auf `posts.author_id` notwendig)
- Performance: Schnell und effizient.

3. Anzeige der neuesten 10 Posts:
- Suche in `posts`, sortiere nach `created_at` absteigend, limitiere auf 10. (1 Abfrage, Index auf `posts.created_at` notwendig)
- Performance: Schnell und effizient.

4.  Hinzufügen eines neuen Kommentars:
- Füge ein neues Dokument in die `comments`-Sammlung ein.
- Optional: Inkrementiere `comment_count` im zugehörigen `posts`-Dokument. Dies kann atomar erfolgen, wenn die Datenbank es unterstützt, oder als separate Update-Operation (eventual consistency).
- Performance: Schnell. Die Aktualisierung des `comment_count` ist ein zusätzlicher Schreibvorgang, der aber die Leseleistung für die Anzeige der Kommentaranzahl verbessert.

Skalierbarkeit
----------------

- Horizontale Skalierbarkeit: Jede Sammlung (`users`, `posts`, `comments`) kann unabhängig voneinander auf verschiedene Shards verteilt werden.
- Dokumentgrösse: Durch die Referenzierung der Kommentare bleiben die `posts`-Dokumente relativ klein, was positiv für die Performance und die Vermeidung von Grössenlimits ist.
- Lese-Skalierbarkeit: Häufige Leseoperationen (Post anzeigen) profitieren von den Denormalisierungen und der Trennung der Sammlungen.
- Schreib-Skalierbarkeit: Schreibvorgänge sind ebenfalls gut skalierbar. Die Aktualisierung denormalisierter Daten (z.B. wenn sich ein username ändert) erfordert mehr Aufwand (Aktualisierung in `users` und in allen zugehörigen `posts` und `comments`). Dies ist ein bekannter Trade-off. Für Anwendungsfälle, in denen Benutzernamen sich selten ändern, ist dies oft akzeptabel. Wenn sie sich häufig ändern, könnte man erwägen, Benutzernamen nicht in Posts/Kommentaren zu denormalisieren und stattdessen bei der Anzeige separate Lookups durchzuführen oder die Aktualisierung über Hintergrundprozesse zu steuern.

### B1E Praktischer Nachweis

> Ich kann ein Datenmodell für eine NoSQL Datenbank entwerfen.

Fragenstellung und Lernziele
==============

**Fragenstellung**: Wie entwirft man ein flexibles und performantes Datenmodell für eine NoSQL-Datenbank, exemplarisch an einem E-Commerce-System?

**Lernziele**:

- Verständnis der Kernkonzepte des NoSQL-Datenmodell-Designs, insbesondere im Kontext von Dokumentendatenbanken.
- Fähigkeit, die Anforderungen einer Anwendung (E-Commerce) in ein geeignetes NoSQL-Datenmodell zu übersetzen.
- Analyse und Begründung von Designentscheidungen wie Denormalisierung, Einbettung (Embedding) vs. Referenzierung (Linking).
- Erstellung eines beispielhaften Datenmodells (im JSON-Format).
- Bewertung der Auswirkungen des Datenmodells auf typische Abfragemuster und Skalierbarkeit.

Umsetzung
=========

Kernkonzepte des NoSQL-Datenmodell-Designs (Dokumentendatenbanken)
----------------

1. **Aggregat-Orientierung**: Daten, die zusammengehören und häufig gemeinsam abgerufen werden, sollten in einem einzigen Dokument (Aggregat) gespeichert werden. So werden Joins minimiert.
2. **Schema-Flexibilität**: Dokumente in einer Collection können unterschiedliche Felder haben. Neue Felder werden ohne Migrationsaufwand ergänzt.
3. **Priorisierung von Leseleistung**: Häufige Lesezugriffe werden optimiert – oft durch Denormalisierung, um Joins zu vermeiden. Schreibvorgänge können dadurch komplexer werden.
4. **Skalierbarkeit**: Horizontale Verteilung (Sharding) wird unterstützt. Das Datenmodell sollte hierfür vorbereitet sein.

Anforderungen einer Anwendung in ein NoSQL-Datenmodell übersetzen
----------------

1. **Entitäten identifizieren**: Hauptobjekte sind in unserem E-Commerce-System z.B. `User`, `Product`, `Order`, `Review`.

2. **Beziehungen definieren**:
- Ein `User` kauft viele `Orders`.  
- Eine `Order` enthält viele `Products`.  
- Ein `User` kann viele `Reviews` schreiben, und ein `Product` hat viele `Reviews`.

3. **Abfragemuster analysieren**:
- Anzeige einer Order mit allen Artikeln und Versandadresse.  
- Auflistung aller Orders eines Users.  
- Anzeige eines Products mit allen Reviews und Rezensenteninfo.  
- Suche nach Produkten in einer Kategorie oder nach Neuerscheinungen.

4. **Performance- und Skalierbarkeitsziele**:
- Tausende Lese-/Schreibvorgänge pro Sekunde
- Datenvolumen in den Collections wächst mit Bestellungen und Reviews.

Beispielanwendung: E-Commerce-System
----------------

Entitäten:

- `User`  
- `Product`  
- `Order`  
- `Review`  

Typische Abfragemuster:
----------------

- Bestellung anzeigen (inkl. Artikel und Adresse)  
- Bestellungen eines Users auflisten  
- Produktdetails mit Reviews anzeigen  
- Neueste Produkte anzeigen

Designentscheidungen: Denormalisierung, Einbettung vs. Referenzierung
----------------

Denormalisierung
------------------

- Redundante Kopien (z.B. Produktnamen in Orders, Benutzername in Reviews), um Lesezugriffe ohne zusätzliche Joins zu ermöglichen.  
- **Nachteil**: Änderungen (z.B. Produktname) müssen an mehreren Stellen synchronisiert werden.

Einbettung (Embedding) vs. Referenzierung (Linking)
------------------

**Einbettung**: Verknüpfte Daten direkt im Elterndokument speichern.

| Vorteile | Nachteile |
|----------|-----------|
| Alles in einem Dokument abrufbar (z.B. Order + Items) | Dokumente können sehr gross werden |
| Atomare Updates des Aggregats möglich | Eingebettete Objekte nur zusammen bearbeitbar |
| Ideal für „one-to-few“ Beziehungen (z.B. Adresse eines Users) | |

**Referenzierung**: Separate Collections, nur IDs oder Zähler im Hauptdokument.

| Vorteile | Nachteile |
|----------|-----------|
| Kleine Hauptdokumente, übersichtlicher | Mehrere Abfragen für zusammengesetzte Daten |
| Unabhängige Bearbeitung der Dokumente | Application-Level-Joins nötig bzw. $lookup in MongoDB |
| Gut für „one-to-many“ mit vielen Elementen (z.B. Reviews) | |

Entscheidungsfindung
----------------

- **„One-to-few“**: Einbettung (z.B. Adressen in `User`).  
- **„One-to-many/one-to-squillions“**: Referenzierung (z.B. viele Reviews).  
- **Häufigkeit des Zugriffs**: Gemeinsamer Zugriff → Einbettung; getrennte Nutzung → Referenzierung.  
- **Datenkonsistenz**: Denormalisierte Felder erfordern Transaktionen oder Background Jobs für Synchronisation.

Beispielhaftes Datenmodell (JSON-Format)
----------------

**users.json**

```json
[
  {
    "_id": "user001",
    "name": "Alice Muller",
    "email": "alice@example.com",
    "join_date": "2024-01-10T08:00:00Z",
    "addresses": [
      {
        "type": "home",
        "street": "Musterstrasse 1",
        "city": "Zurich",
        "postal_code": "8000",
        "country": "Schweiz"
      }
    ]
  },
  {
    "_id": "user002",
    "name": "Bob Schmid",
    "email": "bob@example.com",
    "join_date": "2024-02-05T11:15:00Z",
    "addresses": []
  }
]
```

**products.json**

```json
[
  {
    "_id": "prodA1",
    "name": "Wireless Maus",
    "description": "Ergonomische kabellose Maus",
    "price": 29.99,
    "categories": ["Elektronik","Zubehoer"],
    "stock": 150,
    "created_at": "2024-05-01T09:00:00Z",
    "rating_average": 4.5
  },
  {
    "_id": "prodB2",
    "name": "USB-C Kabel",
    "description": "Schnelles Ladekabel, 1.5m",
    "price": 9.99,
    "categories": ["Elektronik","Kabel"],
    "stock": 500,
    "created_at": "2024-04-20T14:30:00Z",
    "rating_average": 4.2
  }
]
```

**orders.json**

```json
[
  {
    "_id": "order1001",
    "user_id": "user001",
    "order_date": "2024-06-10T14:30:00Z",
    "items": [
      {
        "product_id": "prodA1",
        "product_name": "Wireless Maus",
        "quantity": 2,
        "price": 29.99
      },
      {
        "product_id": "prodB2",
        "product_name": "USB-C Kabel",
        "quantity": 1,
        "price": 9.99
      }
    ],
    "total_amount": 69.97,
    "shipping_address": {
      "street": "Examplestrasse 5",
      "city": "Bern",
      "postal_code": "3000",
      "country": "Schweiz"
    },
    "status": "shipped"
  }
]
```

**reviews.json**

```json
[
  {
    "_id": "rev500",
    "product_id": "prodA1",
    "user_id": "user002",
    "user_name": "Bob Schmid",
    "rating": 5,
    "comment": "Sehr gute Maus, liegt gut in der Hand.",
    "review_date": "2024-06-12T10:15:00Z"
  }
]
```

Bewertung der Auswirkungen des Datenmodells auf typische Abfragemuster und Skalierbarkeit
----------------

Abfragemuster
----------------

1. **Bestellung anzeigen**  
- Lade das Dokument aus `orders` per `_id`.  
- Artikeldetails (`product_name`) sind denormalisiert und direkt verfügbar.  
- Versandadresse als eingebettetes Objekt.  
- **Performance**: Eine Abfrage, keine Joins nötig.

2. **Bestellungen eines Users**  
- Suche in `orders` nach `user_id`. (Index auf `orders.user_id`)  
- **Performance**: Einfache, schnelle Abfrage.

3. **Produktdetails mit Reviews**  
- Lade `product` aus `products` nach `_id`.  
- Suche in `reviews` nach `product_id`. (Index auf `reviews.product_id`)  
- `user_name` in den Reviews ist bereits denormalisiert.  
- **Performance**: Zwei indizierte Abfragen, verhält sich besser als Joins in relationaler DB.

4. **Neueste Produkte anzeigen**  
- Suche in `products`, sortiere nach `created_at` absteigend, limitiere auf N.  
- **Performance**: Sehr schnell.

5. **Neues Review hinzufügen**  
- Insert in `reviews`.  
- Optional: Aktualisierung von `rating_average` in `products`.  
- **Performance**: Schreiboperation plus minimaler weiterer Aufwand.

Skalierbarkeit
----------------

- **Horizontale Skalierung**: Sharding pro Collection.  
- **Dokumentgrössen**: Beherrschbar durch begrenzte Item-Anzahl in Orders.  
- **Lese-Skalierbarkeit**: Denormalisierung & Embedding optimieren.  
- **Schreib-Skalierbarkeit**: Einfach, Änderungen an denormalisierten Feldern erfordern Synchronisation.  
- **Trade-Off**: Denormalisierte Daten vs. Synchronisationsstrategien (Transaktionen, Background Jobs).


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

![JSON syntax diagram](images/json_syntax_diagram.png)

**Definition und Bedeutung:**  
JSON (JavaScript Object Notation) ist ein leichtgewichtiges, textbasiertes Datenformat, das der Datenübertragung zwischen Anwendungen dient. Dieses Wissen ist grundlegend, um die Rolle von JSON in NoSQL-Datenbanken zu verstehen – ein zentrales Lernziel.

**Syntax-Regeln:**

- **Objekte** werden durch geschweifte Klammern `{}` eingeschlossen.  
- **Arrays** werden durch eckige Klammern `[]` dargestellt.  
- **Key-Value-Paare** sind die Grundbausteine; der Schlüssel ist immer ein String und der Wert kann ein String, eine Zahl, ein Boolean, ein Array, ein Objekt oder `null` sein.  
  Das detaillierte Verständnis dieser Regeln ermöglicht es, die Struktur von JSON-Dokumenten zu erklären.
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
- Arrays können beliebige JSON-Werte enthalten, einschliesslich Objekte, Arrays, Zahlen, Strings, Booleans und `null`.
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

- **Individuelle Gestaltung:** Jedes Dokument kann unterschiedliche Felder enthalten, was die Anpassungsfähigkeit von NoSQL-Datenbanken unterstreicht.  
- **Embedded Documents:** Informationen können innerhalb eines Dokuments verschachtelt werden, um komplexe Strukturen abzubilden.  
- **Referenzen:** Statt Daten zu duplizieren, können Dokumente auch auf andere Dokumente verweisen.  

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
  In relationalen Datenbanken fest definierte Strukturen; in NoSQL-Datenbanken fehlen diese Vorgaben, was zu erhöhter Flexibilität fürht.

### C1F

> Ich kann Daten in eine NoSQL Datenbank übernehmen.

Fragenstellung und Lernziele
==============
- **Welche Methoden gibt es, um Daten in eine NoSQL Datenbank zu importieren?** Ich kann verschiedene Ansätze zum Import von Daten in NoSQL Datenbanken nennen.
- **Wie wird der Datenimport praktisch umgesetzt?** Ich kann den Einsatz von Tools wie `mongoimport`, Mongo Express oder Mongo Compass erläutern.
- **Welche Datenformate werden für den Import unterstützt?** Ich kann die häufig genutzten Formate nennen und ihre Besonderheiten erläutern.
- **Wie kann man den Erfolg des Datenimports validieren?** Ich kann erklären, wie durch Abfragen und Überprüfungen sichergestellt wird, dass die importierten Daten korrekt und vollständig übernommen wurden.

Umsetzung
=========
In NoSQL Datenbanken erfolgt die Datenübernahme über verschiedene Methoden. Häufige Ansätze umfassen:

- **CLI-Tools:**  
  Der Einsatz von Befehlszeilentools wie `mongoimport` ermöglicht einen automatisierten und skriptbaren Datenimport. 

- **GUI-basierte Tools:**  
  Anwendungen wie **Mongo Express** oder **Mongo Compass** bieten eine benutzerfreundliche Oberfläche, um Dateien (z. B. JSON oder CSV) in eine Datenbank zu importieren.
  
- **Programmgesteuerten Import:**  
  Durch Skripte in Programmiersprachen wie Python oder JavaScript können Daten programmatisch in die Datenbank übernommen werden.

Beispiel: Import einer JSON-Datei mit mongoimport
---------------------
1. **Vorbereitung:**  
  Stellen Sie sicher, dass die JSON-Datei korrekt formatiert ist und alle erforderlichen Daten enthält.  
  Beispiel für eine JSON-Datei (`data.json`):  

```js
[
  {
    "name": "Max Mustermann",
    "email": "max.mustermann@example.com",
    "age": 30,
    "hobbies": ["Lesen", "Reisen", "Programmieren"]
  },
  {
    "name": "Anna Musterfrau",
    "email": "anna.musterfrau@example.com",
    "age": 25,
    "hobbies": ["Fotografie", "Kochen", "Wandern"]
  }
]
```

2. **Ausführung:**  
  Führen Sie folgenden Befehl aus, um die Daten in die gewünschte Datenbank und Collection zu übernehmen:  

```bash

mongoimport --db exampleDB --collection documents --file data.json --jsonArray

```

Validierung des Datenimports
---------------------
- **Validierung:**  
  Prüfen Sie mittels Abfragen, ob die importierten Dokumente vollständig und korrekt in der Collection vorhanden sind.

Nach dem Import der Daten in die NoSQL-Datenbank kann die folgende Abfrage verwendet werden, um sicherzustellen, dass die Daten korrekt übernommen wurden:

```js
// Überprüfen, ob die Collection Dokumente enthält
db.documents.find().pretty();
```

**Erklärung:**

`db.documents.find()` ruft alle Dokumente aus der Collection `documents` ab.

`.pretty()` formatiert die Ausgabe, um sie lesbarer zu machen.

**Zusätzliche Validierung:**
Falls spezifische Kriterien überprüft werden sollen, kann eine gezielte Abfrage verwendet werden. Zum Beispiel:

```js
// Überprüfen, ob ein bestimmtes Dokument importiert wurde
db.documents.find({ "name": "Max Mustermann" });
```

**Erwartetes Ergebnis:**

- Die Abfrage sollte das Dokument mit dem Namen `Max Mustermann` zurückgeben, falls der Import erfolgreich war.
- Falls keine Ergebnisse zurückgegeben werden, sollte der Importprozess erneut überprüft werden.


**Hinweis:**

Falls die Daten nicht wie erwartet erscheinen, können folgende Schritte helfen:

1. Überprüfen Sie den Importbefehl und die verwendete Datei.
2. Stellen Sie sicher, dass die Datenbank und die Collection korrekt benannt sind.
3. Prüfen Sie die Logs auf mögliche Fehler während des Imports.

Wichtige Begriffe und Strukturen
---------------------
- **Datenimport:**  
  Der Prozess der Übernahme von Daten aus externen Quellen (z. B. Dateien) in eine NoSQL Datenbank.
- **CLI-Tools:**  
  Befehlszeilenprogramme wie `mongoimport`, die den automatisierten Import von Daten ermöglichen.
- **GUI-basierte Tools:**  
  Anwendungen mit grafischer Oberfläche, wie Mongo Express oder Mongo Compass, die den Import von Daten vereinfachen.
- **Validierung:**  
  Methoden zur Überprüfung, ob die importierten Daten korrekt und vollständig übernommen wurden.
- **Fehlerbehandlung:**  
  Mechanismen, um während des Importprozesses auftretende Probleme zu identifizieren und zu beheben.

Der Import von Daten in eine NoSQL Datenbank ist ein zentraler Prozess, der über unterschiedliche Methoden erfolgen kann.  
Ob über CLI-Tools, grafische Anwendungen oder programmatische Ansätze – durch den Einsatz standardisierter Datenformate wie JSON oder CSV und einer anschliessenden Validierung kann sichergestellt werden, dass die Datenübernahme effizient und fehlerfrei erfolgt.

Nachweis
========
1. **Praktische Übung:**  
   Importiere eine JSON- oder CSV-Datei in eine NoSQL Datenbank (z. B. MongoDB) mittels `mongoimport` oder einem GUI-Tool.

Testdb
---------

```dockerfile
version: '3.8'

services:
  mongodb:
    image: mongo:7
    container_name: test_mongo
    ports:
      - "27017:27017"
    volumes:
      - mongo_data:/data/db
      - ./example.csv:/tmp/example.csv:ro
    restart: unless-stopped

volumes:
  mongo_data:
```

```bash
docker-compose up -d
```

```bash
docker exec test_mongo mongoimport `
  --db testdb `
  --collection people `
  --type csv `
  --headerline `
  --file /tmp/example.csv
```

Sample CSV
---------

```csv
name,age,city
Alice,30,New York
Bob,25,San Francisco
Charlie,35,Berlin
```

```bash
docker exec -it test_mongo mongosh
# in der MongoDB Shell
use testdb
db.people.find().pretty()
```

![Import Result](images/import_result.png)

### C1F Praktischer Nachweis

> Ich kann Daten in eine NoSQL Datenbank übernehmen.

Ausgangslage
------------

Gegeben ist eine CSV-Datei mit den folgenden Daten:

```csv
Country;Admin1;Admin2;Date;Value;Unit;Variable
United States;Alabama;;02/12/2024;33.00;%;Soil Moisture
United States;Alabama;;09/12/2024;37.00;%;Soil Moisture
United States;Alabama;;16/12/2024;43.00;%;Soil Moisture
United States;Alabama;;23/12/2024;36.00;%;Soil Moisture
United States;Alabama;;30/12/2024;49.00;%;Soil Moisture
```

Und eine JSON-Datei mit den folgenden Daten:

```json
[
  {
    "Country": "United States",
    "Admin1": "Alabama",
    "Admin2": null,
    "Date": "02/12/2024",
    "Value": 33.00,
    "Unit": "%",
    "Variable": "Soil Moisture"
  },
  {
    "Country": "United States",
    "Admin1": "Alabama",
    "Admin2": null,
    "Date": "09/12/2024",
    "Value": 37.00,
    "Unit": "%",
    "Variable": "Soil Moisture"
  }
]
```

Verwendet wird die bereits erstellten `testdb` Datenbank in der MongoDB.

Um die Daten in die `soil_moisture` Collection zu importieren, können folgende Schritte durchgeführt werden:

```bash
// Copy the CSV file to the MongoDB container
docker cp "<path>\csv\soil_moisture.csv" mongodb:/tmp/soil_moisture.csv

docker exec mongodb mongoimport --db weatherdb --collection soil_moisture --type csv --headerline --file /tmp/soil_moisture.csv
```
![alt-text](images/C1F/importCSV.png)

![alt-text](images/C1F/importProof.png)

Die JSON-Datei wird in die `soil_moisture` Collection importiert:

```bash
// Copy the JSON file to the MongoDB container
docker cp "<path>\json\soil_moisture.json" mongodb:/tmp/soil_moisture.json

docker exec mongodb mongoimport --db weatherdb --collection soil_moisture --file /tmp/soil_moisture.json --jsonArray
```

![alt-text](images/C1F/importJSON.png)

![alt-text](images/C1F/importJSONProof.png)



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

- **Was sind Zugriffsberechtigungen in einer NoSQL Datenbank?**  
  Verstehen, wie Benutzer, Rollen und Zugriffsrechte zusammenspielen, um den Zugriff auf Daten zu steuern.
- **Wie werden Benutzer in einer NoSQL Datenbank angelegt und authentifiziert?**  
  Erlernen, wie individuelle Benutzerkonten erstellt werden und welche Authentifizierungsmethoden eingesetzt werden.
- **Welche Funktion haben Rollen und Zugriffsrechte?**  
  Erkennen, wie Rollen zur Bündelung von Berechtigungen verwendet werden und wie Zugriffsrechte konkret festlegen, was ein Benutzer oder eine Rolle tun darf.
- **Wie unterscheidet sich die Zugriffsverwaltung in NoSQL Datenbanken von relationalen Systemen?**  
  Die speziellen Anforderungen und Flexibilitäten der NoSQL-Zugriffsverwaltung im Vergleich zu traditionellen, schema-gebundenen Systemen verstehen.

Umsetzung
=========

![Role Based Access Control](images/rbac.png)

In NoSQL Datenbanken erfolgt die Zugriffskontrolle über ein mehrschichtiges Sicherheitsmodell. Dieses Modell basiert auf der Verwaltung von Benutzern, der Zuweisung von Rollen und der Definition spezifischer Zugriffsrechte.

Benutzerverwaltung
---------------------

**Definition und Bedeutung:**
Benutzer sind individuelle Konten, die zur Authentifizierung benötigt werden. Jeder Benutzer erhält ein Passwort oder andere Authentifizierungsmerkmale, um seine Identität zu bestätigen.

**Authentifizierung:**  

Methoden umfassen Passwörter, Tokens oder Zertifikate, die den sicheren Zugang gewährleisten.

**Beispiel:**  

Ein Benutzerkonto kann folgendermassen definiert sein:

```json
{
  "user": "alice",
  "pwd": "sicheresPasswort123",
  "roles": ["readWrite"]
}
```

Dieses Beispiel zeigt, wie ein Benutzer mit einem Passwort und einer Rolle in der Datenbank definiert wird.

```js
db.createUser({
  user: "alice",
  pwd: "sicheresPasswort123",
  roles: [{ role: "readWrite", db: "testdb" }]
});

```

  Dieses Beispiel zeigt, wie ein Benutzer zusammen mit seinen zugewiesenen Rollen in der Datenbank definiert wird.

**Rollen:**  

- Rollen fassen mehrere Zugriffsrechte zusammen und können mehreren Benutzern zugewiesen werden.  
- Sie vereinfachen die Verwaltung, indem sie Berechtigungen zentral definieren.
**Zugriffsrechte:**  

- Zugriffsrechte bestimmen, welche Operationen (wie Lesen, Schreiben, Aktualisieren oder Löschen) ein Benutzer oder eine Rolle ausführen darf.  
- Typische Rechte sind beispielsweise `read`, `write`, `dbAdmin` und `clusterAdmin`.

**Beispiel:**  
Eine Rolle mit Lese- und Schreibrechten könnte folgendermassen aussehen:

```json
{
  "role": "readWrite",
  "db": "testdb",
  "privileges": [
    { "resource": { "db": "testdb", "collection": "documents" }, "actions": ["find", "insert", "update", "remove"] }
  ],
  "roles": []
}
```

Dieses Beispiel verdeutlicht, wie Rollen Zugriffsrechte bündeln und gezielt zugewiesen werden können.

Zugriffskontrolle in NoSQL Datenbanken
---------------------

**Implementierung:**  

- Die Zugriffskontrolle erfolgt durch interne Sicherheitsmodelle, wie zum Beispiel den Authentifizierungsmechanismus in MongoDB.  
- Administratoren definieren, welche Benutzer und Rollen existieren und welche spezifischen Rechte ihnen zugewiesen werden.

**Unterschied zu relationalen Datenbanken:**

- Relationale Datenbanken besitzen oft ein festes, tabellenbasiertes Rollenkonzept.  
- NoSQL Datenbanken bieten mehr Flexibilität, um den verteilten und dynamischen Charakter moderner Anwendungen zu unterstützen.

Wichtige Begriffe und Strukturen
---------------------

**Benutzer:**  
Individuelle Konten, die zur Authentifizierung und Autorisierung in der Datenbank verwendet werden.

**Rollen:**  
Gruppen von Zugriffsrechten, die mehreren Benutzern zugeordnet werden können.

**Zugriffsrechte:**  
Bestimmen, welche Aktionen (z. B. lesen, schreiben, administrieren) ein Benutzer oder eine Rolle durchführen darf.

**Authentifizierung:**  
Der Prozess, durch den die Identität eines Benutzers überprüft wird.

**Autorisierung:**  
Der Prozess, der festlegt, welche Operationen ein authentifizierter Benutzer ausführen darf.

### D1F

> Ich kann vordefinierte Zugriffsberechtigungen in einer NoSQL Datenbank umsetzen.

Fragenstellung und Lernziele
==============
- **Welche Methoden gibt es, um vordefinierte Rollen und Berechtigungen in einer NoSQL Datenbank zu definieren und anzuwenden?** Ich kann verschiedene Ansätze aufzählen und kurz beschreiben.  
- **Wie wird die Einrichtung von Rollen und Nutzern praktisch umgesetzt?** Ich kann den Einsatz von Shell‑Befehlen und GUI‑Tools erläutern.  
- **Welche Formate und Tools werden für die Definition von Rollen genutzt?** Ich kann die Nutzung von JSON‑Dateien und programmgesteuerten Skripten erklären.  
- **Wie kann man die korrekte Funktionsweise der Berechtigungen validieren?** Ich kann Prüf‑Abfragen und Tests beschreiben, um zu verifizieren, dass die Berechtigungen greifen.

Umsetzung
=========
Zugriffsberechtigungen in einer NoSQL-Datenbank sind essenziell, um die Sicherheit und Integrität der Daten zu gewährleisten. Sie ermöglichen es, den Zugriff auf Datenbankressourcen gezielt zu steuern und sicherzustellen, dass Benutzer nur die Rechte erhalten, die sie für ihre Aufgaben benötigen. 

Die Umsetzung erfolgt typischerweise durch die Definition von Rollen, die spezifische Berechtigungen bündeln, und die Zuweisung dieser Rollen an Benutzer. Dabei gibt es verschiedene Methoden, um diese Zugriffsberechtigungen zu implementieren:

- **Shell‑Befehle:**  
  Über die Kommandozeile der Datenbank (z. B. mongo Shell) können Rollen mit `db.createRole()` definiert und Nutzern mit `db.createUser()` zugewiesen werden. Dies ist besonders nützlich für Administratoren, die direkten Zugriff auf die Datenbank haben.

- **GUI‑basierte Tools:**  
  Tools wie **MongoDB Compass** oder **Mongo Express** bieten eine benutzerfreundliche Oberfläche, um Rollen und Berechtigungen zu verwalten. Diese Methode eignet sich gut für Benutzer, die weniger Erfahrung mit der Kommandozeile haben.

- **Programmgesteuerte Einrichtung:**  
  Mit Skripten in Programmiersprachen wie JavaScript (Node.js) oder Python können Rollen und Benutzer automatisiert erstellt werden. Dies ist besonders hilfreich in DevOps-Umgebungen, in denen wiederholbare Prozesse erforderlich sind.

Die korrekte Funktionsweise der Berechtigungen kann durch gezielte Prüfungen und Tests validiert werden. Dazu gehört beispielsweise das Überprüfen, ob ein Benutzer nur auf die ihm erlaubten Ressourcen zugreifen kann.

Zugriffsberechtigungen in einer NoSQL-Datenbank sind essenziell, um Datenzugriffe zu kontrollieren und sicherzustellen, dass Benutzer nur die für ihre Rolle erforderlichen Rechte erhalten. MongoDB – als eine der populärsten NoSQL-Datenbanken – setzt dabei auf ein rollenbasiertes Berechtigungssystem (RBAC – Role-Based Access Control).

Eine **Rolle (Role)** ist eine definierte Sammlung von Rechten (Privilegien), die bestimmte Aktionen (z. B. Lesen, Schreiben, Löschen) auf einer bestimmten Ressource (Datenbank, Collection) erlauben. Diese Rollen können vordefiniert oder benutzerdefiniert sein und werden anschliessend einzelnen Benutzern zugewiesen.

Methoden zur Definition und Anwendung von Rollen und Berechtigungen
-------------------

**Manuell über die Shell (z. B. `mongosh`)**

- Direktes Ausführen von Kommandos wie `db.createRole()` und `db.createUser()`.
- Flexibel und vollständig, aber erfordert gute Kenntnisse der MongoDB-Syntax.
- Ideal für Administratoren, Skripting oder Testumgebungen.

**Vordefinierte Rollen verwenden**

- MongoDB bringt eine Reihe **vordefinierter Rollen** mit, z. B.:
  - `read`, `readWrite`, `dbAdmin`, `userAdmin`, `clusterAdmin` usw.
- Diese decken typische Nutzungsszenarien ab und sparen Aufwand bei der Rollenerstellung.
- Vorteil: schnell einsetzbar, sicher getestet.
- Nachteil: weniger granular – z. B. `readWrite` erlaubt sofort alle Schreiboperationen.

**Benutzerdefinierte Rollen (`db.createRole`)**

- Erlaubt fein abgestimmte Rechte, z. B. nur `find` und `aggregate` auf eine bestimmte Collection.
- Ressourcen können auf Datenbank- oder Collection-Ebene eingeschränkt werden.
- Sehr gut geeignet für Sicherheitsanforderungen in produktiven Umgebungen.

**Rollen- und Benutzerverwaltung über GUI-Tools**

- Tools wie **MongoDB Compass** oder **Mongo Express** ermöglichen das Erstellen und Zuweisen von Rollen über eine grafische Oberfläche.
- Besonders nützlich für Teams ohne tiefe MongoDB-Kenntnisse.
- Einschränkung: Nicht alle Optionen sind über die GUI zugänglich (z. B. komplexe Privilegienfilter).

**Automatisierung durch Skripte oder Infrastructure-as-Code**

- Einsatz von Setup-Skripten (`init.js`), Docker-Volumen oder Konfigurationsmanagement (Ansible, Terraform).
- Ideal für DevOps und CI/CD: Rollen und Benutzer werden bei jedem Deployment automatisch eingerichtet.
- Vorteil: Wiederholbarkeit, Versionskontrolle.
- Nachteil: Initial höherer Aufwand zur Erstellung der Skripte.

Beispiel: Erstellung und Zuweisung einer Rolle in MongoDB
--------------------

Erstelle eine Rolle `readOnlyExample`, die ausschliesslich Leserechte für `testdb` hat.  
Erstelle anschliessend den Benutzer `readUser`, weise ihm diese Rolle zu und überprüfe, dass:

- Lesender Zugriff funktioniert ✅  
- Schreibender Zugriff verweigert wird ❌

Vorbereitung
------------

Container:

```yaml
services:
  mongodb:
    image: mongo:8.0
    container_name: test_mongo
    command: ["mongod", "--auth"]
    environment:
      MONGO_INITDB_ROOT_USERNAME: root
      MONGO_INITDB_ROOT_PASSWORD: example
    ports:
      - "27017:27017"
    volumes:
      - mongo_data:/data/db
      - ./example.csv:/tmp/example.csv:ro
    restart: unless-stopped

volumes:
  mongo_data:
```

Data:

```csv
name,age,city
Alice,30,New York
Bob,25,San Francisco
Charlie,35,Berlin  
```
  
Import:

```powershell
docker exec test_mongo mongoimport `
  --username root `
  --password example `
  --authenticationDatabase admin `
  --db testdb `
  --collection people `
  --type csv `
  --headerline `
  --file /tmp/example.csv
```

Ausführung
------------

**1. Rolle erstellen:**
Verbinde dich mit der Admin-Datenbank:

```bash
docker exec -it test_mongo mongosh
```

Dann führe in der `testdb` aus:

```bash
use testdb

db.createRole({
  role: "readOnlyExample",
  privileges: [
   {
    resource: { db: "testdb", collection: "" },
    actions: ["find"]
   }
  ],
  roles: []
})
```

**2. Benutzer erstellen und Rolle zuweisen:**

```js
db.createUser({
  user: "readUser",
  pwd: "readonlypass",
  roles: [{ role: "readOnlyExample", db: "testdb" }]
})
```

**3. Test: Leserechte prüfen**

Anmelden als `readUser`:

```bash
docker exec -it test_mongo mongosh --username readUser --password readonlypass --authenticationDatabase testdb --eval "use testdb"
```

Dann:

```js
use testdb
db.people.find().pretty()
```

✅ Ausgabe sollte Dokumente anzeigen, falls vorhanden.

**4. Test: Schreibrechte prüfen**

```js
db.people.insert({
  name: "Kate ",
  age: 30,
  city: "Los Angeles"
});
```

❌ Fehlermeldung wie z. B.:

```
WriteError: not authorized on testdb to execute command
```

Dies zeigt, dass nur Leserechte bestehen und die Rolle korrekt funktioniert.


Wichtige Begriffe und Strukturen
---------------------
- **Rolle (Role):** Vordefinierte Sammlung von Privilegien, z. B. Lese‑ oder Schreibrechte.  
- **Privileg (Privilege):** Einzelne Berechtigung (z. B. `find`, `insert`), zugewiesen für eine Datenbank und Collection.  
- **Authentifizierung (Authentication):** Verifizierung der Nutzeridentität (z. B. Passwort).  
- **Autorisierung (Authorization):** Prüfung, ob ein authentifizierter Nutzer eine Aktion ausführen darf.

Nachweis
========

**Praktische Übung:**  
Erstelle eine Rolle mit spezifischen Rechten und weise sie einem Benutzer zu.

![Create Role Nachweis](images/create_role_nachweis.png)

Teste die Rolle, indem du versuchst, Daten zu lesen und zu schreiben. Stelle sicher, dass die Leserechte funktionieren und Schreibrechte verweigert werden.

![Test Role Nachweis](images/test_role_nachweis.png)

### D1F Praktischer Nachweis

Erstelle eine Rolle dataEditor, die für die Datenbank productdb in der Collection inventory nur Lese- und Schreibrechte besitzt (kein Löschen).
Erstelle anschliessend den Benutzer editorUser, weise ihm diese Rolle zu und überprüfe, dass:

- Lesen ✅
- Schreiben ✅
- Löschen ❌ nicht erlaubt ist

Vorbereitung
==========

**Docker Container:**

```yml
services:
  mongodb:
    image: mongo:8.0
    container_name: editor_mongo
    command: ["mongod", "--auth"]
    environment:
      MONGO_INITDB_ROOT_USERNAME: root
      MONGO_INITDB_ROOT_PASSWORD: example
    ports:
      - "27018:27017"
    volumes:
      - mongo_data:/data/db
      - ./products.csv:/tmp/products.csv:ro
    restart: unless-stopped

volumes:
  mongo_data:
```

**Daten (CSV):**

```csv
product,price,quantity
Laptop,1200,5
Mouse,25,50
Keyboard,45,30
```

**Import:**

```bash
docker exec editor_mongo mongoimport `
  --username root `
  --password example `
  --authenticationDatabase admin `
  --db productdb `
  --collection inventory `
  --type csv `
  --headerline `
  --file /tmp/products.csv
```

Ausführung
==========

**1. Rolle erstellen:**

Öffne die Mongo-Shell:

```bash
docker exec -it editor_mongo mongosh -u root -p example --authenticationDatabase admin
```

![login admin](images/d1f/login_admin.png)

Dann in der productdb:

```bash
use productdb
```

```js
db.createRole({
  role: "dataEditor",
  privileges: [
    {
      resource: { db: "productdb", collection: "inventory" },
      actions: ["find", "insert", "update"]
    }
  ],
  roles: []
});
```

![create role](images/d1f/create_role.png)

2. Benutzer mit dieser Rolle erstellen

```js
db.createUser({
  user: "editorUser",
  pwd: "editpass123",
  roles: [{ role: "dataEditor", db: "productdb" }]
});
```

![create user](images/d1f/create_user.png)

3. Test: Leserechte prüfen

```bash
docker exec -it editor_mongo mongosh `
  --username editorUser `
  --password editpass123 `
  --authenticationDatabase productdb
```

![login user](images/d1f/login_user.png)

Dann:

```js
use productdb
db.inventory.find().pretty()
```

![find all](images/d1f/find_all.png)


4. Test: Schreibrechte (Update & Insert)

Insert:

```js
db.inventory.insertOne({
  product: "Monitor",
  price: 200,
  quantity: 10
});
```	

![insert](images/d1f/insert_one.png)

Update:

```js
db.inventory.updateOne(
  { product: "Mouse" },
  { $set: { price: 30 } }
);
```

![update](images/d1f/update.png)

5. Test: Löschversuch
```js
db.inventory.deleteOne({ product: "Keyboard" });
```

![delete](images/d1f/delete.png)

Zusammenfassung
------------

Mit dieser Konfiguration wurde eine benutzerdefinierte Rolle erstellt, die gezielte Rechte auf eine Collection gewährt. Das verhindert unbeabsichtigte oder böswillige Löschoperationen – ein nützliches Prinzip für die Rechtevergabe in produktiven MongoDB-Systemen.

### D1E

> Ich kann ein Konzept für Zugriffsberechtigungen einer NoSQL Datenbank entwerfen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

## Backup erstellen Restore durchführen

Warum ist ein Backup wichtig?
-----------------------------

Ein **Backup** ist eine **Sicherungskopie** von Daten, die im Falle eines Datenverlusts oder einer Beschädigung wiederhergestellt werden kann. Es ist wichtig, regelmässig Backups zu erstellen, um Datenverluste zu vermeiden und die **Integrität** und **Verfügbarkeit** der Daten zu gewährleisten.

### E1G

> Ich kann Konzepte für ein Backup einer NoSQL Datenbank erläutern. (z. B. on-demand snapshots, continous cloud backups, legacy backups)

Fragenstellung und Lernziele
==============

- Was sind die Konzepte für ein Backup einer NoSQL Datenbank?
- Wie kann ich ein Backup einer NoSQL Datenbank erstellen?
- Wie kann ich ein Restore einer NoSQL Datenbank durchführen?

- Ich kann die Konzepte für ein Backup einer NoSQL Datenbank erläutern.

Umsetzung
=========

Konzepte für ein Backup einer NoSQL Datenbank
---------------------------------------------

| Kozept   | Beschreibung   |
| :--------- | :--------- |
| On-Demand Snapshots     | Manuelle Erstellung von Snapshots zu bestimmten Zeitpunkten     |  
| Continuous Cloud Backups     | Automatische Sicherung der Datenbank in der Cloud     |  
| Legacy Backups     | Traditionelle Backup-Methoden wie regelmässige Datensicherungen auf Festplatten     |  
| Point-in-Time Recovery     | Wiederherstellung der Datenbank auf einen bestimmten Zeitpunkt     |  

![backup](/images/nosqlbackup.png)

SQL vs. NoSQL Backup
---------------------

| Fall | SQL Backup   | NoSQL Backup   |
| :--------- | :--------- | :--------- |
| Methode | **Datensicherungen** und **Transaktionsprotokolle**     | **Snapshots**, **Replikation** und **Cloud-Backups**     |
| Vorteile | Einfach zu implementieren, bewährte Methoden     | Skalierbar, effizient, automatisiert     |
| Nachteile | Langsam, nicht für grosse Datenmengen geeignet     | Komplexer, erfordert spezielle Tools und Kenntnisse     |
|Anwendung | Kleine bis mittlere Datenbanken, Transaktionsdaten     | Grosse Datenbanken, Big Data, Echtzeitanalysen     |
| Beispiel | SQL Server, MySQL     | MongoDB, Cassandra     |
| Wiederherstellung | Transaktionsprotokolle, Datensicherungen     | Snapshots, Replikation, Cloud-Backups     |
| Skalierbarkeit | Vertikal, begrenzt     | Horizontal, unbegrenzt     |
| Performance | Abhängig von der Hardware     | Abhängig von der Konfiguration     |
| Kosten | Lizenzgebühren, Wartung     | Cloud-Abonnement, Speicherplatz     |
| Support | Herstellerunterstützung     | Community, Dokumentation     |
| Zukunft | Stabil, bewährt     | Innovativ, wachsend     |
| Management | Einfach, traditionell     | Komplex, modern     |

Wie kann ich ein Backup einer NoSQL Datenbank erstellen?
--------------------------------------------------------

Die Erstellung eines Backups einer NoSQL-Datenbank kann je nach Datenbank und Umgebung unterschiedlich sein. Im Allgemeinen gibt es jedoch folgende Schritte:

-> Erstellen eines Snapshots der Datenbank, um den aktuellen Zustand zu sichern.

-> Speichern des Snapshots an einem sicheren Ort, z. B. in der Cloud oder auf einem externen Laufwerk.

-> Überprüfen, ob das Backup erfolgreich erstellt wurde und alle Daten enthalten sind.

Wie kann ich ein Restore einer NoSQL Datenbank durchführen?
----------------------------------------------------------

-> Wiederherstellen des Backups aus dem gespeicherten Snapshot.

-> Überprüfen, ob das Restore erfolgreich war und die Datenbank wiederhergestellt wurde.

-> Testen der Wiederherstellung, um sicherzustellen, dass alle Daten korrekt wiederhergestellt wurden.

Links
========

> https://n2ws.com/blog/database-backup

### E1F

> Ich kann ein Backup und Restore bei einer NoSQL Datenbank anwenden.

Fragenstellung und Lernziele
==============

In dieser Übung lernt man, wie man eine MongoDB-Datenbank sicher sichert und wiederherstellt. Folgende Lernziele stehen im Fokus:

- Ein vollständiges Backup mit mongodump durchzuführen
- Die Datenbank mit mongorestore wiederherzustellen
- Die Datenintegrität nach dem Restore zu verifizieren

Umsetzung
=========

1. **MongoDB-Container mit Authentifizierung aufsetzen:**

Du kannst für diese Übung den Container aus dem Kaptitel [G1F - Anbindung and eine NoSQL Datenbank](#g1f) verwenden.

Falls du den Container nicht mehr hast, folge dem Setup Guide aus dem verlinkten Kapitel.

2. **Backup der Datenbank erstellen:**

Mit diesem Befehl wird ein Verzeichnis /backup/productsdb_backup im Container (und auf dem Host unter /backup) angelegt:

```bash
docker exec products mongodump `
  --username admin `
  --password secret123 `
  --authenticationDatabase admin `
  --db productsdb `
  --out /backup/productsdb_backup
```

Logge dich in den Container ein und überprüfe, ob das Backup erfolgreich erstellt wurde:

```bash
docker exec -it products bash
ls -l /backup
```

3. **Datenbank löschen:**

```bash
docker exec products mongosh `
  --username admin `
  --password secret123 `
  --authenticationDatabase admin `
  --eval 'db.getSiblingDB("productsdb").dropDatabase()'
```

Überprüfe, ob die Datenbank gelöscht wurde:

```bash
docker exec products mongosh `
  --username admin `
  --password secret123 `
  --authenticationDatabase admin `
  --eval 'db.getSiblingDB("productsdb").products.find().toArray()'
```

4. **Datenbank wiederherstellen:**

```bash
docker exec products mongorestore `
  --username admin `
  --password secret123 `
  --authenticationDatabase admin `
  --drop `
  /backup/productsdb_backup
```

Die Datenbank sollte nun wiederhergestellt sein. Überprüfe dies mit:

```bash
docker exec products mongosh `
  --username admin `
  --password secret123 `
  --authenticationDatabase admin `
  --eval 'db.getSiblingDB("productsdb").products.find().toArray()'
```

Nachweis
========

**Datenbank Backup:**

![Datenbank backup](images/e1f/backup.png)

**Datenbank löschen:**

![Datenbank löschen](images/e1f/drop_db.png)

**Überprüfen der Löschung:**
![Überprüfen der Löschung](images/e1f/verify.png)

**Datenbank wiederherstellen:**
![Datenbank wiederherstellen](images/e1f/restore.png)

**Datenbank wiederherstellen:**
![Bestätigen der Wiederherstellung](images/e1f/proof.png)

### E1E

> Ich kann ein Konzept für das Backup einer NoSQL Datenbank erstellen.

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========

## Skalierung und Replikation bei einer NoSQL Datenbank anwenden

Skalierung und Replikation sind wichtige Konzepte in der Datenbanktechnologie, um die Leistungsfähigkeit und Verfügbarkeit von Datenbanken zu verbessern. In diesem Kapitel lernst du, wie du NoSQL-Datenbanken skalierst und replizierst, um mit wachsenden Datenmengen und Benutzeranfragen umzugehen.

### F1G

> Ich kann das Prinzip der Skalierung und die unterschiedlichen Replikationsarten für eine NoSQL Datenbank erläutern. (z. B. Multimaster, primary and replica, Aktiv-Passiv und horizontale Skalierung)

Fragenstellung und Lernziele
==============

- Was sind die Prinzipien der Skalierung und Replikation bei NoSQL Datenbanken?
- Wie funktionieren die unterschiedlichen Replikationsarten?
- Welche Vorteile bieten Skalierung und Replikation für NoSQL Datenbanken?

- Ich kann das Prinzip der Skalierung und die unterschiedlichen Replikationsarten für eine NoSQL Datenbank erläutern.

Umsetzung
=========

Skalierung
----------

Erhöhung der Kapazität und Leistungsfähigkeit einer Datenbank, um mit wachsenden Datenmengen und Benutzeranfragen umzugehen.

![scaling](/images/scaling.png)

Replikation
-----------

Erstellung und Aufrechterhaltung von Kopien von Daten, um die Verfügbarkeit und Zuverlässigkeit zu verbessern.

Unterschiedliche Replikationsarten
---------------------------------

| Replikation   | Beschreibung   |
| :--------- | :--------- |
| Multimaster-Replikation     | Mehre Master-Knoten, die gleichzeitig schreibend auf die Datenbank zugreifen können     |
| Primary and Replica-Replikation     | Ein primärer Knoten, der schreibend auf die Datenbank zugreift, und mehrere Replikationsknoten, die lesend auf die Datenbank zugreifen     |
| Aktiv-Passiv-Replikation     | Ein aktiver Knoten, der schreibend auf die Datenbank zugreift, und ein passiver Knoten, der als Backup dient     |

![replication](images/replication.png)

Vorteile von Skalierung und Replikation
--------------------------------------

- **Höhere Verfügbarkeit**: Durch Replikation können Datenbanken auch bei Ausfällen eines Knotens weiterhin verfügbar sein.
- **Bessere Leistung**: Skalierung ermöglicht es, die Leistungsfähigkeit der Datenbank zu erhöhen, um mit wachsenden Anforderungen Schritt zu halten.

### F1F

> Ich kann für eine NoSQL Datenbank eine Replikation anwenden.

Lernziele
==============

- Replikation in NoSQL einer Datenbanken verstehen.
- Replikation in NoSQL einer Datenbanken anwenden.
- Replikation in NoSQL einer Datenbanken testen.

Umsetzung
=========

Replikation verstehen
---------------------

Replikation ist der Prozess, bei dem Daten von einem Knoten (Master) auf einen oder mehrere andere Knoten (Replikate) kopiert werden. Dies geschieht in der Regel in Echtzeit oder nahezu in Echtzeit, um sicherzustellen, dass alle Knoten über die aktuellsten Daten verfügen.

Replikation anwenden mit MongoDB
--------------------

1. **Erstellen eines Replica Sets**:  
   Ein Replica Set ist eine Gruppe von MongoDB-Instanzen, die dieselben Daten enthalten. Um ein Replica Set zu erstellen, müssen mindestens drei Knoten vorhanden sein.
   Repilca Set ist eine Primary and Replica replication, das heisst, dass ein Knoten als primär fungiert und die anderen Knoten als Replikate fungieren.

2. **Konfigurieren der Knoten**:  
   Jeder Knoten im Replica Set muss konfiguriert werden, um sicherzustellen, dass er als Replikat oder primärer Knoten fungiert.

3. **Starten des Replica Sets**:

    Um das Replica Set zu starten, den Befehl `rs.initiate()` in der MongoDB-Shell verwenden.

4. **Überprüfen des Replica Sets**:

    Den Befehl `rs.status()` verwenden, um den Status des Replica Sets zu überprüfen und sicherzustellen, dass alle Knoten korrekt verbunden sind.

5. **Testen der Replikation**:
    Daten in den primären Knoten einfügen und überprüfen, ob sie auf den Replikaten verfügbar sind.


Umsetzung
=========

Docker-Container für MongoDB Replica Set erstellen

```yml

services:
  mongo1:
    image: mongo
    container_name: mongo1
    ports:
      - "27017:27017"
    command: ["mongod", "--replSet", "rs0"]
  
  mongo2:
    image: mongo
    container_name: mongo2
    ports:
      - "27018:27017"
    command: ["mongod", "--replSet", "rs0"]
  
  mongo3:
    image: mongo
    container_name: mongo3
    ports:
      - "27019:27017"
    command: ["mongod", "--replSet", "rs0"]

```

Verbindung zu mongo1

```bash
docker exec -it mongo1 mongosh
```

Replica Set initialisieren

```bash
rs.initiate({
  _id: "rs0",
  members: [
    { _id: 0, host: "mongo1:27017" },
    { _id: 1, host: "mongo2:27017" },
    { _id: 2, host: "mongo3:27017" }
  ]
})
```
Replica Set überprüfen

```bash
rs.status()
```

Master Knoten bestätigen

```bash
rs.isMaster().ismaster
```
Daten in den primären Knoten einfügen

```bash
use testdb
db.test.insertOne({ message: "replica set test" })
```

Daten auf dem Replikat überprüfen

```bash
docker exec -it mongo2 mongosh

db.getMongo().setReadPref("secondary")

use testdb
db.test.find()
```
Erwartetes Ergebnis

```json
{ _id: ObjectId(...), message: "replica set test" }
```

Nachweis
========

Replica Set initialisieren
--------------------------
![alt-text](images/f1f/initiateSet.png)

Status Check
--------------------------
![alt-text](images/f1f/statusCheck.png)

Daten in den primären Knoten einfügen
---------------------------
![alt-text](images/f1f/injectDataInMaster.png)

Daten auf dem Replikat überprüfen
---------------------------
![alt-text](images/f1f/checkSecondaryForData.png)


### F1E

> Ich kann ein Konzept für die Skalierung einer NoSQL Datenbank erstellen.

Lernziele
==============

- Skalierung in NoSQL einer Datenbanken verstehen.
- Analyse der Skalierungsmöglichkeiten in NoSQL einer Datenbanken machen.
- Konzept für die Skalierung in NoSQL einer Datenbanken erstellen.

Umsetzung
=========

Skalierung in NoSQL-Datenbanken
-----------------------------

In den letzten beiden Kapiteln haben wir die Grundlagen der Replikation und Skalierung in NoSQL-Datenbanken behandelt. 
Skalierung ist ein entscheidender Aspekt, um die Leistungsfähigkeit und Verfügbarkeit von NoSQL-Datenbanken zu gewährleisten.
Replicasets ermöglichen es, Daten über mehrere Knoten zu verteilen und so die Last zu verteilen.

Analyse der Skalierungsmöglichkeiten
----------------------------- 

Die Skalierungsmöglichkeiten in NoSQL-Datenbanken können in zwei Hauptkategorien unterteilt werden:

- **Vertikale Skalierung (Scale Up)**:

  Hierbei wird die Kapazität eines einzelnen Knotens erhöht, indem mehr Ressourcen (CPU, RAM, Speicher) hinzugefügt werden. Dies ist einfach umzusetzen, hat aber Grenzen in Bezug auf Hardware und Kosten.

- **Horizontale Skalierung (Scale Out)**:

  Hierbei werden mehrere Knoten hinzugefügt, um die Last zu verteilen. Dies ermöglicht eine nahezu unbegrenzte Skalierung, da neue Knoten einfach hinzugefügt werden können. NoSQL-Datenbanken sind in der Regel für horizontale Skalierung optimiert.

Konzept für die Skalierung in NoSQL-Datenbanken
-----------------------------

Ein Konzept für die Skalierung in NoSQL-Datenbanken sollte folgende Aspekte berücksichtigen:

- **Anforderung der Skalierung**:

  Zunächst sollte die erwartete Last und das Wachstum der Datenbank analysiert werden. Dies hilft, die geeignete Skalierungsstrategie zu wählen.

- **Lastverteilung**: 

  Die Last sollte gleichmässig auf alle Knoten verteilt werden, um Engpässe zu vermeiden. Dies kann durch Sharding erreicht werden, bei dem Daten in kleinere Teile (Shards) aufgeteilt und über mehrere Knoten verteilt werden.

- **Replikation**:

  Replikation sollte implementiert werden, um die Verfügbarkeit und Fehlertoleranz zu erhöhen. Ein Replica Set ermöglicht es, Daten über mehrere Knoten zu replizieren, sodass bei einem Ausfall eines Knotens die Daten weiterhin verfügbar sind.

- **Monitoring und Skalierung**:

  Ein effektives Monitoring-System sollte implementiert werden, um die Leistung der Knoten zu überwachen und bei Bedarf neue Knoten hinzuzufügen. Automatisierte Skalierung kann helfen, die Ressourcen dynamisch anzupassen, basierend auf der aktuellen Last.

Mit diesen Konzepten kann eine NoSQL-Datenbank effizient skaliert werden, um den Anforderungen moderner Anwendungen gerecht zu werden.

Visualisierung
------------------------------

![scaling](images/scalingConcept.png)


## Anbindung an NoSQL Datenbank erstellen

### G1G

> Ich kann das Prinzip des Zugriffes bei einer NoSQL Datenbank erläutern. (z. B. Queries, Projections)

Fragenstellung und Lernziele
==============
- **Was versteht man unter einer Query in einer NoSQL Datenbank?**  

  Erklären, wie Queries als Abfragebefehle genutzt werden, um gezielt Daten aus einer Datenbank zu filtern.
- **Wie funktionieren Projections und welchen Zweck erfüllen sie?**  

  Verstehen, wie Projections dazu verwendet werden, die zurückgegebenen Felder einer Query zu bestimmen, um die Ergebnismenge zu optimieren.
- **Wie interagieren Queries und Projections miteinander?**  

  Erkennen, dass Queries zur Auswahl von Datensätzen dienen und Projections zur Steuerung des Inhalts der Ergebnisse.
- **Welche speziellen Operatoren und Syntaxelemente kommen in NoSQL-Abfragen zum Einsatz?**  

  Die gängigen Operatoren (z. B. `$eq`, `$gt`, `$in`) und die JSON-basierte Abfragesyntax kennenlernen.

Umsetzung
=========

In NoSQL Datenbanken wie MongoDB erfolgt der Datenzugriff primär über **Queries**. Diese ermöglichen es, mit Hilfe einer JSON-artigen Syntax gezielt Dokumente aus Collections auszuwählen. Ergänzend dazu kommen **Projections** zum Einsatz, um festzulegen, welche Felder in den Abfrageergebnissen enthalten sein sollen.

![MYSQL to MongoDB mapping](images/MySQL-to-MongoDB-mapping.jpg)

Queries in NoSQL Datenbanken
---------------------
- **Definition und Funktion:**  
  Eine Query ist ein Abfragebefehl, der Kriterien zur Auswahl von Dokumenten definiert.  
- **Syntax und Operatoren:**

  - Abfragen werden in einer JSON-ähnlichen Struktur formuliert.  
  - Gängige Operatoren sind beispielsweise:

    - `$eq`: prüft auf Gleichheit.
    - `$gt` / `$lt`: prüfen auf grösser oder kleiner als einen bestimmten Wert.
    - `$in`: prüft, ob ein Wert in einer Liste enthalten ist.

- **Beispiel einer Query:**  
  Um alle Dokumente zu finden, in denen das Feld `status` den Wert `"active"` hat, kann folgende Query verwendet werden:

  ```json
  {
    "status": { "$eq": "active" }
  }
  ```
  Dieses Beispiel demonstriert, wie mit einem einfachen JSON-Kriterium gezielt nach bestimmten Dokumenten gesucht wird.

Projections in NoSQL Datenbanken
---------------------
- **Definition und Zweck:**  
  Projections dienen dazu, die zurückgegebenen Felder einer Query zu bestimmen. Sie helfen, nur relevante Daten abzurufen und reduzieren somit die Menge der übertragenen Informationen.
- **Funktionsweise:** 

  - Durch Angabe einer Projection kann man Felder ein- oder ausschliessen.
  - Typischerweise wird eine 1 für Inklusion und eine 0 für Exklusion verwendet.

- **Beispiel einer Projection:**  
  Um bei der obigen Query nur die Felder `name` und `status` zurückzugeben, kann die Projection wie folgt ergänzt werden:
  ```json
  {
    "name": 1,
    "status": 1,
    "_id": 0
  }
  ```
  Hierbei wird das `_id`-Feld explizit ausgeschlossen, während `name` und `status` in den Ergebnissen enthalten sind.

Zusammenspiel von Queries und Projections
---------------------

![Query und Projection Stages](images/query-w-projection-stages.png)


- **Abfrage und Ergebnisoptimierung:**  
  Zunächst filtert die Query anhand der definierten Kriterien die relevanten Dokumente heraus. Anschliessend wird mit der Projection bestimmt, welche Felder der gefundenen Dokumente im Ergebnis enthalten sein sollen.
- **Vorteile:**  
  - **Effizienz:** Es werden nur die benötigten Daten abgerufen, was Netzwerk- und Verarbeitungsressourcen spart.
  - **Übersichtlichkeit:** Die Ergebnisse enthalten nur die für die Anwendung relevanten Informationen.
- **Kombination in der Praxis:**  
  In einem typischen Anwendungsszenario könnte man eine Query mit einer zugehörigen Projection in einem einzigen Befehl kombinieren, um gezielt und effizient Daten zu extrahieren.

Operatoren und Syntaxelemente
---------------------

**Operatoren:**  

- `$eq`: Gleichheit
- `$gt`, `$lt`: Grösser oder kleiner als
- `$in`: Wert in Liste
- `$and`, `$or`: Logische Verknüpfungen


```js
// Beispiel einer komplexen Query mit Projection
db.collection.find(
  {
    "status": { "$eq": "active" },
    "age": { "$gt": 18 },
    "hobbies": { "$in": ["reading", "traveling"] }
  },
  {
    "name": 1,
    "age": 1,
    "hobbies": 1,
    "_id": 0
  }
);
```

Wichtige Begriffe und Strukturen
---------------------
- **Query:**  
  Ein Abfragebefehl in JSON-Form, der Kriterien für die Auswahl von Dokumenten definiert.
- **Projection:**  
  Eine Spezifikation, welche Felder in den Ergebnissen einer Query enthalten sein sollen.
- **Operatoren:**  
  JSON-basierte Schlüssel wie `$eq`, `$gt`, `$in` usw., die zum Vergleich und zur Filterung von Daten verwendet werden.
- **JSON-Syntax:**  
  Die standardisierte Form zur Darstellung von Daten, die in NoSQL-Abfragen genutzt wird.

Fazit
========
Das Zugriffsprinzip in NoSQL Datenbanken basiert auf einem flexiblen und leistungsfähigen Abfragesystem:
- **Queries** ermöglichen die gezielte Auswahl von Dokumenten durch definierte Filterkriterien.
- **Projections** steuern, welche Felder der abgefragten Dokumente zurückgegeben werden, wodurch die Effizienz und Übersichtlichkeit der Ergebnisse verbessert wird.

Dieses Prinzip erlaubt es, mit minimalem Aufwand präzise und ressourcenschonende Datenzugriffe in NoSQL Umgebungen zu realisieren.

Nachweis
========

### G1F

> Ich kann eine Anbindung an eine NoSQL Datenbank implementieren. (z. B. API)

Fragenstellung und Lernziele
==============


In dieser Uebung geht es darum, eine minimalistische API in TypeScript und Express zu erstellen, die eine Verbindung zu einer MongoDB herstellt. Dabei sollen folgende Lernziele erreicht werden:

- Einrichten eines Docker-Containers mit aktivierter Authentifizierung
- Importieren von CSV-Daten in eine NoSQL-Datenbank
- Konfigurieren einer Datenbank (testdb) und einer Collection (people) mit den Feldern name, age, city
- Implementieren und Testen von REST-Endpunkten (GET und POST)
- Verifizieren von Lese- und Schreibrechten anhand eines Read-Only-Benutzers

Umsetzung
=========

Container Setup
---------------------

Docker-compose Datei erstellen:

```yaml
services:
  mongodb:
    image: mongo:8.0
    container_name: products
    command: ["mongod", "--auth"]
    environment:
      MONGO_INITDB_ROOT_USERNAME: admin
      MONGO_INITDB_ROOT_PASSWORD: secret123
    ports:
      - "27018:27017"
    volumes:
      - ./mongo-data:/data/db
      - ./products.csv:/tmp/products.csv:ro
    restart: unless-stopped
```

Container starten:

```bash
docker compose up -d
```

CSV-Daten:

```csv
productId,name,category,price
P001,Smartphone,Electronics,699.99
P002,Laptop,Electronics,1299.00
P003,Desk Chair,Furniture,149.50
P004,Coffee Mug,Kitchen,12.99
```

Import CSV-Daten in MongoDB:

```bash
docker exec products mongoimport `
  --username admin `
  --password secret123 `
  --authenticationDatabase admin `
  --db productsdb `
  --collection products `
  --type csv `
  --headerline `
  --file /tmp/products.csv
```

Typescript API
---------------------

Wir wollen folgende Endpunkte implementieren:

```bash
GET /people - liefert alle Dokumente

GET /people/:id — liefert ein Dokument per ObjectId

POST /people — legt ein neues Dokument an
```

Projektsetup
---------------------

```bash
pnpm init -y
pnpm add express mongodb dotenv
pnpm add -D typescript @types/express @types/node
pnpm tsc --init
```

`tsconfig.json` Datei erstellen:

```json
{
  "compilerOptions": {
    "target": "ES2020",
    "module": "CommonJS",
    "rootDir": "src",
    "outDir": "dist",
    "strict": true,
    "esModuleInterop": true
  }
}
```

`.env` Datei erstellen:

```bash
MONGO_URI=mongodb://admin:secret123@localhost:27018
DB_NAME=productsdb
PORT=3001
```

API-Code:


```typescript
import express, { Request, Response, NextFunction } from 'express';
import { MongoClient, ObjectId } from 'mongodb';
import dotenv from 'dotenv';

dotenv.config();

const uri = process.env.MONGO_URI;
const dbName = process.env.DB_NAME || 'testdb';
const port = Number(process.env.PORT || 3000);

if (!uri) {
  console.error('Fehler: MONGO_URI nicht gesetzt');
  process.exit(1);
}

const client = new MongoClient(uri, {});

async function main() {
  try {
    await client.connect();
    console.log('✅ Verbunden mit MongoDB');

    const db = client.db(dbName);
    const people = db.collection('people');

    const app = express();
    app.use(express.json());

    // GET /people – alle Datensätze ausgeben
    app.get('/people', async (req: Request, res: Response, next: NextFunction) => {
      try {
        const docs = await people.find().toArray();
        res.json(docs);
      } catch (err) {
        next(err);
      }
    });

    // GET /people/:id – einzelnes Dokument per ID
    app.get('/people/:id', async (req: Request, res: Response, next: NextFunction) => {
      try {
        const { id } = req.params;
        if (!ObjectId.isValid(id)) {
          return res.status(400).json({ error: 'Ungültige ID' });
        }
        const doc = await people.findOne({ _id: new ObjectId(id) });
        if (!doc) {
          return res.status(404).json({ error: 'Nicht gefunden' });
        }
        res.json(doc);
      } catch (err) {
        next(err);
      }
    });

    // POST /people – neuen Datensatz anlegen
    app.post('/people', async (req: Request, res: Response, next: NextFunction) => {
      try {
        const { name, age, city } = req.body;
        if (!name || typeof age !== 'number' || !city) {
          return res.status(400).json({ error: 'Fehlende Felder oder falscher Typ' });
        }
        const result = await people.insertOne({ name, age, city });
        res.status(201).json({ insertedId: result.insertedId });
      } catch (err) {
        next(err);
      }
    });

    // globale Error-Middleware
    app.use((err: Error, req: Request, res: Response, _next: NextFunction) => {
      console.error(err);
      res.status(500).json({ error: 'Interner Serverfehler' });
    });

    app.listen(port, () => {
      console.log(`🚀 Server läuft auf http://localhost:${port}`);
    });
  } catch (err) {
    console.error('Verbindungsfehler:', err);
    process.exit(1);
  }
}

main();
```

`package.json` Skripts ergänzen:

```json
// innerhalb von "scripts":
"build": "tsc",
"start": "node dist/index.js"
```

```bash
pnpm build
pnpm start
```

Nachweis
========

**Praktische Übung:**
![Products](images/curl_products_list.png)

### G1F Praktischer Nachweis

> Ich kann eine Anbindung an eine NoSQL Datenbank implementieren. (z. B. API)

Fragenstellung und Lernziele
==============


In dieser Übung geht es darum, eine minimalistische API in Python und Flask zu erstellen, die eine Verbindung zu einer MongoDB herstellt. Dabei sollen folgende Lernziele erreicht werden:

- Importieren von CSV-Daten in eine NoSQL-Datenbank
- Implementieren und Testen von REST-Endpunkten (GET und POST)

Umsetzung
=========

Container Setup
---------------------

Docker-compose Datei erstellen:

```yaml
services:
  mongodb:
    image: mongo:8.0
    container_name: books-mongo
    command: ["mongod", "--auth"]
    environment:
      MONGO_INITDB_ROOT_USERNAME: admin
      MONGO_INITDB_ROOT_PASSWORD: secret123
    ports:
      - "27018:27017"
    volumes:
      - ./mongo-data:/data/db
      - ./books.csv:/tmp/books.csv:ro
    restart: unless-stopped

  flask-app:
    build: ./flask-app
    container_name: flask-books-api
    ports:
      - "5000:5000"
    environment:
      FLASK_APP: app.py
      FLASK_RUN_HOST: 0.0.0.0
      FLASK_RUN_PORT: 5000
      MONGO_URI: mongodb://admin:secret123@mongodb:27017
      DB_NAME: librarydb
    depends_on:
      - mongodb
```

CSV-Daten:

```csv
isbn,title,author,year
9780140449136,Meditations,Marcus Aurelius,2006
9780261103573,The Hobbit,J.R.R. Tolkien,1937
9780553386790,Thinking\, Fast and Slow,Daniel Kahneman,2011
9780307269997,The Road,Cormac McCarthy,2006
```

Import CSV-Daten in MongoDB:

```bash
docker exec -it books-mongo mongoimport `
  --username admin `
  --password secret123 `
  --authenticationDatabase admin `
  --db librarydb `
  --collection books `
  --type csv `
  --headerline `
  --file /tmp/books.csv
```

Flask API
---------------------

Wir wollen folgende Endpunkte implementieren:

```bash
GET /books - liefert alle Dokumente

GET /books/:id — liefert ein Dokument per ObjectId

POST /books — legt ein neues Dokument an
```

Projektsetup
---------------------

**Layout**

```bash
.
├── docker-compose.yml
├── books.csv
└── flask-app
    ├── Dockerfile
    ├── requirements.txt
    └── app.py
```

**Requirements.txt**

```txt
Flask
pymongo
python-dotenv
```

**Dockerfile**

```dockerfile
FROM python:3.13-slim
WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD ["flask", "run"]
```

API-Code:


```python
import os
from flask import Flask, request, jsonify
from pymongo import MongoClient
from bson.objectid import ObjectId
from dotenv import load_dotenv

load_dotenv()

mongo_uri = os.getenv('MONGO_URI')
db_name = os.getenv('DB_NAME', 'librarydb')

if not mongo_uri:
    raise RuntimeError('MONGO_URI not set')

client = MongoClient(mongo_uri)
db = client[db_name]
books_collection = db['books']

app = Flask(__name__)

@app.route('/books', methods=['GET'])
def get_books():
    books = list(books_collection.find())
    for book in books:
        book['id'] = str(book['_id'])
        del book['_id']
    return jsonify(books), 200

@app.route('/books/<id>', methods=['GET'])
def get_book(id):
    if not ObjectId.is_valid(id):
        return jsonify({'error': 'Invalid ID'}), 400
    book = books_collection.find_one({'_id': ObjectId(id)})
    if not book:
        return jsonify({'error': 'Not found'}), 404
    book['id'] = str(book['_id'])
    del book['_id']
    return jsonify(book), 200

@app.route('/books', methods=['POST'])
def create_book():
    data = request.json
    title = data.get('title')
    author = data.get('author')
    isbn = data.get('isbn')
    year = data.get('year')
    if not title or not author or not isbn or not isinstance(year, int):
        return jsonify({'error': 'Missing fields or wrong types'}), 400
    result = books_collection.insert_one({
        'isbn': isbn,
        'title': title,
        'author': author,
        'year': year
    })
    return jsonify({'insertedId': str(result.inserted_id)}), 201

@app.errorhandler(Exception)
def handle_exception(e):
    return jsonify({'error': 'Internal server error'}), 500

if __name__ == '__main__':
    app.run(
        host=os.getenv('FLASK_RUN_HOST', '0.0.0.0'),
        port=int(os.getenv('FLASK_RUN_PORT', 5000))
    )

```

**Starten der Flask-App**

```bash
docker compose up -d
```

![docker](images/g1f/docker.png)

HTTP-Requests testen
---------------------

**GET /books**

```bash
curl -X GET http://localhost:5000/books
```

![all books](images/g1f/get_books.png)

**POST /books**

```bash
curl -X POST "http://localhost:5000/books" `
    -H "Content-Type: application/json" `
    -d '{
        "isbn": "9780307269997",
        "title": "The Road",
        "author": "Cormac McCarthy",
        "year": 2006
    }'
```

![post book](images/g1f/post_book.png)

**GET /books/:id**

```bash
curl -X GET http://localhost:5000/books/<id>
```

![get by id](images/g1f/get_by_id.png)

### G1E

> Ich kann das Prinzip der parallelen Verarbeitung bei NoSQL Datenbanken anwenden. (z. B. MapReduce Algorithmen)

Fragenstellung und Lernziele
==============

Umsetzung
=========

Nachweis
========
