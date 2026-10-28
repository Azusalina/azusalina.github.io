# Azusalina

## What is it?

The public entry page at https://azusalina.github.io/ for choosing JUPASCal or someProducts. Architecture and maintenance are in [description.md](description.md).

## How to use

Open the website and choose a site. Use the Light/Dark button to change the theme; the choice stays in this browser. No installation or account is required.

To preview locally, run `python3 -m http.server 8790 --bind 127.0.0.1` here and open http://127.0.0.1:8790/ . Destination links use their live domain paths; local preview does not include those independent sites.

Commit and push `master` to publish the static page through GitHub Pages. There are no build dependencies. Stop the local preview with Ctrl+C.
