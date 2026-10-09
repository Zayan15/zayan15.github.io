# Zayan Haroon Moosa — Engineering portfolio

A static portfolio for AWS automation and application engineering, published at [zayan15.github.io](https://zayan15.github.io/).

## Pages

- `index.html`: project cards, professional experience, skills, certifications, and contact links.
- `proledger.html`: ProLedger architecture case study and a standalone fictional ledger illustration. No authentication, cloud requests, or persistent storage.
- `demos.html`: illustrated workflows for the four AWS projects, using synthetic examples.
- `Zayan-Haroon-Moosa-Resume.pdf`: public résumé download.

Built with HTML, CSS, and small browser-side JavaScript demos. No build step or external JavaScript dependency is needed. The demos illustrate workflows; they are not live runs of the underlying projects.

## Preview and review

Run `python3 -m http.server 8000` from the repository directory, then open `http://localhost:8000`.

Check mobile and desktop layouts, project and résumé links, keyboard focus, and interactive demo controls. In the ProLedger demo, adding the $24.50 sample receipt changes spending from $1,935.00 to $1,959.50 and grocery spending from $185.00 to $209.50. Reset restores the original fictional data. Transfers are excluded from spending.

Project descriptions are grounded in reviewed local source. Keep production-validation limits explicit. Use only synthetic demo data; exclude credentials, private ledger records, and employer-confidential material.

## Publishing

The site is served through GitHub Pages. Open a pull request for changes and merge after review; the repository's configured Pages deployment publishes the main branch. A pull request alone does not update the public site.
