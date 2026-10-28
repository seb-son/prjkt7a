Projekt 7a – installierbare Web-App (PWA)

Inhalt: index.html, manifest.webmanifest, sw.js, icons/, fonts/ (alles lokal, kein externer Dienst nötig).

Installieren braucht HTTPS-Hosting (Android erlaubt Installation nur dann):

A) GitHub Pages (kostenlos)
 1. Neues Repository anlegen, alle Dateien dieses Ordners hochladen (Ordnerstruktur beibehalten).
 2. Settings > Pages > Branch main, Ordner / (root) > Save.
 3. Nach ca. 1 Minute: https://<name>.github.io/<repo>/ in Chrome öffnen.
 4. Chrome-Menü (⋮) > "App installieren" bzw. "Zum Startbildschirm hinzufügen".

B) Eigener Server mit HTTPS (z. B. nginx): Ordner in ein Web-Verzeichnis legen, unter https://… ausliefern.

Daten übernehmen: In der alten Version Kalender > "Daten kopieren", in der installierten App Kalender > Textfeld einfügen > "Importieren" (zweimal tippen).
Speicher liegt lokal im Browser/der App dieses Geräts. Bei Updates sw.js: CACHE-Namen (projekt-7a-v1) hochzählen.
