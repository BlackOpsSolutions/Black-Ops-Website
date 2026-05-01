# Black Ops Solutions IT — blackops.net.au

Marketing site for **Black Ops Solutions IT** — Australian IT consulting, cyber security, custom software, SaaS, AI automation, managed services, migrations and infrastructure.

Live: <https://blackops.net.au/>

## Stack

- Static single-page site, no build step
- Hosted on GitHub Pages with a custom domain (see `CNAME`)
- Bootstrap 4 grid + custom CSS in `styles/main.css`
- Vanilla JS in `scripts/main.js`
- SVG brand assets in `img/`

## Project layout

| Path                          | Purpose                                            |
|-------------------------------|----------------------------------------------------|
| `index.html`                  | Whole site — nav, hero, services, AI, AlertaVuln, projects, contact, footer |
| `styles/main.css`             | All site styles                                    |
| `scripts/main.js`             | Nav toggle, year stamp, scroll handling            |
| `img/BOS-wordmark.svg`        | Long-form Black Ops Solutions wordmark             |
| `img/AlertaVuln-sticker.svg`  | AlertaVuln wordmark sticker (matches BOS frame)    |
| `img/AlertaVuln-logo.svg`     | Raw AlertaVuln shield mark                         |
| `img/favicon.svg`             | Site favicon — BOS hex mark                        |
| `robots.txt`, `sitemap.xml`   | Crawl + indexing                                   |
| `CNAME`                       | GitHub Pages custom domain                         |

## Local preview

```powershell
python -m http.server 8181
```

Open <http://127.0.0.1:8181/>.

## License

Proprietary. All rights reserved by Black Ops Solutions — see [`LICENSE.md`](LICENSE.md).

This repository is published for transparency of the live site only. It is **not** licensed for reuse, redistribution, modification, or derivative works. The Black Ops Solutions and AlertaVuln names, logos, wordmarks and brand artwork are trademarks of Black Ops Solutions.
