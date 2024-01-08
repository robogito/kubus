> **Digitalisierung der Vertragsverwaltung** 🚀  
> Im System soll die Vertragsverwaltung wie folgt ablaufen:
>
>1. Der Kursleiter-Vertragstext wird auf der Webseite veröffentlicht und im Formular bei der Registrierung als Kursleiter akzeptiert
>2. Vertrag erstellen: Kursleiter bekommt Sportart und Honorar zugewiesen (Akrobatik, 15 €/Stunde)
>3. Vertrag wird vom Hochschulsport "unterschreiben": Kursleiter wird einem Kurs zugeordnet und bekommt einen Auftrag
>4. Vertrag wird vom Kursleiter "unterschreiben" (Datum des Vertragsbeginns): Kursleiter nimmt den Auftrag an
>5. Vertrag ändern: möglich nur, wenn keine Aufträge laufen - zugewiesene Sportart und Honorar werden "gekündigt" (Datum des Vertragsende) und archiviert, neue werden zugewiesen (Akrobatik, 23 €/Stunde) - gültig nur für neue Aufträge
>
> Behandlung der Papier-Dokumente soll im System zunächst nicht implementiert werden.

**Kursleiter-Verträge**  
Unsere Verträge sind weder semester- noch kursgebunden, sie sind aber Sportartgebunden. Folgende Daten werden eingegeben:
-	Sportart (Auswahlmenü)
-	Datum Beginn (heute)
-	Datum Ende (heute+20 Jahre)
-	Honorar pro Stunde

**Kursleiter-Aufträge**  
Verträge sind Grundlage für Aufträge. Aufträge sind immer zeitraumgebunden (Semester) und nicht immer kursgebunden. Aufträge sind Grundlage für Rückmeldung (Auftragsannahme) und Abrechnung der Kursleiter.

**Zusätzliche Nutzerprofil-Felder**  
Nutzerprofil soll folgende Felder haben:
-	Telefon
-	Bankverbindung für Ausgaben (Kursbuchung)
-	Mitarbeiter-Nummer (wird automatisch vom System vergeben)
-	Bankverbindung für Einnahmen (Kursleiter-Honorar)
-	Steuernummer/ID
-	Finanzamt
-	Qualifikationsnachweise
-	Erste Hilfe-Nachweis

**Unterschriftsverwaltung**  
Wir setzen keine Unterschrift im System ein. Fragen, ob es gewünscht wird.

**Vertragsvorlagen**  
Wir haben folgende Vorlagen:
- Vertrag
- Änderungsvertrag (Honoraränderung)
- Kündigung

**Vertragsbindung bei Kurszuweisung**  
Aufträge dürfen nur an Kursleiter mit Verträgen vergeben werden. Sonst keine Grundlage für Stundenabrechnung.

**Vertragsaufhebungen**  
Verträge werden momentan manuell von beiden Seiten gekündigt. Automatisierung (wenn gewünscht) ist denkbar - wir haben keine unbefristeten Verträge, soll aber frühzeitig sichtbar (Email, Dashboard, Vertragsübersicht) angekündigt werden. Der Kursleiter soll in seinem Profil den Vertrag kündigen können.
