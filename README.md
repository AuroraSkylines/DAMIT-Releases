# DAMN IT! – The Dam Crew

> Four idiots. One dam. Zero qualifications.

Chaotisches 3D-Koop-Spiel für 1–4 Spieler (Windows, Steam-Online-Koop). Dieses Repository enthält nur die
Spieldateien für den **DAMN IT! Launcher**.

## Installieren

1. **[DAMIT-Setup.exe herunterladen](https://github.com/AuroraSkylines/DAMIT-Releases/raw/main/DAMIT-Setup.exe)** und starten.
   Windows fragt eventuell nach („Der Computer wurde durch Windows geschützt“): **Weitere Informationen → Trotzdem ausführen**
   – die Dateien sind (noch) nicht signiert.
2. Installiert wird ohne Admin-Rechte nach `%LOCALAPPDATA%\Programs\DAMIT`.
3. Danach immer über **DAMN IT!** im Startmenü (bzw. Desktop) starten – das öffnet den Launcher.
   Er zeigt die Patch Notes, lädt Updates (**UPDATE**) und startet das Spiel (**PLAY**).

Für Online-Koop muss **Steam laufen**. Einladen: im Spiel `Esc` bzw. Controller `Start` → „Freund einladen“.
Beide Spieler brauchen dieselbe Version – der Launcher sorgt dafür.

## Inhalt dieses Repositorys

| Datei | Zweck |
|---|---|
| `DAMIT-Setup.exe` | Erstinstallation (Launcher + Spiel) |
| `launcher.json` | was der Launcher liest (Version, Dateien, Prüfsummen) |
| `patch_notes.json` | Patch Notes (Deutsch/Englisch) |
| `game/<version>/…` | Spieldateien, gzip-gepackt |
| `launcher/<version>/…` | Launcher-Updates |

Spielstände liegen nie im Installationsordner und werden von Updates nicht angefasst.
