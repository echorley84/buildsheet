# Tiny Bytes

Interactive issues of Tiny Bytes, the Saturday newsletter from Pick & Mix Studios.

Live at https://pickandmixstudios.com/tinybytes/

Each issue lives in its own folder (`welcome/`, `001/`, `002/` ...) as a single `index.html`.
The Bluehost server pulls this repo every 5 minutes into public_html/tinybytes, so anything pushed to `main` goes live automatically.

Subscribe: https://tinybytes.beehiiv.com/subscribe

## Adding an issue

1. Put the issue in its own folder (`002/index.html`, and so on).
2. Add a card for it at the top of the list in `index.html`, the archive page at /tinybytes/. Set `data-release` to the send time in UTC. The card stays hidden until that time, then shows a "New" tag for a week.
