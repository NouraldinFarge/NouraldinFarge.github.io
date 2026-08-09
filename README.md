# Nouraldin Farge — Portfolio Deployment

Generated GitHub Pages deployment for Nouraldin Farge’s software engineering portfolio.

Live site: <https://nouraldinfarge.github.io>

The site highlights:

- DrawScope v0.6.5
- GameVault v0.3.5
- Day-Trading Teacher v0.32.6
- Research Studio v0.1.0-alpha.21, presented as a source-free engineering case study

## Repository role

This repository contains generated deployment output rather than the maintainable application source. It intentionally ships only static HTML, CSS, referenced fonts and images, the résumé, crawl metadata, and a dedicated 404 page. No executable JavaScript or runtime service is required.

Each publication is produced from the version-controlled portfolio source after its rendered-HTML and static-export tests, lint checks, production build, and production dependency audit pass. The exporter copies only referenced assets and verifies that the deployed résumé matches the current ATS-tested PDF. Generated `index.html` and `404.html` files should not be edited by hand.

For readable engineering evidence, follow the project repositories and case study linked from the live site.
