# tv-remote Releases

Veröffentlichte Versionen der Android-App **tv-remote** (Fernbedienung für einen Philips-Android-TV).

Dieses Repo enthält nur die fertigen Dateien einer Version, keinen Quellcode:

- `tv-remote-<Version>.apk`: die App
- `tv-remote-<Version>.apk.sha256`: Prüfsumme der APK
- Release Notes: die Änderungen der Version (eine Zeile pro Änderung) und die Zeile `SHA-256: …`

Die App holt sich neue Versionen selbst aus der neuesten Veröffentlichung (Einstellungen → Updates), prüft die
Prüfsumme und übergibt die Datei dem Android-Installer. Die erste Version mit dieser Funktion (0.2.0) muss einmal von
Hand installiert werden. Der Quellcode bleibt privat auf dem Rechner des Entwicklers.
