# dontwait.fyi

## 🌐 Live at [dontwait.fyi](https://dontwait.fyi)

A one-pager for sending to people who hold meetings for late arrivals.

_Disclaimer: All good-natured grumbles. Garrett is actually a delight._

Inspired by [nohello.net](https://nohello.net) and [noagendameeting.com](https://noagendameeting.com) — one-pagers for things that shouldn't need explaining.

[![GitHub](https://img.shields.io/badge/GitHub-100000?logo=github&logoColor=fff&style=flat)](https://github.com/GarrettSmith/dontwait.fyi) &nbsp; <a href="https://ko-fi.com/X8X61XQPH0" target="_blank"><img height="36" style="border:0px;height:36px;" src="https://storage.ko-fi.com/cdn/kofi2.png?v=3" border="0" alt="Buy Me a Coffee at ko-fi.com" /></a>

---

## Development

Single file: `index.html`. No build step, no dependencies beyond Google Fonts.

Open it directly in a browser:

```
open index.html
```

## Deployment

Push to the `main` branch. GitHub Pages serves `index.html` automatically.

## UTM Tracking

Share links use `r.html` as a redirect to add UTM params. Supported `src` values:

| src param | utm_source | Use when sharing via |
|-----------|------------|----------------------|
| `clipboard` | clipboard | Copy button on the page |
| `linkedin` | linkedin | LinkedIn |
| `twitter` | twitter | Twitter / X |
| `reddit` | reddit | Reddit |
| `hn` | hackernews | Hacker News |
| `mastodon` | mastodon | Mastodon |
| `slack` | slack | Slack |
| `whatsapp` | whatsapp | WhatsApp |
| `email` | email | Email |
| `default` | default | Fallback |

To add a new source: edit `r.html` and add to the `utmMap` object.

```
git add index.html
git commit -m "your message"
git push
```
