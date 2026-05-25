# MVC-Webentwicklung in Java

Dieses Repository enthält Ressourcen und Übungen, die dir helfen sollen, die Grundlagen der Webentwicklung in Java mithilfe von **Servlets** und **JSP-Seiten** zu erlernen.

> [!TIPP]
> **Zum vollständigen Kurs:** [https://stahe.github.io/de-java-web-mvc-mai-2006/](https://stahe.github.io/de-java-web-mvc-mai-2006/)

---

## 📖 Einführung

Ziel dieser Ressource ist es, die grundlegenden Konzepte der Webprogrammierung in Java anhand einer **3-Schichten-MVC-Architektur** zu behandeln. Dieses Dokument basiert auf dem Artikel vom Januar 2005 „Webentwicklung in Java mit Eclipse und Tomcat“ und ergänzt diesen um:
* Die Verwendung des **Eclipse WTP**-Plugins.


* Eine Struktur, die auf der **3-Schichten-Architektur** basiert.


* Ein praktisches Beispiel unter Verwendung eines **DBMS**.



## 🏗️ Anwendungsarchitektur

Das Projekt folgt einer dreistufigen Struktur, um die Modularität und Stabilität des Codes zu gewährleisten:

**Web-Schicht [web]** | Schnittstelle, über die der Benutzer die Anwendung steuern und Informationen abrufen kann.

**Business-Schicht [business]** | Enthält die Geschäftslogik. Unabhängig von der Schnittstelle (Web, Konsole usw.) ist dies die stabilste Schicht.

**Datenzugriffsebene [DAO]** | Verwaltet den Zugriff auf persistente Daten (DBMS) oder externe Daten (Sensoren, Netzwerk).


## 🚀 Lernmethoden

Es gibt verschiedene mögliche Ansätze für diesen Inhalt, die von der schnellsten bis zur effektivsten Methode reichen:

1. **Ansatz für Experten:** Installieren Sie die Tools und testen Sie den heruntergeladenen Code direkt (nur für Entwickler, die mit Eclipse/WTP vertraut sind).


2. **Schnellansatz:** Kopieren Sie den Code und fügen Sie ihn gemäß dem Dokument ein. So kommen Sie schnell voran, aber einige Konzepte könnten „rätselhaft“ bleiben.


3. **Geführter Ansatz:** identisch mit Methode 2, aber konsultiere das Referenzdokument `[ref1]` (Einführung in die Webprogrammierung mit Java) jedes Mal, wenn dies empfohlen wird.


4. **Empfohlener Ansatz:** Geben Sie den gesamten Code manuell ein und lesen Sie dabei aufmerksam mit. Dies ist die effektivste Methode, um die Logik zu verstehen und eigene Syntaxfehler zu korrigieren.

