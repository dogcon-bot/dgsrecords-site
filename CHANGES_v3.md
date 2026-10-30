# dgsrecords_site · CHANGES v3

Date: 2026-10-30 (America/Los_Angeles)

## Wording (label first; DJ Dogcon is one roster artist)

- Removed every "Home of DJ Dogcon" / "home of DJ Dogcon".
- Removed "Flagship" kicker; replaced with **Roster**.
- DJ Dogcon blurb rewritten neutrally: rap and Northwest techno out of Washington. No Aberdeen, no "Leon Lawson", not techno-only.
- Meta description, og:description, JSON-LD description, and hero lede set to label-only copy:
  > DGS Records is Washington State's record label. Holding down the Northwest with PNW rap and Northwest techno. Artists, producers and DJs: sign with DGS.
- Avatar alt text: "DGS Records mark" (was "DJ Dogcon / DGS Records mark").
- PROFILE_KIT_2026-10.md Facebook intro: dropped "Home of DJ Dogcon."

## Hero video

- Switched hero `<video>` from `assets/hero/signing_loop_720.mp4` to takeover sources:
  - `assets/hero/DGS_hero_takeover_9s.webm`
  - `assets/hero/DGS_hero_takeover_9s.mp4`
- Copied both files from `/workspace/dgs_brand/commercials/out/`.
- Left `signing_loop_720.mp4` in the tree unused (safe to delete on a later cleanup; not referenced).

## Infra kept

- `CNAME` → `dgsrecords.com`
- `.nojekyll` present (touched)

## Not in this deploy

- Alias roster pages / artist cards **not** added to the live site yet (data only at `/workspace/dgs_brand/roster/`).

## Grep confirmation

Zero case-insensitive matches for `home of dj dogcon|flagship|indie|independent` in `/workspace/dgsrecords_site/` and `/workspace/PROFILE_KIT_2026-10.md` after edits.

## Bundle

`/workspace/dgsrecords_site_bundle_v3.tgz` — full site folder for push to https://github.com/dogcon-bot/dgsrecords-site (GitHub Pages).
