# Postiz Media Relay (GitHub Pages)

Public mirror of Postiz `/uploads/` for Meta Graph API consumption.

Used as a backup `MEDIA_PUBLIC_URL` when Vercel or other relays misbehave.

URL format: `https://asafyaacobi.github.io/postiz-media/2026/04/20/<hash>.png`

Sync flow: `docker cp postiz:/uploads/. ./` then `git add -A && git commit && git push`.
