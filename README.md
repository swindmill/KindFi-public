# KindFi

**Clear is kind.**

KindFi is an iOS app for parents to manage UniFi firewall rules by family member, right from their iPhone - one-tap blocking, ALLOW-carve-out Exceptions, timed extensions, and scan-to-onboard setup for additional devices. Everything stays on your local network; there's no cloud account, no backend, and no data collection.

This repository exists to host KindFi's support and privacy information for its App Store listing, served at [kindfi.net](https://kindfi.net/). KindFi's source code is maintained in a private repository.

## Support

Have a question, found a bug, or need help? [Open an issue](https://github.com/swindmill/KindFi-public/issues) on this repository.

## Privacy

See [PRIVACY.md](PRIVACY.md), published at [kindfi.net/privacy.html](https://kindfi.net/privacy.html).

## About

KindFi includes open-source software. Full license attribution is included in-app under Settings > Open Source Licenses.

UniFi and UniFi Network Application are trademarks of Ubiquiti Inc. KindFi is not affiliated with Ubiquiti Inc.

---

## Note for maintainers: this repository is generated

**Every tracked file here is build output. Do not edit them in place - the next
build will overwrite your changes without warning.**

The sources live in KindFi's private source repository:

| File here | Source |
|---|---|
| `index.html`, `privacy.html`, `style.css`, `CNAME` | `site/` |
| `README.md` (this file) | `site/README.md` |
| `PRIVACY.md`, and the body of `privacy.html` | `PRIVACY.md` (repo root - the canonical copy) |
| `favicon.svg`, `favicon.ico`, `icon.png` | `docs/app-store/icons/kindfi/`, via `Scripts/render_icons.sh` |

To change anything on the site, edit the source there and run:

```
Scripts/build_site.sh
```

which writes the result straight into this working copy, ready to review,
commit, and push. GitHub Pages publishes within about a minute.

### Why this repository has only one commit

`Scripts/build_site.sh --publish` replaces this repository's history with a
single commit and force-pushes it, so what is public is the current state of
the site and nothing else. The history is not lost - it lives in the private
source repository, where the site's actual sources are versioned.

This exists because GitHub Pages cannot serve a private repository on a free
account, so the repository has to be public to publish the site. Making its
history carry nothing worth reading is the next best thing.

Issues are unaffected by this. They are not stored in git, so the tracker,
its threads, and their URLs survive the rewrite untouched.
