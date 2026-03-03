# RoutePilotX – Professionelle Multi‑Profil‑Routenplanung

![Enterprise Ready](https://img.shields.io/badge/Enterprise-Ready-0f4c81?style=for-the-badge)
![Made in Germany](https://img.shields.io/badge/Made%20in-Germany-000000?style=for-the-badge)
![Routing OSRM](https://img.shields.io/badge/Routing-OSRM-brightgreen?style=for-the-badge)
![OpenLayers](https://img.shields.io/badge/OpenLayers-v10.8-87ceeb?style=for-the-badge)
![Plotly Charts](https://img.shields.io/badge/Charts-Plotly-critical?style=for-the-badge)
![Docker Ready](https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge)
![Multi-Profile](https://img.shields.io/badge/Profiles-Car%20%7C%20Bicycle%20%7C%20Foot-ff69b4?style=for-the-badge)
![Abo Modell](https://img.shields.io/badge/Modell-Subscription-6a0dad?style=for-the-badge)

---

## Professionelle Routenplanung. Multi‑Profil. Sofort einsatzbereit.

**RoutePilotX** ist eine hochperformante, containerisierte Webanwendung für Routenberechnung und Visualisierung für Auto, Fahrrad und Fußgänger. Mit OSRM‑Routing, OpenLayers‑Karten (v10.8) und interaktiven Plotly‑Diagrammen bietet RoutePilotX eine sofort einsatzbereite Lösung für Logistik, Tourismusportale, Flottenmanagement und individuelle Mobilitätslösungen.

Ob Unternehmensanwendung, individuelle Projekte oder Cloud‑Integration – mit RoutePilotX planen Sie **präzise, effizient und professionell**.

---

# 🖥️ Showcase – Funktionsbeispiele

## 1️⃣ Gesamtüberblick

![Gesamtüberblick](assets/overview.png)

Zentrale Kartenansicht mit Auswahl von Profilen (Auto, Fahrrad, Fußgänger), Drag‑&‑Drop‑Wegpunkten und Zwischenstopps.

## 2️⃣ Profil – Auto

![Profil Auto](assets/profile_car.png)

Detailliertes Profil der Route für das Auto mit Distanz, Höhe und Steigung. Unterhalb der Statistik-Anzeige wird der gesamte Routenverlauf visualisiert.

## 3️⃣ Profil – Fahrrad

![Profil Fahrrad](assets/profile_bicycle.png)

Interaktive Analyse von Fahrradrouten über Plotly mit direkter Darstellung des Routenverlaufs unter der Statistik.

## 4️⃣ Profil – Fußgänger

![Profil Fußgänger](assets/profile_foot.png)

Optimale Darstellung für Fußgängerwege inklusive Steigung, Distanz und Routenverlauf.

## 5️⃣ Simulation – Auto

![Simulation Auto](assets/sim_car.png)

Virtuelle Fahrt entlang der Route mit dynamischem Tracking, Sprachausgabe und Routenverlauf.

---

# 🚀 Highlights

![Speed](https://img.shields.io/badge/Speed-Lightning%20Fast-ffb300?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-High-00bfff?style=for-the-badge)
![Multi-Platform](https://img.shields.io/badge/Platform-Desktop%20%7C%20Tablet%20%7C%20Web-8a2be2?style=for-the-badge)
![Realtime](https://img.shields.io/badge/Realtime-Yes-32cd32?style=for-the-badge)

* **Drei Routing‑Profile** – Auto, Fahrrad, Fußgänger mit dedizierten OSRM‑Containern
* **Interaktive Wegpunktverwaltung** – Start, Ziel, Zwischenstopps per Drag & Drop
* **Intelligente Ortsauflösung** – Ortnamen oder exakte Koordinaten (lat, lon)
* **Via‑Modus & GPX‑Export** – Einfache Zwischenstopps und GPS‑Kompatibilität
* **Echtzeit-Fahrsimulation** – Mit Sprachausgabe und dynamischem Routing
* **Kartenlayer** – OSM, Rad-/Wanderkarten, Satellitenbilder
* **Vollständig responsiv** – Desktop und Tablets
* **Docker‑basiert** – Einfache On‑Premise oder Cloud‑Installation

---

# 🗺️ Funktionsübersicht

## 📚 Routenplanung & Wegpunkte

* Start-, Ziel- und beliebig viele Zwischenpunkte
* Drag & Drop zur Sortierung
* Via-Modus: Klicke direkt auf Karte für Zwischenstopps
* Schritt‑für‑Schritt Navigation mit Entfernungsangaben
* Unterhalb der Statistik-Anzeige wird der gesamte Routenverlauf visualisiert

## 🧭 Profil & Analyse

* Interaktive Diagramme mit Distanz, Höhe, Steigung
* Maus-Hover für Detailinformationen
* Plotly Charts zur visuellen Analyse
* Routenverlauf direkt unter der Statistik-Anzeige sichtbar

## 🌐 Simulationsmodus & Sprachausgabe

* Virtuelle Fahrt entlang der Route
* Geschwindigkeit einstellbar
* Dynamische Anzeige der verbleibenden Strecke und Ankunftszeit
* Deutsche Sprachansagen für Abbiegehinweise
* Routenverlauf unterhalb der Statistik während Simulation sichtbar

## 🖼️ Karten & Layer

* OpenLayers 10.8 als Frontend-Kartenbibliothek
* Verschiedene Kartenlayer: Standard, Rad-/Wanderkarten, Satellit
* GPS-Tracking der aktuellen Position

## 📦 Routen speichern, laden & exportieren

* Browserbasierte Speicherung (IndexedDB/localStorage)
* GPX-Export für GPS-Geräte und andere Anwendungen

---

# 🔧 Technische Basis

| Komponente      | Technologie                        |
| --------------- | ---------------------------------- |
| Routing-Engine  | OSRM (Open Source Routing Machine) |
| Frontend-Karte  | OpenLayers 10.8                    |
| Diagramme       | Plotly.js                          |
| Container       | Docker + Docker Compose            |
| Backend-Skripte | Bash (init.sh) + OSRM Werkzeuge    |
| Datenquellen    | OpenStreetMap, Open-Elevation API  |

---

# 🏢 Für professionelle Nutzung konzipiert

* Präzise, Multi-Profil Routenplanung
* Integration in Unternehmens- und Cloud-Umgebungen
* Anpassbare OSRM-Profile und Kartenlayer
* Docker-basierte On-Premise oder Cloud-Bereitstellung
* Erweiterbar für individuelle Anforderungen

---

# 📦 Lizenz & kommerzielle Nutzung

RoutePilotX wird als kommerzielles Produkt unter proprietärer Lizenz angeboten. Kontaktieren Sie uns für:

* Anpassungen
* Support & Wartungsverträge
* On-Premise oder Cloud Hosting
* SLA Vereinbarungen

---

# 📞 Kontakt

**wm87 GbR**
Musterstraße 123
12345 Musterstadt
Deutschland

E‑Mail: [info@geoportal-de.example](mailto:info@geoportal-de.example)
Telefon: +49 123 4567890
Handelsregister: HRB 98765
USt‑ID: DE987654321

---

# 📄 Rechtliches

Die bereitgestellten Geodaten unterliegen den Lizenzbedingungen der jeweiligen Datenquellen (Bund, Länder, BKG, OpenStreetMap u.a.).
Für Inhalte externer Dienste wird keine Haftung übernommen.
Design und Software sind Eigentum der wm87 GbR.

---

**Die zentrale Plattform für professionelle Routenplanung, Analyse und Simulation.**
