<div align="center">
  <img src="https://raw.githubusercontent.com/PicPeak/picpeak/main/docs/picpeak-logo.png" alt="PicPeak" width="280" />

  ### Open-source, self-hosted photo sharing for events

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?logo=docker&logoColor=white)](https://ghcr.io/picpeak/picpeak/backend)
  [![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-theluap-FFDD00?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/theluap)

  [Homepage](https://www.picpeak.app) · [Live Demo](https://demo.picpeak.app) · [Documentation](https://docs.picpeak.app)
</div>

---

**PicPeak** is a powerful, self-hosted open-source alternative to commercial
photo-sharing platforms like PicDrop and Scrapbook. Built for photographers and
event organizers, it makes sharing beautiful, time-limited client galleries
simple — while you keep full control over your data and branding.

### Why PicPeak

- 💰 **No monthly fees** — one-time setup, unlimited galleries
- 🔒 **Your data, your server** — nothing leaves your infrastructure
- 🎨 **White-label ready** — full branding customization
- 📱 **Mobile-first** — beautiful on every device
- 🌍 **Multi-language** — EN / DE built in

### Repositories

| Repo | What it is |
|------|-----------|
| [**picpeak**](https://github.com/PicPeak/picpeak) | The main application (backend + frontend) |
| [**docs**](https://github.com/PicPeak/docs) | Documentation site sources ([docs.picpeak.app](https://docs.picpeak.app)) |
<!-- Add companion app / plugin repos here as they land -->

### Get started

Up and running in under 5 minutes with Docker:

```bash
# 1. Clone
git clone https://github.com/PicPeak/picpeak.git
cd picpeak

# 2. Copy the environment template — defaults work out of the box.
#    Machine secrets (JWT, DB, Redis) are auto-generated on first run.
cp .env.example .env

# 3. Start
docker compose up -d

# 4. Open http://localhost:3000
```

**First run — create your admin account:** open
[http://localhost:3000/admin](http://localhost:3000/admin) (you'll be redirected
to `/setup`), grab the one-time setup token from the logs
(`docker compose logs backend | grep -i "setup token"`), then set your admin
email + password. See the [documentation](https://docs.picpeak.app) for the full
walkthrough, configuration, and production deployment.

### Try it first

Live demo at **[demo.picpeak.app](https://demo.picpeak.app)** — admin login
`demo@picpeak.app` / `Demo2026!` (resets periodically; uploaded content may be
removed without notice).

### Contributing & support

- 🐛 Found a bug or have an idea? [Open an issue](https://github.com/PicPeak/picpeak/issues)
- 🤝 [Contributing guide](https://github.com/PicPeak/.github/blob/main/CONTRIBUTING.md)
- 💬 [Discussions](https://github.com/PicPeak/picpeak/discussions)
- 🔒 [Security policy](https://github.com/PicPeak/.github/blob/main/SECURITY.md)
- ☕ [Support the project](https://buymeacoffee.com/theluap)

<div align="center"><sub>MIT licensed · Made for photographers, by developers</sub></div>
