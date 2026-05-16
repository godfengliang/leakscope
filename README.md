# LeakScope

[![Live Demo](https://img.shields.io/badge/Live_Demo-leakscope.surge.sh-brightgreen?style=for-the-badge)](https://leakscope.surge.sh)

> See exactly what your browser reveals to every website you visit.

**Try it now:** [leakscope.surge.sh](https://leakscope.surge.sh)

## What it detects

- **Canvas Fingerprint** — unique rendering hash
- **WebGL** — GPU vendor and renderer
- **Screen & Display** — resolution, color depth, pixel ratio
- **Timezone & Locale** — TZ, language, date format
- **Hardware** — CPU cores, memory, platform, touch support
- **Battery** — level, charging status
- **Storage & APIs** — localStorage, IndexedDB, Service Workers
- **Permissions** — geolocation, camera, microphone, notifications

## Features

- Privacy score (0-100) with animated ring
- Shareable score card for social media
- Per-category leak assessment
- Zero network requests — all checks run locally

## Tech

Single HTML file. Zero dependencies. Pure browser APIs.

Canvas API, WebGL, Battery API, Permissions API, Intl API.

## License

MIT
