# KI-Werkstatt

Kinder trainieren im Browser eine eigene KI, die Bilder oder Körperhaltungen erkennt. Läuft am iPad (Safari), ohne Anmeldung und ohne Code.
Ein Bildungsprojekt im Design von MINT2Go. Der Aufbau (Klassen, Üben, Ausprobieren) ist dem Werkzeug „Teachable Machine“ nachempfunden. Die KI-Werkstatt ist nicht mit Teachable Machine oder Google verbunden.

**Ausprobieren:** https://makingvs.github.io/ki-werkstatt/

## Was sie kann

- **Bildprojekt** und **Posenprojekt** (Arme, Beine, Kopf), bis zu 6 Klassen.
- Drei Schritte, jeder passt auf einen iPad-Bildschirm: **1 Sammeln**, **2 Üben**, **3 Ausprobieren**.
- Ein Tipp auf den Auslöser macht ein Foto, Halten macht Fotos hintereinander. Dazu Bilder hochladen, Countdown und Serie.
- Drei Arten zu üben: automatisch, Runde für Runde, von Hand.
- **Modell herunterladen und hochladen** (Datei ohne Bilder).
- **Scratch (TurboWarp):** Das Modell lässt sich in Scratch nutzen. Anleitung: https://makingvs.github.io/ki-werkstatt/scratch.html

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Die ganze App in einer Datei (HTML, CSS, JavaScript). Kein Build nötig. |
| `scratch.html` | Anleitung für Scratch (TurboWarp). |
| `scratch/ki-werkstatt-erweiterung.js` | Die Erweiterung für TurboWarp (läuft ohne Sandbox). |
| `assets/` | Logos von MINT2Go. |

Lokal ausprobieren (die Kamera braucht `localhost` oder https): `python -m http.server 8000` und dann http://localhost:8000/ öffnen.

## Datenschutz

Kamerabilder, Beispiele und trainierte KIs bleiben auf dem Gerät. Die Seite verschickt nichts, speichert nichts im Browser und setzt keine Cookies.
Beim Start eines Projekts lädt sie Programme (jsDelivr) und ein fertiges Erkennungsmodell (Google, Kaggle) aus dem Internet. Diese Anbieter sehen dabei technische Daten wie die IP-Adresse.

## Lizenzen und Rechte

- Der selbst geschriebene Quelltext ist noch nicht unter einer Open-Source-Lizenz freigegeben. Alle Rechte vorbehalten.
- Geladene Bausteine: TensorFlow.js, MobileNet und PoseNet (Apache-2.0, © Google LLC). Das MobileNet-Modell wurde mit ImageNet trainiert, dessen Bedingungen nur nicht-kommerzielle Forschung und Bildung erlauben.
- Die kleinen Symbole in der App sind Material Icons von Google (Apache-2.0, © Google LLC).
- Die KI-Werkstatt ist nicht mit der Scratch Foundation, TurboWarp, Teachable Machine oder Google verbunden und wird von ihnen nicht unterstützt.
- Logo und Erscheinungsbild gehören MINT2Go.
- Alle Angaben mit Quellen stehen in der App unter Menü → „Info, Lizenzen und Datenschutz“.
