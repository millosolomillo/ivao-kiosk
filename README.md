# IVAO Live Airport Board

A full‑screen, **blue‑and‑yellow airport‑style arrivals & departures board** powered by the [IVAO Whazzup v2 JSON feed](https://wiki.ivao.aero/en/home/devops/api/whazuup/file-format-v2).  
It displays **live** pilot and ATC data for a selected airport ICAO code, updating automatically every minute:

https://millosolomillo.github.io/ivao-kiosk/

---

## ✈ Features

- **Live IVAO data** — pulls directly from the official Whazzup v2 JSON feed.
- **Arrivals & Departures tables** — shows callsign, origin/destination, aircraft type, flight phase, and ETA/ETD.
- **UTC times** — ETA and ETD are converted from IVAO’s “seconds since midnight UTC” into `HH:MM UTC` format.
- **Auto‑refresh** — updates every 60 seconds without reloading the page.
- **Full‑width airport display** — styled in classic deep blue with bright yellow text for maximum readability.
- **URL parameter support** — pre‑fill and auto‑load an airport by adding `?icao=XXXX` to the page URL.

---

## 🖥 Usage

1. Open the page in your browser (e.g. via GitHub Pages).
2. Enter a **4‑letter ICAO code** (e.g. `EHAM`) in the input box.
3. Click **Show** — the board will load arrivals and departures for that airport.
4. The board will refresh automatically every minute.

---

## 🔗 Quick‑link to a specific airport

You can share a link that opens directly to a specific airport by adding `?icao=XXXX` to the URL:
https://millosolomillo.github.io/ivao-kiosk/?icao=LEMD

