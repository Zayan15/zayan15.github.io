# Zayan Haroon Moosa — Personal portfolio

A responsive, static portfolio focused on personal Python and AWS automation projects. Built with semantic HTML and CSS; no build step, JavaScript runtime, or external font dependency.

## Local preview

From the repository directory, run `python3 -m http.server 8000`, then open `http://localhost:8000`.

## Content

- Introduction and contact links
- Four separate project cards linking to public repositories
- Existing public professional experience, education, and certifications
- Technologies demonstrated by the personal projects
- Explicit prototype status and links to implementation limitations

Update the text, project links, and styles in `index.html`. Keep claims tied to demonstrated work and exclude confidential employer details, credentials, and private configuration.

## Deployment

The existing `.github/workflows/static.yml` publishes the repository to GitHub Pages on pushes to `main` or manual workflow dispatch. A pull request does not deploy this update; merging it into `main` triggers the existing workflow.

## Checks before publishing

- Check the layout at desktop and mobile widths.
- Confirm navigation, repository links, LinkedIn, and email links.
- Check keyboard focus and the skip link.
- Confirm project descriptions match the linked implementations.
