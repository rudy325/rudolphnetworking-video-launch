# Rudolph Networking Video Launch

Small static launch page intended for `video.rudolphnetworking.com`.

## Run locally

```bash
npm start
```

## Deploy

This app is Railway-friendly out of the box:

- Start command: `npm start`
- Port: provided by Railway via `PORT`

After deploy, point the `video` subdomain in Cloudflare to the Railway domain with a `CNAME` record.
