# Trento hike planner – bus and train

A small web app for planning hikes from Trento (Trentino, Italy) by public transport: pick a date, see which places you can reach by
bus or train (directly or with **one change**), how long the ride takes, when the last way home leaves and how that compares with
sunset. Every place gets a verdict: Comfortable, Tight, Risky or No way back.

The app speaks **English and Ukrainian** (it follows your device language; switch in Filters → Language) and has a **light and a dark theme** (Filters → Theme, default: follows the device).

**Open it:** https://boreico.github.io/trento-hike-planner/ – on Android Chrome use the menu → *Install app* (it then opens full screen
and the timetable works offline; the map tiles need a connection). On iPhone: Share → *Add to Home Screen*.

Мобільний планувальник походів з Тренто: автобуси й потяги, зворотна дорога, захід сонця (українською: Filters → Мова).

This repository only holds the generated site (`index.html` contains the whole timetable). It is rebuilt from a private project;
the timetable is valid until the dates shown in the app (buses to 25 Jun 2027, trains to 12 Dec 2026).

## Data and credits

- Buses and the Trento–Malè railway: **Trentino Trasporti open data** (GTFS, extraurban), licence CC BY 2.5 –
  <https://www.trentinotrasporti.it/>.
- Brenner-line trains (Verona – Trento – Bolzano): **STA – Open Data Hub South Tyrol**, CC0 – <https://opendatahub.com/>.
- Valsugana line trains (Trento – Pergine – Borgo – Bassano): read from Trentino Trasporti's published timetable PDFs.
- Map: © OpenTopoMap (CC-BY-SA), © OpenStreetMap contributors, hiking trails © waymarkedtrails.org; map library Leaflet (BSD-2).

## No guarantee

Timetables change, strikes and replacement buses are not in the data, a bus stop is not a trailhead, and sunset is a flat-ground
estimate. Always check <https://www.trentinotrasporti.it/> and <https://www.trenitalia.com/> before you travel. Not affiliated with
Trentino Trasporti, Trenitalia or STA.
