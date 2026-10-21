# Ben & Mia – Das Puppenhaus

Android-Puppenhaus-App für Kinder ab 4–5 Jahren mit Ben, Mia, Hund Bello und Kaninchen Flocke.

## Spielen

- **4 Zimmer:** Wohnzimmer, Kinderzimmer, Küche, Badezimmer – unten antippen zum Wechseln.
- **Figuren ziehen:** Ben, Mia, Bello und Flocke mit dem Finger verschieben.
  - aufs Sofa oder auf einen Hocker → sitzen
  - ins Hochbett (oben oder unten) → schlafen
  - in die Badewanne → baden
  - Bello ins Körbchen, Flocke aufs Kissen → schlafen
- **Umziehen in ein anderes Zimmer:** Figur oder Spielzeug auf einen Zimmer-Knopf unten ziehen.
- **Füttern:** Kühlschrank öffnen, Essen antippen, dann Apfel, Möhre, Keks oder Banane auf eine Figur ziehen.
- **Zum Antippen:** Lampen, Fenster (Tag/Nacht), Fernseher, Blume, Spielkiste, Herd, Waschbecken, Badewanne, Toilette, Ball, Teddy, Ente und alle Figuren.
- Alle paar Sekunden wackelt ein Gegenstand, damit Kinder neue Sachen entdecken.
- Der Spielstand wird automatisch gespeichert. „Neu anfangen“ auf dem Startbildschirm (zweimal tippen) setzt alles zurück.

## APK bauen (ohne Android Studio)

1. Dieses Projekt in ein GitHub-Repository hochladen.
2. Unter **Actions → APK bauen** läuft der Build automatisch (oder per „Run workflow“).
3. Nach ca. 3–5 Minuten unter dem Lauf das Artefakt **puppenhaus-apk** herunterladen, entpacken und `app-debug.apk` aufs Handy kopieren und installieren.

## Aufbau

- `app/src/main/assets/index.html` – das komplette Spiel (Grafik, Töne, Logik), funktioniert auch im Browser
- `app/src/main/java/.../MainActivity.java` – Vollbild-WebView, Querformat, keine Internetverbindung nötig
