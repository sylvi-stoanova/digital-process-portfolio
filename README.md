# Mini Case Study: Digitalisierung eines Verwaltungsprozesses

|Prozessanalyse | Digitale Lösungskonzepte | Test & Evaluation|

## Ausgangssituation

Eine kommunale Servicestelle erhält Bürgeranfragen per E-Mail.
Die eingehenden Anfragen werden von Mitarbeitenden gesichert und anschließend der zuständigen Fachabteilung zugeordnet. 
Diese Mini Case Study untersucht, wie dieser bestehende Prozess durch einen digitalen Lösungsansatz unterstützt werden kann.
Im Mittelpunkt steht dabei nicht die vollständige Automatisierung des Prozesses, sondern die sinnvolle Unterstützung der Mitarbeitenden bei einem wiederkehrenden Arbeitsschritt.

## Zielsetzung

Für die Zuordnung eingehnder Anfragen wird ein kleiner digitaler Lösungsansatz konzipiert und 
als Proof of Concept getestet.
Der Lösungsansatz analysiert eine eingehende Anfrage und schlägt eine von drei möglichen Fachabteilungen vor.
Der weitere Prozess bleibt unter menschlicher Kontrolle:

1. Digitale Analyse der Anfrage
2. Vorschlag einer zuständigen Fachabteilung
3. Prüfung durch einen Mitarbeitenden
4. Bestätigung oder Korrektur der Zuordnung
5. Dokumentation des Ergebnisses

# Prozessprinzip

**Eingehende Anfrage → Digitale Vorprüfung → Zuordnungsvorschlag**

**→ Menschliche Prüfung → Bestätigung / Korrektur → Dokumentation**

> **Leitgedanke:** Technologie unterstützt den Verwaltungsprozess. Fachliche Kontrolle und Entscheidung verbleiben beim Menschen.


**Projektart:** Mini Proof of Concept
**Testdaten:** ausschließlich fiktive Daten
**Schwerpunkte:** Prozessanalyse, Digitalisierung, Anforderungsdefinition, Teststellung, Human-in-the-Loop


---

## Soll-Prozess

Der bestehende manuelle Prozess wird um eine digitale Vorprüfung ergänzt. Ziel ist es, die Zuordnung eingehender Anfragen zu unterstützen, ohne die fachliche Entscheidung vollständig zu automatisieren.

### Ablauf

1. Eine neue Anfrage geht ein.
2. Der Inhalt wird digital analysiert.
3. Das System empfiehlt **Abteilung A, B oder C**.
4. Ein Mitarbeitender überprüft die Empfehlung.
5. Bei Zustimmung wird die vorgeschlagene Abteilung bestätigt.
6. Bei Ablehnung wählt der Mitarbeitende die richtige Abteilung aus.
7. Die endgültige Zuordnung wird dokumentiert.

### Rollenverteilung

### Testkategorien

Für den Proof of Concept werden drei fiktive Fachabteilungen verwendet:

- **Abteilung A – Abfallservice:** Mülltonnen, Müllabholung und Abfall
- **Abteilung B – Straßen & Beleuchtung:** Straßenschäden und Straßenbeleuchtung
- **Abteilung C – Bürgerservice:** Ausweise und Meldeangelegenheiten

| System | Mitarbeitende |
| --- | --- |
| Anfrage analysieren | Empfehlung überprüfen |
| Abteilung vorschlagen | Vorschlag bestätigen oder korrigieren |
| Ergebnis bereitstellen | Endgültige Zuordnung festlegen |

> **Wichtig:** Das System trifft keine endgültige Entscheidung. Die Verantwortung für die Zuordnung verbleibt beim Mitarbeitenden.
