# Automation Portfolio – Nazarii Zhurov

Selbstständiges Erlernen von KI-Automatisierung und Datenanalyse.
Ziel: Ausbildung zum Fachinformatiker.

> Lernbeginn: 26 März 2026 | Täglicher Lernaufwand: 2–3 Stunden

---

## Projekte

### Projekt 1 – Automatische Formularverarbeitung mit KI - 28.03.2026

**Tools:** Make.com · Google Forms · OpenAI (ChatGPT) · Gmail · Google Sheets

**Problem:**
Kundenanfragen über ein Kontaktformular mussten manuell gelesen
und beantwortet werden – das kostet Zeit und ist fehleranfällig.

**Lösung:**
Make.com-Szenario das automatisch ausgeführt wird sobald 
ein Kunde das Google-Formular ausfüllt:
1. Make liest die Formularantwort
2. OpenAI analysiert den Inhalt und erstellt eine passende Antwort
3. Gmail versendet die Antwort automatisch an den Kunden
4. Alle Daten werden in Google Sheets gespeichert

**Ergebnis:**
![Projekt 1 Screenshot](Projekt%201%20Screenshot.png)
Antwortzeit von mehreren Stunden auf 0 Sekunden reduziert.
Vollständig automatisiert – kein manueller Aufwand nötig.

---

### Projekt 2 – Automatische E-Mail-Bearbeitung mit KI - 29.03.2026

**Tools:** Make.com · Gmail · OpenAI (ChatGPT) · Google Sheets

**Problem:**
Eingehende E-Mails mussten manuell gelesen, bewertet
und beantwortet werden.

**Lösung:**
Make.com-Szenario das bei jedem eingehenden E-Mail startet:
1. Make erkennt die neue E-Mail in Gmail
2. OpenAI liest den Inhalt und generiert eine sinnvolle Antwort
3. Gmail sendet die Antwort automatisch zurück
4. Betreff, Inhalt und KI-Antwort werden in Google Sheets protokolliert

**Ergebnis:**
![Projekt 2 Screenshot](Projekt%202%20Screenshot.png)
E-Mails werden in Echtzeit verarbeitet und beantwortet.
Komplette Dokumentation aller Vorgänge in der Tabelle.

---

### Projekt 3 – RSS-News & Wetter-Assistent via Telegram - 31.03.2026

**Tools:** Make.com · RSS · OpenWeatherMap · OpenAI (ChatGPT) · Telegram Bot

**Problem:**
Jeden Morgen manuell Nachrichten und Wetter prüfen kostet Zeit.

**Lösung:**
Make.com-Szenario das automatisch alle 15 Minuten läuft:
1. RSS liest aktuelle Nachrichten (z.B. Tagesschau)
2. OpenWeatherMap liefert aktuelle Wetterdaten
3. OpenAI analysiert beide Quellen und erstellt eine 
   persönliche Zusammenfassung
4. Telegram Bot sendet die Nachricht auf Ukrainisch und Deutsch

**Ergebnis:**
![Projekt 3 Screenshot](Projekt%203%20Screenshot.png)
Automatischer persönlicher Assistent – läuft alle 15 Minuten,
kein manueller Aufwand. 4 Dienste in einem Szenario integriert.
## Technische Fähigkeiten

---

### Projekt 4 – KI-Agent: Automatischer Wochenbericht

**Tools:** Make.com · Make AI Agent · Google Sheets · Telegram Bot

**Geschäftsszenario:**
Ein Verkäufer pflegt seine Verkaufsdaten in Google Sheets.
Jeden Montag analysiert ein KI-Agent automatisch alle Daten
und liefert einen vollständigen Wochenbericht.

**Automatisierungsablauf:**
1. Google Sheets liefert alle Verkaufsdaten
   (Datum, Produkt, Menge, Umsatz)
2. Text Aggregator fasst alle Zeilen zusammen
3. Make AI Agent analysiert die Daten und führt 3 Aufgaben aus:
   - Erstellt personalisierte Telegram-Nachricht mit Rankings
   - Berechnet Gesamtumsatz und Einzelumsätze
   - Gibt Verbesserungsvorschläge als Business Analyst
4. Telegram Bot sendet den fertigen Wochenbericht
5. Google Sheets speichert die analysierten Daten

**Besonderheit:**
Erster Einsatz von Make AI Agents – fortgeschrittene Technik
die eigenständige Entscheidungen und mehrere parallele
Aufgaben ermöglicht.

**Ergebnis:**
![Projekt 4 Screenshot](Projekt%204%20Screenshot.png)
Vollautomatischer Business-Intelligence-Report. Spart dem
Verkäufer 30–60 Minuten manuelle Auswertung pro Woche.
Einsetzbar für jeden kleinen Betrieb mit Verkaufsdaten.

---

### Projekt 5 – Automatisches Bestellsystem mit Webhook

**Tools:** Make.com · Tally · Webhook · OpenAI · 
Router · Telegram · Gmail · Google Sheets

**Geschäftsszenario:**
Ein Online-Shop erhält Bestellungen über ein 
Tally-Formular. Das System verarbeitet jede 
Bestellung vollautomatisch in Echtzeit.

**Automatisierungsablauf:**
1. Kunde füllt Tally-Bestellformular aus
2. Webhook löst Make-Szenario sofort aus
3. OpenAI erstellt personalisierte HTML-Bestätigungs-E-Mail
4. Router verteilt parallel auf 3 Kanäle:
   → Gmail sendet Bestätigung an Kunden
   → Telegram benachrichtigt das Team sofort
   → Google Sheets speichert alle Bestelldaten

**Technische Highlights:**
- Echtzeit-Verarbeitung via Webhook
- Tally fields[] Array korrekt gemappt
- HTML-formatierte E-Mails
- 3 parallele Router-Pfade gleichzeitig

**Ergebnis:**
![Projekt 5 Screenshot](Projekt%205%20Screenshot.png)
Vollautomatische Bestellverarbeitung in unter 
20 Sekunden. Kein manueller Aufwand nötig.
Einsetzbar für jeden Online-Shop oder 
Dienstleister.

**Status:** 5x erfolgreich getestet ✓

---

### Projekt 6 – KI-Website-Consultant "Joe"

**Tools:** Make.com · Tally · Browse AI · Make AI Agent · 
Gmail · Google Calendar · Google Sheets

**Geschäftsszenario:**
Eine Webdesign-Agentur erhält täglich Anfragen von 
Unternehmen die ihren Webauftritt verbessern möchten.
"Joe" übernimmt die komplette Erstbearbeitung automatisch.

**Automatisierungsablauf:**
1. Kunde füllt Tally-Formular aus
   (Name, Email, Website, Wunschtermin, Nachricht)
2. Browse AI analysiert die angegebene Website
3. Make AI Agent "Joe" führt 6 Tasks aus:
   → Spam & Relevanzprüfung
   → Website-Analyse (Design, UX, Klarheit)
   → Kalender-Check (Mo–Fr 09–16 Uhr CET)
   → Termin erstellen oder Alternativen vorschlagen
   → Personalisierte E-Mail mit konkreter Beobachtung
   → Google Sheets Logging
4. Gmail sendet E-Mail direkt an den Kunden
5. Google Calendar erstellt Meeting mit Google Meet
6. Google Sheets protokolliert alle Daten

**Technische Highlights:**
- Browse AI für Echtzeit Website-Analyse
- Make AI Agent mit 6 strukturierten Tasks
- Kalender-Logik mit Zeitfenster-Prüfung
- Strikte Prompt-Regeln für natürliche Kommunikation
- Vollständiges CRM-Logging

**Ergebnis:**
![Projekt 6 Screenshot](Projekt%206%20Screenshot.png)
![Projekt 6 Screenshot](Projekt%206.1%20Screenshot.png)
Ersetzt 30–60 Minuten manuelle Erstbearbeitung 
pro Anfrage. Reif für den Einsatz in echten 
Webdesign-Agenturen.

*Erstellt: 19. April 2026*

---

| Tool | Level |
|------|-------|
| Make.com | Fortgeschritten |
| Make AI Agents | Fortgeschritten |
| Browse AI | Grundlagen |
| Google Calendar API | Grundlagen |
| Webhooks | Grundlagen – Fortgeschritten |
| Router & parallele Pfade | Fortgeschritten |
| OpenAI API (via Make) | Fortgeschritten |
| Google Sheets | Fortgeschritten |
| Gmail Automation | Fortgeschritten |
| Tally Forms | Grundlagen – Fortgeschritten |
| Python | Grundlagen (Start) |
| GitHub | Grundlagen |

---

## Nächste Schritte
- [ ] Python Grundlagen (Kaggle)
- [ ] SQL Grundlagen
- [ ] Power BI Dashboard
- [ ] Kombiniertes Datenanalyse-Projekt

---
*Lernbeginn: 26 März 2026*
