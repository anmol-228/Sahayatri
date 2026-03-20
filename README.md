# Sahayatri

Sahayatri is a frontend prototype for smarter public transport flows, built around commuter discovery, route visibility, and driver-side crowd status updates.

## Overview

The project was built as a Smart India Hackathon-style transport prototype focused on improving urban commute usability through clearer route discovery and mobile-friendly interface flows.

The repository includes:

- `user-app/`: commuter interface for route discovery, map-based tracking, and bus status views
- `driver-app/`: driver interface for trip startup and crowd-level updates
- `index.html`: simple landing page that links both flows for easier project preview

## Problem Statement

Urban commuters often struggle to identify routes, understand transport flow, and access clear live-style information in one place.

## Features

- separate commuter and driver modules
- route-oriented UI and navigation flow design
- map-based visualization using Leaflet and OpenStreetMap
- responsive layouts built with Bootstrap and custom styling

## Tech Stack

- HTML
- CSS
- JavaScript
- Bootstrap 5
- Leaflet
- OpenStreetMap

Planned future scope:

- Spring-based backend integration
- database-backed transport data
- real-time status synchronization

## Project Structure

```text
.
├── index.html
├── user-app/
│   └── index.html
└── driver-app/
    └── index.html
```

## Running Locally

This is a static prototype, so you can run it with any simple local server.

```bash
python3 -m http.server 8000
```

Then open:

- `http://localhost:8000/`
- `http://localhost:8000/user-app/`
- `http://localhost:8000/driver-app/`

## Current Status

This repository focuses on product flow, interface design, and frontend interaction patterns. It is a working prototype, and production backend services are not included yet.
