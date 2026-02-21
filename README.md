# VibeRide

A web-based ride-hailing prototype that matches riders with drivers based on **ride vibe preferences** rather than just proximity.

## Concept

Riders select their preferred ride vibe — like Chill & Quiet, Party Mode, or Music Lover — and get matched with drivers who support that vibe. The focus is on personality-based compatibility to make every ride enjoyable.

## Features

### Rider Flow
- Enter pickup and drop-off locations
- Choose a ride vibe from 6 options
- Browse matched drivers ranked by rating and experience
- View driver profiles with vibe tags, vehicle info, and trip count
- **Live ride tracker** with animated SVG map, ETA countdown, and trip phases

### Driver Flow
- Create a driver profile with name and vehicle
- Select multiple vibes you support
- View your saved profile card with stats
- Get added to the live driver pool for matching

### Ride Vibes
| Vibe | Description |
|------|-------------|
| Chill & Quiet | Peaceful, minimal conversation |
| Chat & Connect | Friendly conversation welcome |
| Music Lover | Great playlists, volume up |
| Party Mode | High energy, good times |
| Work & Focus | Quiet space, get things done |
| Podcast & Learn | Discover something new |

### Live Ride Tracker
After selecting a driver, a full tracking experience plays out:
- Animated car moving along a city map route
- Phase transitions: heading to pickup, arrived, en route, destination reached
- Real-time ETA countdown ring
- Trip progress bar
- Driver info strip with call button
- Trip summary with fare and vibe rating on arrival

## Tech Stack

Single-file HTML/CSS/JS — no frameworks, no build step, no dependencies. Just open `index.html` in a browser.

## Running

```bash
open index.html
```

Or double-click the file to open it in your default browser.

## Scope

This is an MVP prototype focused on **preference matching only**. It does not include:
- Real navigation or maps API
- Payment processing
- Backend or database
- User authentication

All driver data is hardcoded in a small dataset within the app.
