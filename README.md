# ta-player

The Tragedy Academy's custom episode player.

Embed on a Podpage episode page (Custom Player box):

```html
<div data-ta-player="ep135"></div>
<script>(function(){var s=document.createElement("script");s.src="https://jay0997.github.io/ta-player/player.js?v="+Date.now();document.body.appendChild(s);})();</script>
```

Each episode lives in its own folder (`ep135/`): `data.json` (words, phrases, lessons), `eq.bin` (EQ energy), `cover.jpg`, `guest.jpg`, `share.jpg`. Audio plays from the published Riverside episode (URL in `data.json`).
