# Neethu & Ajnas — A Celebration of Love & New Beginnings

Interactive, responsive wedding reception & housewarming invitation website for **Neethu Mohan** & **Ajnas CH**.

## Event Details
- **Occasions**:
  1. **Wedding Reception**: Neethu Mohan (D/o Mohanan PP & Praveena K.) & Ajnas CH (S/o Pocker K & Hajira CH)
  2. **Housewarming Ceremony**: Of our new home — **ELORA**
- **Date**: Sunday, 20th December 2026
- **Time**: 5:00 PM onwards
- **Venue**: ELORA, Pathinaramparamba, Malappattam

---

## Features
- **Hero & Countdown**: Live countdown timer configured for Sunday, 20 December 2026 at 5:00 PM IST.
- **Audio & BGM Controls**: Background music with audio controls and track catalog selector.
- **Dual Event Cards**: Dedicated cards for the Wedding Reception and the Housewarming Ceremony with Google Maps directions and Add to Calendar options.
- **Family Details**: Bride & Groom family introductions with parental blessings.
- **Interactive Lightbox Gallery**: High-resolution gallery with modal slideshow view.
- **Live Guest Wishes**: Realtime Firebase guestbook feed and submission.
- **Downloadable Card & PDF**: Printable PDF export and celebration card save buttons.

---

## Quick Start (Run Locally)

You can preview the website using any local static server:

### Option 1: Python
```bash
python3 -m http.server 8000
```
Then visit [`http://localhost:8000`](http://localhost:8000).

### Option 2: Node / npm
```bash
npm start
# or
npx serve .
```

---

## Structure
```text
.
├── index.html                           # Main invitation website
├── wedding-card.jpg                     # Downloadable card
├── og-thumb.png                         # Social preview image
├── package.json                         # Node configuration
├── README.md                            # Documentation
└── assets/
    ├── cover-couple.jpg                 # Hero cover image
    ├── hero-clouds-sound.mp4            # Background video
    ├── wedding-bgm.mp3                  # Background audio track
    ├── bg-clouds-deep.jpg               # Background artwork
    ├── bg-clouds-soft.jpg               # Background artwork
    ├── bg-pattern.jpg                   # Background texture
    ├── library.js                       # Audio library tracks
    ├── gallery/                         # Gallery photos (gallery-01 to gallery-14)
    └── vendor/                          # Client dependencies
```
