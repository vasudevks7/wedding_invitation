# Nazel - Wedding Invitation & Guest Feedback Dashboard

A digital wedding invitation web application for Fahad & Nesrin, complete with Arabic calligraphy, countdown timer, background ambient music, and a guest feedback form with an administrative review dashboard.

## Features

- **Cover & Unfolding Invitation**: Animated transition from the envelope cover to the formal wedding invitation card.
- **Background Music**: Ambient wedding chimes & harp audio loop (`music.mp3` / `music.wav`) with interactive audio controls (`♪` / `♫`).
- **Live Countdown Timer**: Countdown to the celebration on Wednesday, December 30, 2026.
- **Guest RSVP & Wishes**: Attendance response (Attending / Not Attending), optional star rating, and blessings with reliable localStorage backup and Supabase cloud sync.
- **Private Admin Dashboard (`admin.html`)**: Protected portal for reviewing guest RSVPs, attendance counts, average rating, CSV export, and deletion.
- **Local Dev Server (`serve.js`)**: Lightweight Node.js static server with HTTP range support for media streaming and clean URL routing.

## Getting Started

Open `index.html` directly in any web browser, or start the local server:

```bash
node serve.js
```
Then visit:
- **Home Hub**: [http://localhost:3000](http://localhost:3000)
- **Invitation**: [http://localhost:3000/invite.html](http://localhost:3000/invite.html) (or `http://localhost:3000/invite`)
- **Admin Dashboard**: [http://localhost:3000/admin.html](http://localhost:3000/admin.html) (or `http://localhost:3000/admin`)

