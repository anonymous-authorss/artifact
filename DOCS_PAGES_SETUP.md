# Anonymous GitHub Pages Setup

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml` that builds the Sphinx documentation from `docs/source` and deploys it to GitHub Pages.

How to use it safely:

1. Push this repository to the final anonymous GitHub account.
2. In that anonymous repository, enable GitHub Pages with `Source: GitHub Actions`.
3. Let the workflow publish the documentation automatically from the `main` branch.
4. Share only the anonymous Pages URL.

Anonymous-review cautions:

- Do not publish the docs from a repository owned by a real-name or research-group account.
- Do not reuse the original GitHub Pages URL, Read the Docs project, or a custom domain that can be traced back to you.
- Re-check badges, footer links, source links, and any manually added external links before making the site public.
