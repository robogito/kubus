## Epic: Als Manager möchte ich eine Einrichtung erstellen, damit ich mein Sportangebot planen und verkaufen kann
- Als Manager möchte ich einen Standort erstellen
- Als Manager möchte ich ein Gebäude (Objekt, Feld, Tennisplatz) erstellen und einem Standort zuordnen
- Als Manager möchte ich einen Raum (Halle, Saal) erstellen und einem Gebäude zuordnen
- Als Manager möchte ich eine Liste der Standorte, Gebäude und Räume anzeigen
- Als Manager möchte ich einem Standort, Gebäude oder Raum eine Zugangskontrolle zuordnen
- Als Manager möchte ich den Belegungsplan eines Standorts, Gebäude oder Raums anzeigen und ausdrucken
- Als Manager möchte ich den Terminstandort allen Interessenten so anzeigen, dass er schnell gefunden wird

### Standort
Ein Standort ist eine Location mit Adresse. 

**Pflicht**
- Straße
- Nr.
- Stadt
- PLZ
- Koordinaten

**Option**
- Bezeichnung
- Kürzel
- Kurzbeschreibung
- Telefon
- Zugangskontrolle
- Öffnungszeiten

### Gebäude, Sportplatz
Ein Gebäude (Objekt, Platz) gehört immer zu einem Standort. 

**Pflicht**
- Bezeichnung

**Option**
- Kapazität
- Kurzbeschreibung
- Kürzel
- Etagen
- Zugangskontrolle

### Raum
Ein Raum (Halle) kann nur einem Gebäude zugeordnet werden. 

**Pflicht**
- Bezeichnung

**Option**
- Raumnummer
- Kapazität
- Kurzbeschreibung
- Kürzel
- Etage
- Zugangskontrolle
