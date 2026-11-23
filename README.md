# newportfolio2026

Avinash Bhadrakali's portfolio, served by the Cloudflare Worker `newportfolio2026`
(https://newportfolio2026.avinashxproduct.workers.dev/).

Cloudflare Workers Builds deploys this repo automatically: every push to `main`
runs `npx wrangler deploy`.

- `worker.js`: the whole site. The home page is in `HTML`, folder images in `IMGS`,
  and the SR-IOV case study in `CASE_SRIOV` (served at `/work/sr-iov`).
- `wrangler.toml`: Worker name and settings.
