<h1 align="center">HevalMedia</h1>
<p align="center">Ein freier Medienserver – gebrandet, gestylt und mit Donate-Option – als Community-Fork von Jellyfin.</p>

<p align="center">
  <a href="./LICENSE"><img alt="License: GPLv2" src="https://img.shields.io/badge/license-GPLv2-blue"></a>
  <a href="https://github.com/ismail1411/HevalMedia/releases"><img alt="Releases" src="https://img.shields.io/github/v/release/ismail1411/HevalMedia?display_name=tag"></a>
  <a href="https://hub.docker.com/r/ismail1411/hevalmedia"><img alt="Docker" src="https://img.shields.io/badge/docker-hevalmedia-2496ED?logo=docker&logoColor=white"></a>
</p>

---

## Überblick

**HevalMedia** ist ein Fork des Open-Source-Medienservers **Jellyfin**.
Ziele dieses Forks:

-   **Eigenes Branding & Styling** (Name, Logo, Farben, Fonts)
-   **Donate-Button (PayPal)** in der Web-UI
-   Bereitstellung via **Docker** und klare Entwickler-Doku

> **Hinweis:** HevalMedia ist **kein offizielles Jellyfin-Projekt** und verwendet **nicht** das Jellyfin-Logo/Branding.
> Upstream: [Jellyfin](https://github.com/jellyfin/jellyfin) (GPLv2).

---

## Features

-   🎨 **Branding & UI**: angepasstes Theme, eigene Assets
-   💝 **Spendenintegration**: PayPal-Link direkt im UI
-   🐳 **Docker-Image**: schneller Start auf Servern/NAS
-   🧩 **Kompatibel** mit der Jellyfin-Ökosphäre (Clients/Apps)

---

## Schnellstart

### Docker (empfohlen)

```bash
docker run -d --name hevalmedia \
  -p 8096:8096 \
  -v /pfad/zu/medien:/media \
  -v /pfad/zu/config:/config \
  ismail1411/hevalmedia:latest
```
