# Konstantin Konradi

Ich baue Software für Betriebe. Seit Mai 2026 mit einem eigenen Unternehmen,
Fynaxa, über das ich Kunden betreue — von der Aufnahme des Ablaufs im Betrieb bis
zum laufenden Dienst.

Was ich für zeigbar halte, liegt hier. Der rote Faden ist nicht eine Sprache oder
ein Framework, sondern die langweiligen Teile: Idempotenz, Protokolle, ein Weg
zurück nach einem Absturz, und rechtliche Randbedingungen als ausführbare Tests
statt als Absatz in einer Richtlinie.

### Was hier liegt

| | |
|---|---|
| **[hallenbuch](https://github.com/Fynaxa/hallenbuch)** | Fahrzeugerfassung und Sammelabrechnung, im Kundenauftrag gebaut. E-Rechnung nach EN 16931, systemd, 329 Tests. Reine Standardbibliothek. |
| **[lead-response-case](https://github.com/Fynaxa/lead-response-case)** | Fallstudie zu einem System mit rund 35.000 Zeilen, das Anfragen über WhatsApp, Mail und Formular beantwortet und Termine bucht. Kein Quelltext, keine Kundendaten — nur die Entscheidungen. |
| **[whatsapp-starter](https://github.com/Fynaxa/whatsapp-starter)** | Die Schicht unter einem WhatsApp-Bot: Signaturprüfung, doppelte Zustellungen, das 24-Stunden-Fenster. Das, was langweilig zu schreiben und teuer zu debuggen ist. |
| **[inbox-automation](https://github.com/Fynaxa/inbox-automation)** | Postfach überwachen, Mail nach Regeln einordnen, Felder herausziehen, Aktionen auslösen. Keine Mail wird zweimal verarbeitet, auch nach einem Absturz nicht. |
| **[table-pipeline](https://github.com/Fynaxa/table-pipeline)** | Die CSV- und Excel-Dateien, die Kunden tatsächlich schicken: falsch deklarierte Kodierung, deutsche Dezimaltrennzeichen, verschobene Kopfzeilen. Stimmen die Zeilenzahlen am Ende nicht, bricht der Lauf ab. |

**545 automatische Tests** über alle Projekte, dazu 58 Prüfungen in Node, überwiegend gegen Fehlerfälle: API-Ausfälle,
halbe Schreibvorgänge, doppelte Webhooks, abgelaufene Zugänge.

### Wie ich arbeite

Ich arbeite mit KI-Werkzeugen, hauptsächlich Claude Code — das steht so in der
Commit-Historie, weil es stimmt. Was das nicht ersetzt, ist die Entscheidung,
**was nicht gebaut wird**: kein eigenes Rechnungsprogramm neben einem
GoBD-pflichtigen System, kein automatischer Versand ohne menschliche Freigabe,
keine zugesagte Trefferquote, die nicht gemessen wurde. Diese Begründungen stehen
in den READMEs, und sie sind der Teil, den ich zur Beurteilung anbiete.

### Womit

Python (am liebsten ohne Abhängigkeiten), SQLite, HTTP, JavaScript. WhatsApp
Business API, IMAP/SMTP, Google Calendar, Lexware Office. DSGVO Art. 28,
§ 7 UWG, AI Act Art. 50, GoBD, EN 16931 — nicht als Schlagworte, sondern weil sie
bestimmen, was das System darf.

### Erreichbarkeit

info@fynaxa.de
