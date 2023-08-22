# Ferienkalender Deutschland

Dieses Projekt enthält alle Ferien in Deutschland ab dem Schuljahr 2021/22 und wird fortlaufend aktualisiert.
https://www.indesign-kalender.de/api/v1/vacation.json

## Parameter

###### base_data

Hier sind alle Stammdaten zu finden, die für die Zuordnung des Einträge benötigt werden.

**base_data.location**<br>
_location.id_: ID des Eintrag <br>
_location.location_name_: Name des Bundesland <br>
_location.location_short_: Kürzel des Bundesland<br>

**base_date.vacation**<br>
_vacation.id_: ID des Eintrag<br>
_vacation.vacation_name_: Bezeichnung der Ferien<br>

**base_date.school_year**<br>
_school_year.id_: ID des Eintrag<br>
_vacation.year_: Schuljahr<br>

###### data

Hier sind alle Ferientermine angelegt.

_data.date_start_: Erster Ferientag, `YYYY-MM-DD`<br>
_data.date_end_: Letzter Ferientag, Format `YYYY-MM-DD` <br>
_data.vacation_id_: Zuordnung zur der Bezeichnung der Ferien `base_date.vacation.id`<br>
_data.location_id_: Zuordnung zum Bundesland `base_date.location.id`<br>
_data.location_id_: Zuordnung zum Schuljahr `base_date.school_year.id`<br>
_data.lastupdate_: Letztes Update Kultusministerkonferenz<br>

`Alle Angaben ohne Gewähr.`
