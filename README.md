# Ferienkalender Deutschland
Dieses Projekt enthält alle Ferien in Deutschland ab dem Schuljahr 2021/22 und wird fortlaufend aktualisiert.
https://www.indesign-kalender.de/v1/vacation.json

## Parameter

###### base_data
Hier sind alle Stammdaten zu finden, die für die Zuordnung des Einträge benötigt werden.

**base_data.location**<br>
*location.id*: ID des Eintrag <br>
*location.location_name*: Name des Bundesland <br>
*location.location_short*: Kürzel des Bundesland<br>

**base_date.vacation**<br>
*vacation.id*: ID des Eintrag<br>
*vacation.vacation_name*: Bezeichnung der Ferien<br>

**base_date.school_year**<br>
*school_year.id*: ID des Eintrag<br>
*vacation.year*: Schuljahr<br>

###### data
Hier sind alle Ferientermine angelegt.

*data.date_start*: Erster Ferientag, `YYYY-MM-DD`<br>
*data.date_end*: Letzter Ferientag, Format `YYYY-MM-DD` <br>
*data.vacation_id*: Zuordnung zur der Bezeichnung der Ferien `base_date.vacation.id`<br>
*data.location_id*: Zuordnung zum Bundesland `base_date.location.id`<br>
*data.location_id*: Zuordnung zum Schuljahr `base_date.school_year.id`<br>
*data.lastupdate*: Letztes Update Kultusministerkonferenz<br>

`Alle Angaben ohne Gewähr.`
