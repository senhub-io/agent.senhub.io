# agent.senhub.io

Source of the [agent.senhub.io](https://agent.senhub.io) landing page.

Static HTML, no build step. Edit `index.html` directly.

Served via GitHub Pages, deployed automatically on push to `main`.
The custom domain is set through the `CNAME` file (`agent.senhub.io`).

## Related

- Agent source code — [github.com/senhub-io/senhub-agent](https://github.com/senhub-io/senhub-agent)
- Documentation — [agent.senhub.io/docs](https://agent.senhub.io/docs/)
- Platform — [senhub.io](https://senhub.io)

## Updating the social preview image

`assets/og-image.png` (1200×630) is rendered from `assets/og-image.html`.
After editing the HTML, re-export the PNG (e.g. headless Chrome screenshot
at 1200×630) and bump the `?v=` query in the `og:image` / `twitter:image`
tags in `index.html` so scrapers refetch it.

## License

Apache License 2.0. See [LICENSE](./LICENSE).
