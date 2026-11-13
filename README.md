# Simple Beamer-Steuerung

Steuert die Beamer-Ebene über der Posterwand im Simple Weidenallee.

- `/` Bedienfeld fürs Team (Änderungen nur mit PIN)
- `/#beamer` Beamer-Ansicht für den Laptop am Projektor

Kasse: Im Bedienfeld unter „Kasse & Budget“ Artikel antippen, der Preis geht vom Budget (Standard 500 €) ab. Der Restbetrag läuft mit Fortschrittsbalken unten rechts auf der Wand runter, bei 0 gibt es ein Feuerwerk.

Daten und Live-Sync laufen über Supabase (Projekt Simple-Clockin, Tabellen `beamer_docs` und `beamer_secret`).
Statische Seite ohne Build-Schritt: Vercel liefert `index.html` direkt aus.
