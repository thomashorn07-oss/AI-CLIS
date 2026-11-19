# AGENTS.md

## Repo (verifiziert)

- Workspace: `C:\Users\T_hor\OneDrive\CLOUD_PROJEKTE\CLOUD_WORKSPACE\OpenCode` (Windows, PowerShell).
- Inhalt aktuell: nur `tetris.html` (statisches Tetris-Spiel in HTML/CSS/JS, kein Build-System, keine Pakete, keine Tests, kein Lint/Typecheck konfiguriert).

## Wichtige Kommandos (genau)

- Spiel öffnen (aus Repo-Root, PowerShell):
  - `start tetris.html`
- Optional: direkt im Browser per Dateipfad öffnen: `tetris.html` doppelklicken.

## Arbeitsweise in diesem Repo

- Änderungen bevorzugt direkt in `tetris.html` (einzige Quelldatei). Keine Annahmen über Frameworks/Tools treffen (nicht vorhanden).
- Keine generischen Boilerplate-Dateien anlegen, außer explizit gewünscht.
- Wenn später `package.json`/Build/Test/Lint dazukommt: dieses `AGENTS.md` aktualisieren (exakte Befehle + Reihenfolge hier eintragen).

## Nicht vorhanden (nicht erfinden)

- Kein `npm`/`node`-Scripts, kein CI, keine Formatter/Typechecker-Konfigs, keine Tests – also keine `lint/typecheck/test`-Kommandos ausführen, die nicht existieren.
