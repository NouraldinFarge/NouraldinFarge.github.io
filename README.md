# Nouraldin Farge — React & TypeScript Software Engineering Portfolio

Generated GitHub Pages deployment for Nouraldin Farge’s React/TypeScript software-engineering portfolio.

Live site: <https://nouraldinfarge.github.io>

Maintainable source: <https://github.com/NouraldinFarge/portfolio-source>

The site highlights:

- DrawScope v0.6.5
- GameVault v0.3.5
- Day-Trading Teacher v0.36.0, a 13-lesson public Windows release
- Research Studio private build v0.1.0-alpha.24, with a public source-free case-study snapshot verified August 15, 2026 and a dedicated project page at
  <https://nouraldinfarge.github.io/research-studio/>

The site also has a deliberately separate [Active public-source prereleases](https://nouraldinfarge.github.io/#active-source) section for Reader, Media Scout, and SiteWipe. These repositories are available for code review while release gates remain open; they are not presented as supported releases or downloads.

## Repository role

This repository contains generated deployment output rather than the maintainable application source. It intentionally ships only static HTML, CSS, referenced images, the résumé, crawl metadata, and a dedicated 404 page. No executable JavaScript or runtime service is required.

Each publication is produced from a clean, version-controlled [portfolio source](https://github.com/NouraldinFarge/portfolio-source) revision after its rendered-HTML, static-export, desktop/mobile Chrome and Axe, lint, and production-build checks pass. The exporter copies only referenced assets, rejects executable bundles and local development paths, verifies that the deployed résumé matches the current ATS-tested PDF, and writes the exact source revision to [`portfolio-build.json`](portfolio-build.json). This repository validates the generated artifact independently on every pull request. After changes reach `main`, a second least-privilege job deploys only the verified artifact through SHA-pinned official GitHub Pages actions. Generated HTML and CSS should not be edited by hand.

For readable engineering evidence, follow the maintainable source, project repositories, and case study linked from the live site. Report portfolio vulnerabilities through the [source repository’s private security channel](SECURITY.md), not a public issue here.

## License

Generated source code is covered by the [MIT License](LICENSE). Personal portfolio copy, résumé content, branding, and media assets are excluded from that grant; see [CONTENT-LICENSE.md](CONTENT-LICENSE.md).
