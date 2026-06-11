# [LandMArk-Based-Navigation-System ](https://landnav.vercel.app/)
# LandNav - Landmark-Based Navigation System

A human-centric navigation system that replaces metric instructions ("turn right in 200m") with landmark-anchored guidance ("turn right after Apollo Hospital on your left").

## The Problem

Current navigation systems rely on distance-based cues that don't match how humans naturally navigate. People don't estimate distances — they look for recognizable landmarks. This mismatch causes missed turns, hesitation, and increased cognitive load, especially in unfamiliar areas.

## How It Works

LandNav generates turn-by-turn instructions anchored to real-world landmarks using a proprietary multi-factor salience scoring algorithm that adapts in real-time based on transport mode, time of day, atmospheric visibility, vehicle speed, and user navigation behavior.

```
Traditional: "Turn right in 200 meters"
LandNav:     "Turn right after Apollo Hospital on your left"
```

The system uses real-time GPS hardware data (position, speed, accuracy), weather and visibility conditions, and geospatial analysis to select the most contextually relevant landmark at each decision point.

## Features

- Multi-factor context-adaptive landmark salience scoring
- Real-time GPS tracking with speed-adaptive landmark selection
- Weather and visibility-aware scoring
- Approach-direction aware landmark prioritization
- Left/right spatial awareness relative to route direction
- Self-improving navigation through implicit behavioral learning
- Multiple input methods: GPS, map tap, coordinates, or place search
- Indian-context landmark categorization (temples, kiranas, branded stores)
- Responsive design for mobile and desktop

## Tech Stack

- **Map**: Leaflet.js + OpenStreetMap tiles
- **Routing**: OSRM (Open Source Routing Machine)
- **Landmarks**: Overpass API (OpenStreetMap)
- **Weather**: Open-Meteo API
- **Geocoding**: Nominatim

## Team

- Dharunpathi T (ED23B018)
- Divyesh Kumar N (ED23B020)
- Lohith Reddy (ED23B082)

**Mentor:** Dr. Harikrishna Rangam

Department of Engineering Design, IIT Madras

## License

All rights reserved. Patent pending.
