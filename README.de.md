# Pokopla — The Pokopia planning tool

🇩🇪 Deutsch · [🇬🇧 English](./README.en.md)

Ein inoffizielles, browserbasiertes Planungstool für **Pokémon Pokopia**. Damit kannst du deine Pokémon in eigene Gruppen einteilen, Habitate zuweisen und den Überblick über Fähigkeiten und Litter-Items behalten — läuft komplett im Browser, keine Anmeldung, keine Server, deine Daten bleiben auf deinem Gerät.

**[→ Live-Demo](https://bwons.github.io/Pokopla/)**

---

## Features

- Vollständige Pokopia-Pokédex-Datenbank (Hauptspiel, Blubbmeeria-DLC, Event-Pokémon) mit Talenten und Verstreuen-Items
- Eigene Custom-Gruppen mit Farbe, Beschreibung und WIP/DONE-Status
- Habitat-Verwaltung inkl. eigener/umbenannter Gebiete
- Drag & Drop, Mehrfachauswahl, Bearbeiten-Modus mit Verwerfen/Speichern
- Zweisprachig (Deutsch/Englisch), inkl. übersetzter Pokémon-Namen, Fähigkeiten und Gebietsnamen
- Als Progressive Web App (PWA) installierbar — läuft offline, eigenes App-Icon auf iOS und macOS
- JSON-Export/-Import als Backup und zum Übertragen zwischen Geräten

## Nutzung

Einfach `index.html` im Browser öffnen, oder das ganze Repo per GitHub Pages hosten (Settings → Pages → Deploy from branch → `main` / `root`). Alle Pfade sind relativ, funktioniert also sowohl unter `username.github.io` als auch unter `username.github.io/repo-name`.

**Installation als "App":**
- iPhone: Safari → Teilen → "Zum Home-Bildschirm"
- Mac (Sonoma+): Safari → Ablage → "Zum Dock hinzufügen"

## Wie dieses Tool entstanden ist

Dieses Tool wurde größtenteils mit Unterstützung von **Claude (Anthropic)** entwickelt — von der grundlegenden Struktur über einzelne Features bis zur Pokémon-Datenrecherche. Der komplette Code liegt offen in diesem Repository, sodass jede:r nachvollziehen kann, was hier passiert (kein Tracking, keine versteckte Datenübertragung — siehe [Datenschutz](#datenschutz)).

## Datenquellen

Die Pokémon-, Talent- und Habitat-Daten stammen aus öffentlich zugänglichen Community-Wikis, primär:
- [bisafans.de](https://www.bisafans.de/spiele/spin-offs/pokopia/) (deutsche Namen, Talente)
- [Serebii.net](https://www.serebii.net/pokemonpokopia/) (englische Fähigkeiten-Referenz)

Alle Angaben nach bestem Wissen recherchiert, aber ohne Gewähr auf Vollständigkeit oder Korrektheit — Pokopia wird laufend weiterentwickelt und aktualisiert.

## Datenschutz

Dieses Tool erhebt keinerlei Daten, hat kein Tracking und keine Analytics. Alle Eingaben (Gruppen, Zuordnungen, eigene Pokémon) werden ausschließlich lokal im `localStorage` deines Browsers gespeichert und verlassen dein Gerät nie — außer du exportierst sie selbst als JSON-Datei. Es findet keine Kommunikation mit einem Server statt (außer dem einmaligen Laden der App-Dateien selbst).

## Rechtliches / Disclaimer

**Pokémon, Pokopia und alle zugehörigen Namen, Charaktere und Bilder sind Marken- und Urheberrechte von Nintendo, Creatures Inc. und GAME FREAK inc.** Dieses Projekt ist ein inoffizielles Fan-Tool, das in keiner Verbindung zu Nintendo, The Pokémon Company, Creatures Inc. oder GAME FREAK inc. steht und von diesen weder unterstützt noch autorisiert wird. Es dient ausschließlich privaten, nicht-kommerziellen Zwecken.

Für die Pokémon-Namen, Talente und sonstigen Spieldaten wird kein eigenes Urheberrecht beansprucht — diese gehören den jeweiligen Rechteinhabern. Beansprucht wird lediglich Urheberrecht am eigens geschriebenen Code dieses Tools (siehe [LICENSE](./LICENSE)).

Falls du als Rechteinhaber Einwände gegen dieses Projekt hast, öffne bitte ein Issue oder kontaktiere mich direkt — ich nehme das Repo dann umgehend offline.

## Lizenz

Der Quellcode dieses Tools steht unter der [CC BY-NC 4.0](./LICENSE)-Lizenz (Namensnennung, nicht-kommerziell) — du darfst ihn also nutzen, verändern und weiterverbreiten, aber nicht kommerziell. Diese Lizenz gilt **nicht** für Pokémon-bezogene Namen, Daten oder Marken (siehe oben).
