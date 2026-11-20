# Thanksgivukkah

A one-page countdown to the next time Thanksgiving and Hanukkah collide (next: Nov 27, 2070; last: Nov 28, 2013).

## Setup

1. Settings → Pages → Source: **GitHub Actions**.
2. Settings → Secrets and variables → Actions → Variables: add `GA_MEASUREMENT_ID` (e.g. `G-XXXXXXX`). It is injected into `index.html` on deploy; leave it unset to deploy without analytics.
