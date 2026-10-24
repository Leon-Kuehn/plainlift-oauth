# plainlift-oauth

Statische Rücksprungseiten für die OAuth-Anmeldung in der iOS-App Plainlift.

Gerätedienste wie Withings und Polar verlangen eine erreichbare HTTPS-Adresse als
Callback. Die Seiten unter `withings/` und `polar/` reichen Code und Status unverändert an
`plainlift://oauth/withings` bzw. `plainlift://oauth/polar` weiter. Sie speichern nichts, laden nichts nach
und sendet nichts an Dritte. Den Code tauscht die App selbst gegen ein Token.
