# Anonymous Review Checklist

This copy was created from `HEAD` of the original repository without git history.

Default anonymization already applied in this copy:

- Removed `dist.zip` so built package metadata does not expose author emails or the original GitHub homepage.
- Replaced the Google Drive dataset link with the Kaggle dataset link in `README.md`, `docs/source/index.rst`, and `docs/source/about.rst`.
- Removed project page, arXiv, original GitHub, and PyPI links from the README and docs landing pages.
- Replaced PyPI-based installation snippets with source-install instructions (`pip install .`) in the README and installation guide.
- Switched README image links from `raw.githubusercontent.com/huiyang-yi/...` to repository-local image paths.
- Replaced package metadata authors in `pyproject.toml` with `Anonymous Authors`.
- Replaced Sphinx author metadata in `docs/source/conf.py` with `Anonymous Authors`.
- Replaced citation author blocks with `Anonymous Authors`.
- Removed direct email contact details from the README and docs pages.

Items to review before making the repository public:

- `README.md`: confirm the anonymous citation block and contact wording are acceptable for review.
- `docs/source/index.rst`: confirm the anonymous citation block and contact wording are acceptable for review.
- `docs/source/about.rst`: confirm the anonymous citation block and contact wording are acceptable for review.
- `pyproject.toml`: decide what `project.urls` value should be after review; it is currently a placeholder.
- `.readthedocs.yaml`: safe to keep in a private copy, but do not connect it to a public Read the Docs project until the public docs destination is anonymous.
- GitHub repository settings: owner account, repository description, website, topics, releases, tags, and Pages/Read the Docs bindings must all be checked manually.
- Git commit identity: create commits in this copy using an anonymous name and email only.

Recommended checks:

- Search for `huiyang-yi`, real names, real emails, the original GitHub URL, the project page URL, the arXiv URL, and the old Google Drive URL before publishing.
- Search for `PyPI` and `pip install causalcompass` if you want to ensure no reviewer-facing instructions still point to the public package index.
- If you later build a wheel or source distribution from this copy, inspect the generated metadata again before uploading it anywhere.
