# SMN Cutz

- `/` — public booking page. Clients pick Cut / Beard / Eyebrows and send a request.
- `/admin` — private shop app (email login, owner only): requests, schedule, clients, photos.

Static site on Vercel, data in Supabase (`config.js` holds the public project URL and publishable key; access is enforced by row-level security).
