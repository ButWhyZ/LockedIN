# LockedIN
A real-time LinkedIn networking web app for events and meetups.  Join a room, see who's in the room, and track connections live!


# LockedIN

> Walk in. Lock in. Link up.

LockedIN is a real-time LinkedIn networking web app built 
for events, GBMs, classes, and meetups. Hosts create a 
room and share a QR code. Attendees scan to join, see 
everyone in the room as live profile cards, and track 
their connections — all without sending a single cold DM.

---

## Features

- LinkedIn OAuth authentication
- Create and host rooms with a QR code and short room code
- Live attendee list with list and grid view
- Connection tracking — none → in progress → connected
- Private notes per connection
- Post-room summary with follow-up nudges
- Account history across all past rooms
- Fully responsive — mobile and web

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React (Vite) |
| Backend | Django + Django REST Framework |
| Database | PostgreSQL |
| Realtime | Polling (MVP) → Django Channels (post-MVP) |
| Auth | LinkedIn OAuth via social-auth-app-django |
| Hosting | Vercel (frontend) · Railway (backend + database) |

---

## Getting Started

### Prerequisites
- Python 3.11+
- Node.js 18+
- PostgreSQL
- LinkedIn Developer App credentials

