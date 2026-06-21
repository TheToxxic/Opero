# Opero

**KI-gestützter Operations-Workspace** für professionelles Projektmanagement.  
Aufgaben, Entscheidungen, Risiken, Dokumente, KI-Assistent und tägliche Arbeit – alles in einer lokal laufenden Desktop-App.

[**→ Jetzt herunterladen**](https://github.com/TheToxxic/Opero/releases/latest)

---

## Was ist Opero?

Opero richtet sich an Projektverantwortliche, Berater und Teams, die ihre Steuerungsinformationen in einer übersichtlichen, KI-gestützten Umgebung verwalten wollen – ohne Cloud-Zwang und ohne SaaS-Abonnement.

**Kernfunktionen:**

- **Projektbuddy (KI-Assistent)** — Kontextbewusstes Fragen & Antworten auf Basis deiner eigenen Projektdaten, inkl. semantischer Suche
- **Heute-Seite & Briefing** — Tagesüberblick mit Fokusblöcken, Meilensteinen und KI-Narrativ
- **Risikoregister & Scope-Control** — Risiken, Entscheidungen und Scope-Änderungen strukturiert erfassen
- **Aufgaben & Hierarchie** — Aufgabenliste mit Unteraufgaben, Fortschritt, wiederkehrenden Aufgaben und E-Mail-Entwürfen
- **Dokumenten-Workspace** — Import von PDF, DOCX, PPTX, EML u. v. m.; KI-gestützte Vorschläge & Familien
- **Kalenderplanung & Export** — Fokusblöcke vorschlagen und per Fantastical, Calendar.app oder .ics exportieren
- **Reporting & Intelligence** — Trend-Charts, Markdown-Export, Kerndokumente je Teilprojekt
- **Lokale Datenhaltung** — SQLite-Datenbank, kein Server, kein Login, volle Datenkontrolle

---

## Download

Alle Releases → [Releases-Seite](https://github.com/TheToxxic/Opero/releases)

### Windows

| Datei | Beschreibung |
|---|---|
| `Opero-Setup-x.x.x.exe` | Installer (empfohlen) |
| `Opero-x.x.x-win.zip` | Portable – kein Admin nötig |

1. Installer herunterladen und per Doppelklick starten
2. Installationsassistenten folgen
3. Desktop-Shortcut starten – fertig

Alle Daten lokal unter `%APPDATA%\Opero\`.

### macOS (Apple Silicon · arm64)

| Datei | Beschreibung |
|---|---|
| `Opero-x.x.x-mac-arm64.dmg` | Disk Image (empfohlen) |
| `Opero-x.x.x-mac-arm64.zip` | ZIP-Archiv |

1. DMG herunterladen und öffnen
2. Opero in den Programme-Ordner ziehen
3. **Erststart:** Rechtsklick auf die App → „Öffnen" (einmalige Gatekeeper-Bestätigung, da unsigniert)  
   oder im Terminal:
   ```
   xattr -dr com.apple.quarantine "/Applications/Opero.app"
   ```

Alle Daten lokal unter `~/Library/Application Support/Opero/`.

---

## Systemvoraussetzungen

| | Windows | macOS |
|---|---|---|
| Architektur | x64 | Apple Silicon (arm64) |
| Mindestversion | Windows 10 | macOS 13 Ventura |
| Festplatte | ~250 MB | ~250 MB |
| Internetzugang | Optional (KI-Features) | Optional (KI-Features) |

---

## Rechtliches / Legal

© 2025 Chris Riess. Alle Rechte vorbehalten.

Opero ist **proprietäre, urheberrechtlich geschützte Software**. Der Quellcode ist nicht öffentlich.  
Jede nicht genehmigte Vervielfältigung, Weitergabe, Dekompilierung, Modifikation oder Weiterverbreitung – ganz oder in Teilen – ist **untersagt** und wird zivil- und strafrechtlich verfolgt.

Opero is **proprietary software**. All rights reserved.  
Unauthorized copying, redistribution, reverse engineering, modification or resale of this software, in whole or in part, is strictly prohibited and may result in severe civil and criminal penalties under applicable law.

---

*Opero – Clarity before complexity.*