# 🏺 Let's Go Archäo

Webbasierte Prototypapp zur archäologischen Funddokumentation – entwickelt vom Team APG Let's Goooooo @MPDV für die FLL.

URL: https://lele-lp.github.io/letsgoarchaeo/

---

## Funktionen

- **Funddokumentation** – Funde mit Material, Fundart, Epoche, GPS-Koordinaten, Fotos und weiteren Details erfassen
- **Interaktive Karte** – alle Fundstellen mit GPS-Daten auf einer Leaflet-Karte visualisieren
- **Nachrichten** – internes Nachrichtensystem zwischen Nutzern
- **Rollen** – Student, Archäologe und Admin mit unterschiedlichen Berechtigungen
- **Dunkelmodus** – umschaltbar über die Einstellungen
- **Globaler Speicher** – alle Daten werden geräteübergreifend gespeichert und bleiben nach dem Neuladen erhalten

---

## Anmeldung

| Rolle | Benutzername | Passwort |
|---|---|---|
| Student | `demo_student` | `demo123` |
| Archäologe | `demo_archaeologist` | `demo123` |
| Admin | `demo_admin` | `admin123` |
| Owner | `lets go` | `go1234` |

Neue Accounts können über die Registrierung mit einem Rollen-Code erstellt werden:

| Code | Rolle |
|---|---|
| `MPDV2025` | Student |
| `ARCHAEO2025` | Archäologe |
| `ADMIN2025` | Admin |

---

## Technologie

- React 18, Tailwind CSS, Leaflet.js
- Läuft vollständig im Browser – keine Installation nötig
- Globaler, persistenter Speicher für geräteübergreifende Synchronisation (Auto-Refresh alle 10 Sekunden)

---

## Kontakt

**APG Let's Goooooo @MPDV**  
Heidelberger Str. 39, 74821 Mosbach  
LegoAg@gmail.com · 06261 97240
