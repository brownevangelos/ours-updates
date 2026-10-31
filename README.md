# ours. – öffentliche Updates

Dieses Repository enthält öffentliche Versionsinformationen und künftig signierte APK-Dateien. Der Quellcode der Android-App bleibt privat.

## Aktueller Status
Noch keine neue APK hier veröffentlicht. `latest.json` nennt Version 3, sodass die bereits installierte v3 **kein** Update angeboten bekommt.

## Neue Version veröffentlichen
1. `versionCode` in der privaten Android-App erhöhen.
2. Release-APK **mit demselben Signierschlüssel** wie v3 erstellen und testen.
3. In diesem öffentlichen Repository ein GitHub Release mit der signierten APK als Asset erstellen.
4. Erst danach `latest.json` auf den neuen `versionCode`, `versionName` und die direkte HTTPS-Downloadadresse des APK-Assets setzen.
5. Aktualisierung auf einem Gerät mit installierter Vorgängerversion testen.

**Keine Zugangsdaten, Signierschlüssel, Firebase-Konfigurationsdateien oder persönlichen Daten veröffentlichen.**

Die App prüft derzeit beim Start auf neue Versionen. Sie öffnet bei Zustimmung den APK-Download im Browser; Android kann weitere Download- und Installationsbestätigungen verlangen.
