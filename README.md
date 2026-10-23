# plainlift-oauth

Statische Rücksprungseiten für die OAuth-Anmeldung in der iOS-App Plainlift.

Gerätedienste wie Withings verlangen eine erreichbare HTTPS-Adresse als
Callback. Die Seite unter `withings/` reicht Code und Status unverändert an
`plainlift://oauth/withings` weiter. Sie speichert nichts, lädt nichts nach
und sendet nichts an Dritte. Den Code tauscht die App selbst gegen ein Token.
