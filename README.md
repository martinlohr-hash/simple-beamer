# Simple Beamer-Steuerung

Steuert die Beamer-Ebene über der Posterwand im Simple Weidenallee.

- `/` Bedienfeld fürs Team (Änderungen nur mit PIN)
- `/#beamer` Beamer-Ansicht für den Laptop am Projektor

Daten und Live-Sync laufen über Supabase (Projekt Simple-Clockin, Tabellen `beamer_docs` und `beamer_secret`).
Statische Seite ohne Build-Schritt: Vercel liefert `index.html` direkt aus.
