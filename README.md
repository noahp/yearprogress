# yearprogress

A tiny single-page site showing how much of the current year has elapsed.

Live at [yearprogress.noahpendleton.com](https://yearprogress.noahpendleton.com).

## Stack

Static `index.html` — no build step, no dependencies. The percentage is
computed client-side and ticks every second.

## Deploy (GitHub Pages)

1. Push to GitHub.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The `CNAME` file sets the custom domain to `yearprogress.noahpendleton.com`.
4. Add a DNS `CNAME` record for `yearprogress` → `<user>.github.io`.
