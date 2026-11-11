# UoA City Indoor Map (unofficial)

A lightweight 3D indoor map of the University of Auckland **City Campus**: search a room number
(`401-439`, `260-098`, `303-G20`), a building, or a facility (`toilet`, `lift`, `eng lecture`) and see
which building, which floor, and where on that floor it is.

**This is a student-made, non-commercial project. It is not an official University of Auckland product
and is not affiliated with or endorsed by the University.**

## What it does

- Campus view with every University building as a 3D model, surrounding streets and street names
- Per-building cutaway: pick a level and see its rooms, corridors, stairs, lifts and toilets
- Search by room number, building number or name, room type, or level (`401 level 4`)
- Building entrances with a Google Maps walking link to the exact door
- Works on phones; panels can be collapsed
- Works offline after the first visit

## Data and copyright

This repository contains **only the page code and OpenStreetMap data**.

| Data | Source | In this repository? |
|---|---|---|
| Rooms, floors, building outlines | © University of Auckland, from its public map service ([maps.auckland.ac.nz](https://maps.auckland.ac.nz/)) | **No.** Each visitor's browser downloads it directly from the University's service on the first visit and stores it on that device only. |
| Streets, neighbouring buildings, entrances | © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), Open Database Licence (ODbL) | Yes, embedded in `map.html` |
| Page code | This project, MIT licence | Yes |

The 3D shapes, walls, stairs, street levels and room colours are approximations derived from that data
for orientation only. Do not rely on them for safety or accessibility decisions; the official map is the
authority.

## Takedown

If you are a rights holder and want anything changed or removed, please open an issue on this
repository. It will be taken down promptly.

## Running it

Open `map.html` from any web server (for example GitHub Pages). The first visit needs an internet
connection and takes a few seconds while about 20,000 rooms are downloaded; after that it starts
instantly and works offline. Use **About → Re-download campus data** to refresh.
