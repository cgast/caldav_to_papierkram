# caldav_to_papierkram
 
**Auslesen eines CalDav Kalenders und Buchung der Termine in Papierkram als Time Entries**

Ich hasse Zeiterfassung. Ich habe nie verstanden, warum man in einem eigenen Tool Kunden, Jobnummern, Stunden und Beschreibungen erfassen muss, wenn man das alles doch schon zumindest grob in seinem Kalender pflegt. caldav_to_papierkram sucht in einem Kalender alle Termine eines Monats und versucht in Papierkram die entsprechenden Kunden und Jobs zu finden um dann Time Entries für Papierkram zu erzeugen und diese per API hochzuladen.

Im Kalender werden die Zeiten erfasst und nach dem Format "Firma - Projekt - Tätigkeit - Beschreibung" beschriftet. Also sowas wie: "Meier GmbH - Website - Programmierung - Layout überarbeitet und Templates produktiv gestellt"

**Nie mehr "Stunden buchen", nur noch "Kalender pflegen".**
