# MRI Guard — support site

Live at <https://papaetfilles.github.io/mriguard-support/> (GitHub Pages).

**Do not edit the files in this repository.** They are copies.

The pages are written in the app repository, under `appstore/website/`,
next to the app whose strings, prices and claims they have to agree with —
and published from there with `./deploy.sh`. Editing here creates a second
version that silently drifts from the app, which is exactly what happened
between July and September 2026.

Static HTML, no build step, no dependencies. The App Store badges are
Apple's own artwork, stored in the repo rather than hotlinked, in a black
and a white variant swapped by `prefers-color-scheme`.
