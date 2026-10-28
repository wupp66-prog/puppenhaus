# Ben & Mia – Das Puppenhaus

Android-Puppenhaus-App für Kinder ab 4–5 Jahren mit Ben, Mia, Hund Bello und Kaninchen Flocke.

## Spielen

- **6 Zimmer:** Wohnzimmer, Kinderzimmer, Küche, Badezimmer, Spielzimmer und Garten – unten antippen zum Wechseln.
- **Figuren ziehen:** Ben, Mia, Bello und Flocke mit dem Finger verschieben.
  - aufs Sofa, auf einen Hocker oder den Sitzsack → sitzen
  - ins Hochbett → schlafen, in die Badewanne → baden
  - aufs Schaukelpferd → wippen, auf die Schaukel → schaukeln
  - oben auf die Rutsche → rutscht von allein runter
  - in den Sandkasten → spielen
  - Bello ins Körbchen oder in die Hundehütte, Flocke aufs Kissen → schlafen
- **Zimmer wechseln:** Figur oder Spielzeug auf einen Zimmer-Knopf unten ziehen.
- **Kleiderschrank (Kinderzimmer):** Schrank antippen oder Ben/Mia auf den Schrank ziehen – je 5 Outfits.
  - Ben: Alltag, Fußball, Pirat, Feuerwehr, Schlafanzug
  - Mia: Alltag, Prinzessin, Sommer, Regen, Schlafanzug
- **Füttern:** Kühlschrank öffnen oder Toaster antippen, dann Essen auf eine Figur ziehen.
- **Spielzeug geben:** Spielzeug auf eine Figur ziehen – sie reagiert (z. B. Knochen zu Bello, Seifenblasen zu Mia).
- **Spielzeug:** Ball, Teddy, Ente, Auto (fährt), Bauklötze A/B/C (zum Turm stapeln), Kreisel, Luftballon (platzt), Knochen (Bello holt ihn), Gießkanne (Blumen wachsen), Seifenblasen.
- **Zum Antippen:** Lampen, Fenster und Sonne (Tag/Nacht), Fernseher, Kuckucksuhr, Blume, Mobile, Spielkiste, Herd, Toaster, Waschbecken, Badewanne, Toilette, Xylophon, Trommel, Staffelei, Radio (alle tanzen!), Sandkasten.
- Alle paar Sekunden wackelt ein Gegenstand, damit Kinder neue Sachen entdecken.
- Der Spielstand wird automatisch gespeichert (alte Spielstände bleiben erhalten). „Neu anfangen“ auf dem Startbildschirm (zweimal tippen) setzt alles zurück.

## APK bauen (ohne Android Studio)

1. Dieses Projekt in ein GitHub-Repository hochladen.
2. Unter **Actions → APK bauen** läuft der Build automatisch (oder per „Run workflow“).
3. Nach ca. 3–5 Minuten unter dem Lauf das Artefakt **puppenhaus-apk** herunterladen, entpacken und `app-debug.apk` aufs Handy kopieren und installieren.

## Aufbau

- `app/src/main/assets/index.html` – das komplette Spiel (Grafik, Töne, Logik), funktioniert auch im Browser
- `app/src/main/java/.../MainActivity.java` – Vollbild-WebView, Querformat, keine Internetverbindung nötig
