# Gaetano Reale Immobilien

> Professionelle Immobilien-Website für Tübingen — Kaufen & Mieten.  
> Gebaut mit reinem HTML, CSS und JavaScript. Keine Frameworks, keine Build-Tools.

---

## 🚀 Live starten

Einfach `index.html` im Browser öffnen — fertig.  
Oder auf einen beliebigen Webserver / GitHub Pages hochladen.

### GitHub Pages aktivieren
1. Repository auf GitHub hochladen
2. **Settings → Pages → Branch: `main` → Folder: `/ (root)`**
3. Speichern → Die Seite ist live unter `https://[username].github.io/[repo-name]`

---

## 📁 Projektstruktur

```
gaetano-reale/
├── index.html          ← Komplette Website (HTML + CSS + JS in einer Datei)
├── assets/
│   └── images/         ← Eigene Bilder hier ablegen
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🔐 Admin-Zugang

Das kleine Personen-Icon oben rechts in der Navigation öffnet den Login.

| Feld         | Wert            |
|--------------|-----------------|
| Benutzername | `Gaetano Reale` |
| Passwort     | `170709`        |

> ⚠️ **Wichtig:** Das Passwort vor dem Live-Gang im Code ändern!  
> Suche in `index.html` nach `'170709'` und ersetze es.

---

## ✨ Features

- **Intro-Animation** — Splash Screen mit Slide-in beim ersten Laden
- **Apple-Style Design** — Reines Schwarz/Weiß, Playfair Display Serif
- **GSAP Animationen** — Hero-Reveal, Parallax, Scroll-Trigger
- **Objekte** — Kaufen & Mieten mit Filter-Tabs und Detail-Modal
- **Admin-Dashboard** mit:
  - Website-Bearbeitungsmodus (alle Texte direkt bearbeiten)
  - Objekte erstellen / bearbeiten / löschen
  - Bild-Upload (Drag & Drop)
  - Kontaktdaten & Öffnungszeiten bearbeiten
  - E-Mail-Weiterleitung einstellen
- **Datenpersistenz** via `localStorage` (kein Server nötig)
- **Vollständig responsiv** — Mobile, Tablet, Desktop

---

## 🛠 Anpassen

### Kontaktdaten ändern (ohne Admin)
In `index.html` folgende Stellen suchen und ersetzen:

```
Otto-Erbe-Weg 38        → Ihre Adresse
72072 Tübingen          → Ihre PLZ + Stadt
+49 7071 00 00 00       → Ihre Telefonnummer
info@reale-immobilien.de → Ihre E-Mail
```

### Eigene Bilder
1. Bilder in `assets/images/` ablegen
2. Im Admin-Dashboard unter „Objekt erstellen" den Pfad `assets/images/dateiname.jpg` eingeben

---

## 📦 Abhängigkeiten (CDN)

Keine lokale Installation nötig. Folgende Bibliotheken werden über CDN geladen:

| Bibliothek | Version | Verwendung |
|------------|---------|------------|
| GSAP | 3.12.5 | Animationen |
| GSAP ScrollTrigger | 3.12.5 | Scroll-Animationen |
| Google Fonts | — | Playfair Display, DM Sans |

> Für Offline-Betrieb: CDN-Links in `index.html` durch lokale Dateien ersetzen.

---

## 📄 Lizenz

MIT — frei verwendbar und anpassbar.

---

*Gaetano Reale Immobilien · Otto-Erbe-Weg 38 · 72072 Tübingen*
